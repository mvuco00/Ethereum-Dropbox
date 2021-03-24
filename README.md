# Ethereum-Dropbox
<div style="float: right">
<img alt="Ethereum" src="https://img.shields.io/badge/platform-Ethereum-lightgrey"/>
<img alt="Solidity" src="https://img.shields.io/badge/language-Solidity-blue"/>
</div>

Dropbox clone based on Ethereum smart contracts.

<p float="left">
<img src="images/dropbox.png" width="500">
</p>

## Requirements
- MetaMask
- Web3.js
- Ganache

## Built with
- ReactJS
- Solidity


## Commands

- compiling

```
truffle compile
```

- deploying smart contract to blockchain

```
truffle migrate
```

- console

```
truffle console
```

- DStorage is the name of the smart contract that is created in migrations folder. We retrive deployed copy of smart contract and assign it to the variable dstorage

```
dstorage = await DStorage.deployed()
```

- We can access smart contract properties

```
dstorage.address
```

- deploying new copy to the blockchain (if we added some new code)

```
truffle migrate --reset

```
