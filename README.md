# Merkle Airdrop

## Description
The `MerkleAirdrop.sol` contract enables the distribution of ERC-20 tokens. It uses Merkle Proofs to verify address eligibility. It includes a `claim` function that allows addresses to receive the airdrop without paying gas fees. Furthermore, it implements signatures to ensure that only intended recipients can claim the tokens.

## Topics
Solidity, Foundry, OpenZeppelin SafeERC20, Ownable, MerkleProof, EIP712, ECDSA

# Getting Started

## Requirements

- [git](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git)
- [foundry](https://getfoundry.sh/)

## Quickstart

```
git clone https://github.com/lukris02/merkle-airdrop
cd merkle-airdrop
forge build
```

## Deploy

This will default to your local node. You need to have it running in another terminal in order for it to deploy.

```
make deploy
```

## Testing

```
forge test
```
