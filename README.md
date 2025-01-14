## ⚠️ Disclaimer: This code is going through audits. It is NOT intended for a production use yet.

**[Symbiotic Protocol](https://symbiotic.fi) is an extremely flexible and permissionless shared security system.**

This repository contains a Symbiotic Staker Rewards interface, its default implementation, and a default Operator Rewards.

## Documentation

Can be found [here](https://docs.symbiotic.fi/core-modules/rewards).

## Technical Documentation

Can be found [here](./specs).

## Usage

### Env

Create `.env` file using a template:

```
ETH_RPC_URL=
ETHERSCAN_API_KEY=
```

\* ETH_RPC_URL is optional.

\* ETHERSCAN_API_KEY is optional.

### Build

```shell
forge build
```

### Test

```shell
forge test
```

### Format

```shell
forge fmt
```

### Gas Snapshots

```shell
forge snapshot
```
