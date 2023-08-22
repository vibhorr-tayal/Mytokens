# Mytokens
This program is a basic smart contract written in Solidity, a programming language used for developing smart contracts on the Ethereum blockchain.

## Description

The MyToken contract includes these main components:
##### State Variables:
* tokenName: A public string variable that represents the name of the token. In this case, it's set to "Vibhor".
* tokenAbbrv: Another public string variable representing the abbreviation of the token name. It's set to "Vib".
* totalSupply: An unsigned integer representing the total supply of tokens. It's initialized to 0 and will change as tokens are minted or burned.
##### Balance Variable:
* balances: Mapping variable that associates addresses with their respective token balances.
##### Functions:
* mint(address _address, uint _value): Function to mint new tokens and assign them to a specified address.
* burn(address _address, uint _value): Function to burn (destroy) existing tokens.

## Getting Started
### IDE
REMIX: The Native IDE for Web3 Development.
[ https://remix-project.org/ ]
### Execution of the program
* Firstly copy code from this Github Repository
* Verify the solidity version and then compile your code.
* Deploy the smart contract and check for functionality.

## Authors
Vibhor Tayal

## License
This project is licensed under the MIT License.
