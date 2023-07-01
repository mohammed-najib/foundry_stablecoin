# Stablecoin project

This is a stable coin project writen using foundry for EVM chains.

### Stablecoin Design:

1. Relative Stability: Anchored or Pegged -> $1.00
   1. Chainlink Price feed.
   2. Set a function to exchange ETH & BTC -> $$$
2. Stability Mechanism (Minting): Algorithmic (Decentralized)
   1. People can only mint the stablecoin with enough collateral (coded)
3. Collateral: Exogenous (Crypto)
   1. wETH
   2. wBTC

## Commands

```sh
# Initialize foundry project
forge init

# install openzeppelin
forge install openzeppelin/openzeppelin-contracts@v4.8.3 --no-commit
```
