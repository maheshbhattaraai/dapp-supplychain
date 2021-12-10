# Supply chain & data auditing

## Overview

This DAPP is for a decentralized approach for certifcation schemes, issuance and verification.
Any party can become a Certifier and assign a suitable Authority that can delegate authority of certification

## Deployment Details

https://rinkeby.etherscan.io/address/0xe67F430aEC55CD984A729F9A1e4B0Da3E0F0d5dD
from 0x345434c69B373476e9919E7e21F125e51d19fF68 address

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See deployment for notes on how to deploy the project on a live system.

### Prerequisites

Please make sure you've already installed ganache-cli, Truffle and enabled MetaMask extension in your browser.

### Versions

```
 Truffle : 5.1.33
 Node : v14.16.0
 NPM : 6.14.11
 Sol : ^0.5.0
 @truffle/hdwallet-provider: ^1.0.37,

```

### Installing

```
npm install
```

```
ganache-cli -m "spirit supply whale amount human item harsh scare congress discover talent hamster"
```

In a separate terminal window, test the DApp:

```
truffle compile
truffle migrate
truffle test
```

In a separate terminal window, launch the DApp:

```
npm run dev
```

## Deployment:

To deploy the smart contract to the rinkeby test network below steps were followed -

After running tests:

```
truffle develop
```

to open the truffle console.
Compile and deploy the smart contract using:

```
compile
truffle migrate --reset --network rinkeby
```

## Images:

### Activity Diagram

![Activity Diagram](https://github.com/maheshbhattaraai/dapp-supplychain/blob/main/Images/CoffeeActivity.png)

### Sequence Diagram

![Sequence Diagram](https://github.com/maheshbhattaraai/dapp-supplychain/blob/main/Images/CoffeeSequence.png)

### State Diagram

![State Diagram](https://github.com/maheshbhattaraai/dapp-supplychain/blob/main/Images/CoffeeState.png)

### Class Diagram

![Class Diagram](https://github.com/maheshbhattaraai/dapp-supplychain/blob/main/Images/CoffeeClassDiagram.png)

## Built With

- [Ethereum](https://www.ethereum.org/) - Ethereum is a decentralized platform that runs smart contracts
- [IPFS](https://ipfs.io/) - IPFS is the Distributed Web | A peer-to-peer hypermedia protocol
  to make the web faster, safer, and more open.
- [Truffle Framework](http://truffleframework.com/) - Truffle is the most popular development framework for Ethereum with a mission to make your life a whole lot easier.

## Acknowledgments

- Solidity
- Ganache-cli
- Truffle
- IPFS
- Template code from Udacity
