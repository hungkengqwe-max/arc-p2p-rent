# arc-p2p-rent

Digital rental escrow on Arc testnet.

- Chain ID: `5042002`
- RPC: `https://rpc.testnet.arc.network`
- USDC: `0x3600000000000000000000000000000000000000`
- Explorer: https://testnet.arcscan.app

## Contract

`src/P2PRent.sol` records USDC payments and emits accounting events.

## Build

```bash
forge build
```

## Deployment

- Contract: `0x6298B993d3078013934336B9FD497B826B966234`
- Tx: `inferred-from-nonce`
- Explorer: https://testnet.arcscan.app/address/0x6298B993d3078013934336B9FD497B826B966234
