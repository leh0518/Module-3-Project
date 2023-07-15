# Contract Deployment Readme

This readme provides instructions on how to deploy the provided Solidity contract to remix.ethereum.org using a local host network. The contract is a simple token contract that allows minting and burning of tokens, as well as an example function with a requirement.

## Prerequisites
- Internet connection
- Web browser
- remixd installed (if not already installed, run `npm install -g remixd`)

## Deployment Steps

1. Open your terminal and run the following command to start the remixd service:

```remixd

2. Open your web browser and go to [remix.ethereum.org](https://remix.ethereum.org).

3. Once the Remix IDE is loaded, click on the "Open File" icon on the top-left corner of the File Explorer panel.

4. In the "Connect to Localhost" section, click on "Connect to Localhost" to establish a connection to your local host network.

5. In your terminal, run the following command to start a local Ethereum node using Hardhat:

```shell
npx hardhat node
```

6. In the Remix IDE, click on the "Deploy & Run Transactions" tab.

7. From the "Environment" dropdown, select "Web3 Provider".

8. In the "Workspace" section on the left panel, click on "Localhost" to set the workspace to your local host network.

9. Click on the "Compile" button in the Remix IDE to compile the contract.

10. If the contract compiles successfully without any errors, proceed to the next step. If there are compilation errors, review the error messages and make any necessary corrections to the contract code.

11. Click on the "Deploy" button next to the contract name.

12. Confirm the transaction in your Ethereum client.

13. Once the contract is successfully deployed, you can interact with it by calling its functions through the Remix IDE interface.

Congratulations! You have successfully deployed the provided Solidity contract to remix.ethereum.org using a local host network. You can now proceed with testing and utilizing the contract functions as needed.
