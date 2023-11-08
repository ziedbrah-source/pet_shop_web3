# Ethereum Pet Shop DApp

This repository contains the code for an adoption tracking system for a pet shop built using Ethereum and smart contracts. It is based on the Ethereum Pet Shop tutorial from the Truffle Suite documentation.[Tutorial](https://trufflesuite.com/guides/pet-shop/))

## Getting Started

These instructions will help you get a copy of the project up and running on your local machine for development and testing purposes.

### Prerequisites && Installation

Please refer to the tutorial as this is not the official tutoril, here we gonna just give some steps their value.

### Compilation:
in the compilation of the contracts we can see the generation of the build folder where we can see the .json file for each contract, in which there is the ABI and some other info.

![Screenshot from 2023-11-08 12-40-10](https://github.com/ziedbrah-source/pet_shop_web3/assets/68474414/5b0f05f4-dc5f-4026-a896-b257586e1e8a)

### Migration:
Migration will send the .json to the network of ganache and this will trigger a transaction of "smart contract creation".


### Adoption of a pet:
Having already configured metamask, and by adopting a pet, the code in the front will trigger web3 that will trigger metamask that will ask you for an approval, if you accepted, this will trigger a transaction of type: "user to smart contract"
and this will invoke the functionnality of adotpin in the smart contract that will be executed in the EVM and will use GAS for it that you will pay during the transaction.

#### Entering the website and metamask detected and being triggered to sign in:
![Entering the website and metamask being triggered to sign in](https://github.com/ziedbrah-source/pet_shop_web3/assets/68474414/8e1c5df9-ec03-452f-84da-f2291d1de947)
#### Waiting for the confirmation of the transaction:
![Waiting for the confirmation ( the signature ) of the user](https://github.com/ziedbrah-source/pet_shop_web3/assets/68474414/6f67567b-1ab8-4e12-bf7b-79477fd43975)
#### Transaction confirmed:
![Transaction confirmed](https://github.com/ziedbrah-source/pet_shop_web3/assets/68474414/59d2b885-2693-4ec9-96d1-67a2441860f3)
#### The transaction in ganache network:
![the transaction in ganache network](https://github.com/ziedbrah-source/pet_shop_web3/assets/68474414/930f9386-967b-45e9-959d-8c72c5ea6731)
