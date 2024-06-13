# MyToken Solidity Smart Contract

This Solidity smart contract implements a basic token management system that allows minting and burning of tokens. It serves as a foundational example for understanding how to manage token balances on the Ethereum blockchain.

## Description

This contract, named `MyToken`, is written in Solidity, a programming language used for developing smart contracts on the Ethereum blockchain. It includes functionalities to mint new tokens and burn existing tokens based on specified conditions. The contract manages token details such as name, abbreviation, and total supply, providing a basic framework for token management.

## Features

- **Token Details**: Stores the token name, abbreviation, and total supply.
- **Balance Tracking**: Uses a mapping to keep track of token balances for Ethereum addresses.
- **Mint Function**: Allows the creation of new tokens by increasing the total supply and adding tokens to a specified address.
- **Burn Function**: Enables the destruction of tokens by decreasing the total supply and deducting tokens from a specified address, with validation to ensure sufficient balance.

## Getting Started

### Prerequisites

To interact with or deploy this contract, you need:

- An Ethereum development environment or online IDE such as Remix.
- Basic knowledge of Solidity and Ethereum smart contract deployment.

### Deploying the Contract

1. **Online IDE (Remix)**:
   - Go to [Remix IDE](https://remix.ethereum.org/).
   - Create a new file and name it `MyToken.sol`.
   - Copy and paste the contract code into the file.
   - Compile the contract using the Solidity compiler.
   - Deploy the contract and interact with it using Remix's deployment and transaction tools.

### Example Usage

Once deployed, you can interact with the contract to mint new tokens and burn existing tokens as follows:

```solidity
// Mint 100 tokens to address '0xAddress'
myToken.mint(0xAddress, 100);

// Burn 50 tokens from address '0xAddress'
myToken.burn(0xAddress, 50);
```
