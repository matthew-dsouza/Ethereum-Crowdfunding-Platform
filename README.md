# StartKitt - An Ethereum-based Decentralised Crowdfunding Platform

This project is a Decentralised Crowdfunding Platform built using ReactJS, Vite, JavaScript, Tailwind CSS, Thirdweb SDK, Hardhat, and it can be paired with the Metamask wallet to perform Ethereum transactions on the Goerli testnet of Ethereum.

# Features

Allows users to create and manage crowdfunding campaigns.
Users can contribute funds to campaigns using Ethereum.
Campaign creators can withdraw funds from successful campaigns.
Supports integration with the Metamask wallet for secure and seamless Ethereum transactions.
Built-in support for the Goerli testnet to facilitate testing and development.
Prerequisites

# To run the project locally, you need to have the following tools installed:

Node.js (v14 or above)
npm (Node Package Manager)
Metamask extension for your web browser
Getting Started

# Configuration

The project's configuration can be found in the hardhat.config.js file. You can modify the network settings to connect to different Ethereum networks.

By default, the project is configured to use the Goerli testnet. To deploy the smart contracts and interact with the Goerli testnet, you need to have a Goerli testnet account with test Ether. You can obtain test Ether from the Goerli faucet.

# Deployment

To deploy the smart contracts to the Ethereum network, follow these steps:

Make sure you have configured the desired network in the hardhat.config.js file.
Compile the smart contracts:
bash
Copy code
npx hardhat compile
Deploy the smart contracts:
bash
Copy code
npx hardhat run scripts/deploy.js --network YOUR_NETWORK_NAME
Replace YOUR_NETWORK_NAME with the name of the desired network (e.g., goerli).
Once the deployment is successful, the console will display the addresses of the deployed contracts. Update the contract addresses in the appropriate places in the frontend code (src/contracts folder).

# License

This project is licensed under the MIT License.
