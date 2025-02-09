# Land_Registry-

## Introduction
This project is a **Land Registry System** implemented using **Ethereum Smart Contracts** on the **Remix IDE**. It allows users to register land, transfer ownership, and verify land details securely and transparently using blockchain technology.

## Features
- **Register Land**: Owners can register their land with details like location, size, and price.
- **Ownership Transfer**: Allows secure transfer of land ownership.
- **Transparency & Security**: Uses blockchain to prevent fraud and ensure authenticity.
- **MetaMask Integration**: Enables users to interact with the contract using MetaMask.

## Prerequisites
- **MetaMask Wallet** (Installed in Browser)
- **Remix IDE** (https://remix.ethereum.org/)
- **Solidity Compiler** (In Remix, select Solidity version 0.8.x or appropriate)
- **Ethereum Test Network** (Like Goerli, Sepolia, or Ganache for local testing)

## Smart Contract Implementation
The **LandRegistry.sol** contract includes:
1. **Structs & Mappings**: Stores land details and ownership information.
2. **Modifiers**: Ensures only authorized users can perform certain actions.
3. **Functions**:
   - `registerLand()`: Registers new land with owner details.
   - `transferOwnership()`: Transfers ownership of land.
   - `getLand()`: Retrieves details of a registered land.
   - `isLandRegistered()`: Checks if a given address is the landowner.

## Deployment Steps
1. **Open Remix IDE**: Go to [Remix](https://remix.ethereum.org/).
2. **Create a New File**: Name it `LandRegistry.sol` and paste the smart contract code.
3. **Compile the Contract**:
   - Select the Solidity compiler version (e.g., `0.8.20`).
   - Click **Compile**.
4. **Deploy the Contract**:
   - Select the environment as **Injected Web3** (for MetaMask) or **Remix VM** (for local testing).
   - Click **Deploy**.
   - Approve the transaction in MetaMask.
5. **Interact with the Contract**:
   - Use the deployed contract to register land, transfer ownership, and fetch details.

## Testing
- Use **Ganache** for local testing or deploy on a test network.
- Interact with the contract functions through Remix’s **Deployed Contracts** section.

## Future Enhancements
- Implement **Front-end UI** using React & Web3.js.
- Integrate **IPFS** for storing land documents.
- Add **Multi-signature Approval** for transactions.

## Author
Developed by Sayali Shinde.
