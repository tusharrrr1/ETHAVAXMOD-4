# ERC20 Token Contract - README

This Solidity smart contract implements an ERC20 token called "Degen" (DGN). The contract allows users to transfer tokens, mint new tokens, burn existing tokens, add items to a catalog, redeem items using token balances, and retrieve information about the items.

## Getting Started

To deploy the ERC20 token contract and interact with it, follow these steps:

### Prerequisites

Make sure you have the following software installed on your machine:

- Remix IDE: A web-based integrated development environment for Ethereum smart contracts. Visit [Remix IDE](https://remix.ethereum.org) to access the IDE.
- MetaMask: A browser extension wallet for interacting with Ethereum-based applications. Install MetaMask for your preferred browser and set up an account.

### Deployment on Remix IDE

1. Open the [Remix IDE](https://remix.ethereum.org) in your web browser.

2. Create a new file in Remix IDE and name it `ERC20Token.sol`.

3. Copy the entire content of the ERC20 token contract provided above and paste it into the `ERC20Token.sol` file in Remix IDE.

4. Compile the contract by selecting the appropriate Solidity compiler version (e.g., 0.8.19) in Remix IDE and clicking the "Compile" button.

5. Connect MetaMask to Remix IDE by clicking on the MetaMask extension icon in your browser and following the instructions to log in.

6. Select the desired Ethereum testnet (e.g., Fuji) in MetaMask.

7. Deploy the contract by clicking the "Deploy & Run Transactions" tab in Remix IDE.

8. In the deployment section, select the contract named "ERC20" from the dropdown menu.

9. Click the "Deploy" button to deploy the contract to the selected testnet.

10. Confirm the transaction in MetaMask and wait for the contract to be deployed. Once deployed, you will see the contract address in the Remix IDE.

### Checking on Snowtrace Testnet

1. Open the [Snowtrace](https://testnet.snowtrace.io/) website in your web browser.

2. Enter the contract address obtained from Remix IDE into the search bar on the Snowtrace explorer.

3. Press Enter or click the search icon to retrieve information about the deployed ERC20 token contract.

4. You can now view the contract details, including the token balances, transactions, and other relevant information.

## License

This ERC20 token contract is released under the [MIT License](https://opensource.org/licenses/MIT). Feel free to use, modify, and distribute it as per the terms of the license.

**Note:** It is essential to exercise caution when deploying and interacting with smart contracts. Make sure to thoroughly test and audit the contract code before deploying it to the Ethereum mainnet or any other production environment.
