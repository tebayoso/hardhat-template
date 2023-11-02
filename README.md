# Sample Hardhat Project

This repository contains a basic Hardhat setup suitable for Solidity development. Hardhat is an Ethereum development environment designed for professionals, enabling them to compile, deploy, test, and debug Ethereum software. This project includes a simple smart contract, a test suite, and a deployment script.

## Pre-requisites

Before cloning the project and running the tasks, ensure you have the following installed on your system:
- Node.js (version 18)
- npm (Node Package Manager)

## Getting Started

To get started with the Sample Hardhat Project, follow these steps:

1. Clone the repository to your local machine.
2. Navigate to the root directory of the cloned repository.
3. Install the required npm packages by running `npm install`.

## Available Tasks

Hardhat tasks are the cornerstone of Hardhat's functionality. This project comes with the following predefined tasks that you can run:

- `npx hardhat help`: Display a help message with all the available tasks.
- `npx hardhat test`: Run the Mocha tests included in this project.
- `REPORT_GAS=true npx hardhat test`: Run the tests and report gas usage.
- `npx hardhat node`: Start a local Ethereum node.
- `npx hardhat run scripts/deploy.ts`: Run the deployment script to deploy the smart contract to a local or remote network.

## Smart Contract

The sample smart contract is located in the `contracts/` directory. This contract is a basic example to show how a contract can be created and tested using Hardhat.

## Testing

Tests for the smart contract can be found in the `test/` directory. You can add your own tests to this directory to ensure your smart contracts work as expected.

## Deployment

To deploy the contract using Hardhat, use the `npx hardhat run scripts/deploy.ts` command. This will execute the deployment script located in the `scripts/` directory.

## Configuration

The `hardhat.config.ts` file contains the configuration for your Hardhat environment. You can customize your Hardhat setup by modifying this file.

## Support

If you have any questions or run into any issues, feel free to open an issue in the repository or submit a pull request with your fixes and improvements.

Hence, this README provides you with the basic instructions to set up and start interacting with Solidity smart contracts using Hardhat. Explore the `tasks/` directory for more custom tasks that can be run with Hardhat.

Happy coding!
