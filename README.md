OVERVIEW
This Solidity smart contract defines a simple token named "META" with the abbreviation "MTA". It includes functionalities for minting and burning tokens, and maintaining token balances for addresses.

CONTRACT DETAILS
  PUBLIC VARIABLES
  tokenName: Name of the token, "META".
  tokenAbbrv: Abbreviation of the token, "MTA".
  totalSupply: Total supply of tokens, initially 0.
  
  MAPPINGS
  balances: Tracks token balances for each address.
  
  FUNCTIONS
  mint(address _address, uint _value): Mints _value tokens to _address, increasing totalSupply.
  burn(address _address, uint _value): Burns _value tokens from _address, decreasing totalSupply if the address has enough tokens.
  
USAGE
Deploy the contract to an Ethereum-compatible blockchain. Interact using:

Minting Tokens: mint(address _address, uint _value)
Burning Tokens: burn(address _address, uint _value)

This project is licensed under the MIT License - see the LICENSE.md file for details
