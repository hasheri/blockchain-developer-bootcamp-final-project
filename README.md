# NFTT Marketplace

This is an open decentralized NFT Marketplace built with smart contracts powered by Ethereum. It basically consists in an open platform where each user can mint his own NFT and expose it on a marketplace. 

## Features
* `Mint`: The user must input a name, description and upload a file (image) to mint his own NFT.
* `Make Offer`: The user can offer his NFT by specifying its price. If someone fulfills this offer, then the ownership is transferred to a new owner.
* `Buy`: A user can buy those NFT which someone else offered. This will require paying the requested price.

## Getting Started
These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

### The repository
First, you will need to `clone` or `fork` the repository into your Github account:
```
$ git clone https://github.com/hasheri/blockchain-developer-bootcamp-final-project.git
```

### Installing
Run the following command in your terminal after cloning the main repo:
```
$ npm install
```

### Running Local Blockchaing and Deployment
```
$ npx hardhat node
$ npx hardhat run scripts/deploy.js --network localhost
```

### Running the Tests
```
$ npx hardhat test
```

### Opening the User Interface
```
$ npm run dev
```