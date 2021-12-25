# NFT market

### Basic Sample Hardhat Project

This project demonstrates a basic Hardhat use case. It comes with a sample contract, a test for that contract, a sample script that deploys that contract, and an example of a task implementation, which simply lists the available accounts.

Try running some of the following tasks:

```shell
npx hardhat accounts
npx hardhat compile
npx hardhat clean
npx hardhat test
npx hardhat node
node scripts/sample-script.js
npx hardhat help
```


### Setup

Market: 0x54e866C43Ed7EaEf5821de98e8DCaAD39af05ff1 (testnet)
NFT 721: 0x54e866C43Ed7EaEf5821de98e8DCaAD39af05ff1 (testnet)

##### To start project:

```
npx hardhat
888    888                      888 888               888
888    888                      888 888               888
888    888                      888 888               888
8888888888  8888b.  888d888 .d88888 88888b.   8888b.  888888
888    888     "88b 888P"  d88" 888 888 "88b     "88b 888
888    888 .d888888 888    888  888 888  888 .d888888 888
888    888 888  888 888    Y88b 888 888  888 888  888 Y88b.
888    888 "Y888888 888     "Y88888 888  888 "Y888888  "Y888

Welcome to Hardhat v2.8.0

✔ What do you want to do? · Create a basic sample project

✔ Hardhat project root: · /var/www/nft-market
✔ Do you want to add a .gitignore? (Y/n) · y
✔ Do you want to install this sample project's dependencies with npm (@nomiclabs/hardhat-waffle ethereum-waffle chai @nomiclabs/hardhat-ethers ethers)? (Y/n) · y
```

##### Install package:
```
npm install --save-dev dotenv
npm install -D @nomiclabs/hardhat-waffle ethereum-waffle chai @nomiclabs/hardhat-ethers ethers @nomiclabs/hardhat-etherscan hardhat-abi-exporter hardhat-contract-sizer
npm install @openzeppelin/contracts
```

##### Deploy contract:
```
npx hardhat run --network testnet scripts/deploy.js
```

##### Verify contract with hardhat:
```
npx hardhat verify --network testnet 0x5070E94423B75E6a40d185aa3E22964B9F3C03dE 
```