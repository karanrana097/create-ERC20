# Create-and-Mint-Token

## Introduction
This repository contains the Solidity smart contract code for the ERC-20 token, designed with basic functionalities such as minting, burning, and transferring the tokens.
This README file provides an overview of the ERC-20 token contract that includes instructions on how to deploy the contract to the local Hardhat test network using Remix Connect Localhost and how to interact with it using Remix in the Hardhat provider environment.

## ERC20 Standard interface functions

- function totalSupply() public view returns (uint256);
- function balanceOf(address tokenOwner) public view returns (uint);
- function allowance(address tokenOwner, address spender)
- public view returns (uint);
- function transfer(address to, uint tokens) public returns (bool);
- function approve(address spender, uint tokens)  public returns (bool);
- function transferFrom(address from, address to, uint tokens) public returns (bool);

#Implementation
##Execution
To run this program, you can use Remix, an online Solidity IDE. Follow these steps:
- Go to the Remix website at https://remix.ethereum.org/.
- Create a new file by clicking on the "+" icon in the left-hand sidebar. Save the file with a .sol extension (e.g., Token.sol).
- Copy and paste the provided code into the file.

## Author
Karan Rana
