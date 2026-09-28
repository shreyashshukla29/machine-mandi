# MachineMandi

MachineMandi is a decentralized machine-to-machine (M2M) marketplace and verification protocol that connects automated hardware with on-chain settlement, cryptographic proof verification, and secure off-chain relayers to enable trustless machine leasing and automated job payments.

## Team Ownership & Responsibilities

- **Member 1**: Blockchain contract, protocol specification, and test suite.
- **Member 2**: MST deployment and cloud/node infrastructure.
- **Member 3**: Backend services, API gateway, and transaction relayer.
- **Member 4**: Embedded device firmware and hardware integration.

> **Note:** The frontend application will be built after the smart contract and backend interfaces have stabilized.

## Repository Structure

```text
machine-mandi/
├── README.md
├── .gitignore
├── LICENSE
├── blockchain/          # Smart contracts, Hardhat test suites, and deployment scripts
├── backend/             # Off-chain services, relayer, device auth, and job management
├── firmware/            # Embedded hardware source code and PlatformIO configurations
├── frontend/            # Web application user interface
├── docs/                # Architecture, protocols, interface specs, and security guides
└── demo/                # Sample proof payloads, job schemas, and demonstration assets
```
