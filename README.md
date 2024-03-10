# ERC721 Marketplace & Collection Smart Contracts

## Overview

This project focuses on the development of ERC721 smart contracts for a decentralized NFT marketplace and ERC721 collection creation. The marketplace enables users to create and fulfill orders securely using ECDSA signatures, ensuring secure transactions. Additionally, the project includes a factory contract, allowing anyone to create their own ERC721 collection without restrictions.

## Features

### ERC721 Marketplace

- **Order Creation**: Users can create sell orders for ERC721 tokens.
- **Buyer Authentication**: Buyers can purchase orders using signer key signatures with ECDSA for secure and authorized transactions.

### ERC721 Collection Factory

- **Permissionless Creation**: Anyone can use the factory contract to create their own ERC721 collection.
- **Unrestricted**: Users can create an unlimited number of collections without any platform-imposed restrictions.

## Technologies Used

- **Solidity**: Smart contracts are developed in Solidity to implement the marketplace and collection creation logic.
- **ECDSA Signatures**: Utilizes ECDSA signatures for secure buyer authentication in the marketplace.
- **Factory Contract**: Implements a factory contract pattern for ERC721 collection creation.
- **Blockchain Integration**: Leverages blockchain technology for decentralized and transparent smart contract execution.

## How to Contribute

Contributions are welcomed! If you're interested in enhancing the smart contracts, adding new features, or improving security, feel free to fork the repository and submit a pull request.

## License

This project is licensed under the [MIT License](LICENSE).
