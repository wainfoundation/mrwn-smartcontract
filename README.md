# 🪙 MRWN Token Smart Contract (Coming Soon)

Official smart contract for the **MRWN Token**, powering the decentralized ecosystem of the **Mrwain Organization** built on the **Pi Network**.

MRWN is the utility token used across DApps such as:

- 🌐 **TruthWeb** – Decentralized social commerce
- ☁️ **Cloudy** – Web3 collaboration & storage
- 💳 **QuantumPay** – Payment API using Pi Network
- 🛠️ **TaskHub** – Work-to-earn task platform
- 🧠 **TrendForge** – Trend analysis & media
- 🔗 **DropLink** – Web3 smart link platform
- 🛒 **Salenus** – Pi-powered ecommerce marketplace

---

## 📦 Features

- 🔐 Based on OpenZeppelin ERC20 standard
- 🪙 Mintable and upgradeable for utility
- ⚖️ Role-based permissions for secure control
- ✅ Ready for deployment on Pi Network testnet/mainnet
- 🧪 Fully testable using Hardhat

---

## 🧱 Project Structure

```
mrwn-smartcontract/
├── contracts/           # Smart contracts
├── deploy/              # Deployment scripts
├── scripts/             # Token interactions
├── test/                # Test cases
├── hardhat.config.js    # Hardhat configuration
├── README.md            # Project documentation
└── .env                 # Private keys & secrets
```

---

## 🚀 Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/mrwain-org/mrwn-smartcontract.git
cd mrwn-smartcontract
```

### 2. Install dependencies

```bash
npm install
```

### 3. Configure environment

Create a `.env` file and add:

```
PRIVATE_KEY=your_private_key_here
PI_RPC_URL=https://your-pi-node-or-testnet-rpc
```

### 4. Compile & deploy

```bash
npx hardhat compile
npx hardhat run deploy/00_deploy_mrwn.js --network pi
```

---

## ✅ Testing

```bash
npx hardhat test
```

---

## 🛠️ Built With

- [Solidity](https://soliditylang.org/)
- [Hardhat](https://hardhat.org/)
- [OpenZeppelin Contracts](https://github.com/OpenZeppelin/openzeppelin-contracts)
- [Pi Network](https://minepi.com/)

---

## 📘 License

This project is licensed under the [MIT License](LICENSE).

---

## 📢 Stay Connected

- 🌍 [mrwain.org](https://mrwain.org) *(coming soon)*
- 💬 [@mrwain_org](https://x.com/mrwain_org)
- 📩 support@mrwain.org

> Everything here is open for transparency, so the Pi community can track the evolution of each project and trust the ecosystem we’re building together. 🌐

---

## 🏗️ Badges

![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)
![Build Status](https://img.shields.io/github/actions/workflow/status/mrwain-org/mrwn-smartcontract/ci.yml?branch=main)
![Version](https://img.shields.io/github/package-json/v/mrwain-org/mrwn-smartcontract)
