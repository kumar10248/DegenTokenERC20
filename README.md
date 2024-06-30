# DegenToken

DegenToken is a blockchain-based token designed to support fundraising activities. Built on the Ethereum network, it leverages the ERC20 standard for token implementation, providing a secure and standardized method for token management.

## Features

- **ERC20 Compliance**: Ensures compatibility with the vast ecosystem of Ethereum-based applications and services.
- **Fundraising Support**: Designed to facilitate fundraising by allowing token holders to donate tokens to others.
- **Token Minting**: The organizer can mint new tokens to increase the supply, supporting the fundraising process.
- **Token Burning**: Allows token holders to burn their tokens, reducing the total supply and potentially increasing the value of remaining tokens.
- **Token Redemption**: Enables token holders to redeem tokens for assets, facilitated through integration with the `IGameAsset` interface.

## How It Works

1. **Initialization**: Upon deployment, the contract mints an initial supply of tokens to the organizer's address and sets up the game asset interface.
2. **Minting Tokens**: Only the organizer can mint new tokens, controlling the supply.
3. **Donating Tokens**: Token holders can donate tokens to any address, supporting fundraising activities.
4. **Burning Tokens**: Token holders can voluntarily burn their tokens, reducing the total supply.
5. **Redeeming Tokens**: Token holders with at least one token can redeem it for a game asset, as defined by the `IGameAsset` interface.

## Getting Started

To interact with the DegenToken contract, you will need:

- An Ethereum wallet with ETH for transaction fees.
- A connection to the Ethereum network (e.g., through MetaMask or a similar Ethereum wallet/browser extension).

## Deployment

The contract is deployed on the Ethereum network. You will need to use a tool like Truffle or Hardhat to compile and deploy the contract. Ensure you have set up your deployment scripts with the correct constructor parameters, including the initial token supply and the game asset contract address.

## Contributing

Contributions are welcome! If you have suggestions for improvements or new features, please open an issue or submit a pull request.

## License

DegenToken is released under the MIT License. See the LICENSE file for more details.