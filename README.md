# Ethereum Voting System
Ethereum Voting System is a simple, secure, and decentralized voting system powered by Ethereum smart contracts. It was built with Solidity, leveraging OpenZeppelin's safe math operations, and tested with Truffle.

## Getting Started
These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

## Prerequisites
You will need the following tools:

Node.js and npm
Truffle
Ganache (optional, for a personal blockchain)
Installing
Clone the repo:
```
git clone https://github.com/yourusername/ethereum-voting-system.git
cd ethereum-voting-system
```

Install NPM packages:
```
npm install
```

Compile the contracts:
```
truffle compile
```

## Testing
To test the Voting System contracts, run the following command:
```
truffle test
```

## Deployment
After testing, the smart contract can be deployed to a testnet or mainnet using Truffle. Remember to update the truffle-config.js file with the correct network settings before deployment.

## Smart Contract Details
VotingSystem
The VotingSystem contract allows for the creation of candidates and voting for them in a secure and transparent manner. It ensures that a voter can only vote once, and each vote is linked to a unique Ethereum address.

## Methods
vote: This method allows an Ethereum address to cast a vote for a specific candidate. The address cannot vote more than once.

Built With
- Solidity - Ethereum's smart contract programming language
- OpenZeppelin - A library for secure smart contract development
- Truffle - A development environment, testing framework, and asset pipeline for Ethereum

## License
This project is licensed under the MIT License.
