# Truffle Pet Shop Starter 

This is a simple dapp that allows users to adopt pets. It is a good starting point for learning how to build a dapp on Truffle.

## Setup

You need to have Truffle installed globally to run the tests and deploy the smart contracts. You can install Truffle by running the following command:

```bash
npm install -g truffle
```

Install the dependencies by running the following command:

```bash
npm install
```

Add in all the necessary environment variables in a `.env` file. You can use the `.env.example` file as a reference.

```bash
cp .env.example .env
```

## Useful Scripts

### Running the tests

To run the tests, run the following command:

```bash
truffle test
```

### Deploying the smart contracts

To deploy the smart contracts to the network specified in `truffle-config.js`, run the following command:

```bash
truffle migrate --network <network>
```

### Verifying the smart contracts on Etherscan

To verify the smart contracts on Etherscan, run the following command:

```bash
truffle run verify <ContractName> --network <network>
```



