# Reef.finance bootnode
### Open source, hosted bootnode for Reef.finance

## How to connect
You can connect to the [Jelly](https://www.jellypool.xyz/staking) bootnode by adding the `--bootnode` parameter when you start your node:
```
./reef-node \
  --chain mainnet \
  --base-path /reef/bootnode \
  --port 30333 \
  --bootnodes /ip4/reef-bootnode.jellypool.xyz/tcp/30333/p2p/PUBLICKEY
  --name MyNode
```

## How to use this Docker version
This dockerized version of the bootnode will generate a node-key on compilation time. Please save these keys in a safe place.
The Dockerfile will take care of starting the node and keep it resilient.

## What is Jelly
Jelly is a sub-project of NextBlu. We want to embrace crypto and we have launched our own validator on Reef.finance. We are now ready to release open tools and nodes for the community.
