# Custom Token Contract 
This repository contains a custom token contract developed for an assessment challenge. The contract includes features such as minting, burning, and balance tracking, adhering to Solidity and Ethereum smart contract principles.


## Description

An assessment challenge led to the development of a unique token contract, which is available in this repository. All of the following conditions are met by the contract:

Name, short form, and total supply of the token are among the important information kept in public variables.
maintains track of token holdings using an address-to-balance mapping.

increases the balance of a given address and the overall supply of tokens to be created by implementing a mint function.
boasts a burn feature that lets you destroy tokens to lower the amount in circulation as well as the balance associated with a specific address.
In order to guarantee that the account balance is adequate for the designated burn amount, the burn function includes conditionals.
Demonstrating a mastery of Ethereum and Solidity smart contract development principles, this project offers a basic grasp of token creation and maintenance.

## Getting Started

### Installing
To run this program, you can use Remix, an online Solidity IDE. To get started, go to the Remix website at https://remix.ethereum.org/.

Once you are on the Remix website, create a new file by clicking on the "+" icon in the left-hand sidebar. Save the file with a .sol extension (e.g., Tokens.sol). Copy and paste the following code into the file:

### Executing program

To compile the code, click on the "Solidity Compiler" tab in the left-hand sidebar. Make sure the "Compiler" option is set to "0.8.18" (or another compatible version), and then click on the "Compile Tokens.sol" button.
![image](https://github.com/vikash-kumar-mahto/Solidity-Assessment-1/assets/93486699/d13918d6-fba5-4814-b50a-bb3852a97f2a)

Once the code is compiled, you can deploy the contract by clicking on the "Deploy & Run Transactions" tab in the left-hand sidebar. Select the "Tokens" contract from the dropdown menu, and then click on the "Deploy" button.

Once the contract is deployed, you can interact with it by calling the burn and mint function. and you can modify the value of the fuctions using the addresses and deploy it accordingly

## Help
if there is any issue while compiling the code then make sure the compiler version which you have written in the code must be the same when you selecting the compiler.

## Authors

Vikash Kumar Mahto
[@Vikash](https://www.linkedin.com/in/vikash-kumar12122002/)

## License

This project is licensed under the [MIT] License - see the LICENSE.md file for details
