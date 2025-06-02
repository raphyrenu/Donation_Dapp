
# 🎓 Decentralized Scholarship Donation DApp

A fully functional decentralized application (DApp) built on the Ethereum blockchain that allows users to:

- 💰 Donate ETH to a scholarship fund
- 📄 Apply for scholarships
- 🔐 Allow the admin to release funds to applicants

Built with:
- ✅ Solidity (Smart Contract)
- ✅ Truffle (Development Framework)
- ✅ Ganache (Local Ethereum Blockchain)
- ✅ MetaMask (Wallet Integration)
- ✅ Web3.js (Blockchain Interaction)
- ✅ HTML/CSS/JavaScript (Frontend)

---

## 🚀 Preview

![DApp Preview](./dapp-preview.png)

> Replace the image file `dapp-preview.png` with a screenshot of your app.

# 🎓 Decentralized Scholarship Funding (Donation DApp)

A simple decentralized application (DApp) that allows donors to fund scholarships and students to apply for financial support. Built using Solidity, Truffle, and Web3.js.

---

## 📁 Project Structure

```
donation-dapp/
│
├── contracts/
│   └── Scholarship.sol
│
├── migrations/
│   └── 1_deploy_contract.js
│
├── client/
│   ├── index.html
│   └── web3.js
│
├── build/               # Auto-generated after compile
├── truffle-config.js
└── README.md
```

---

## 🛠️ Installation & Setup

### 1. Install Dependencies

Install global dependencies:

```bash
npm install -g truffle
npm install -g ganache-cli
npm install -g http-server
```

Initialize local project dependencies:

```bash
cd donation-dapp
npm init -y
npm install web3
```

---

### 2. Start Ganache

Start your local blockchain environment:

```bash
ganache-cli
```

Leave this terminal running while testing your DApp.

---

### 3. Compile & Deploy Smart Contract

In a separate terminal:

```bash
truffle compile
truffle migrate --reset
```

After migration, copy the **deployed contract address** and update this line in `client/web3.js`:

```js
const contractAddress = "PASTE_HERE";
```

---

### 4. Serve the Frontend

Navigate to the `client` directory and run a local web server:

```bash
cd client
npx http-server
```
---

Open your browser to [http://localhost:8080](http://localhost:8080)

---

## 🦊 MetaMask Setup

1. Install MetaMask extension in your browser
2. Import Ganache account using mnemonic/private key
3. Add a custom network:
   - Network Name: Ganache
   - RPC URL: http://127.0.0.1:8545
   - Chain ID: 1337
4. Connect wallet from the DApp interface

---

## 🧪 Usage

1. **Connect Wallet**
2. **Donate ETH**
3. **Apply for Scholarship**
4. **Admin Releases Funds** to recipient addresses

---

## 📷 Screenshots

> Insert your UI screenshots here

\`\`\`markdown
![Home Page](./screenshots/home.png)
![MetaMask Prompt](./screenshots/metamask.png)
\`\`\`

---

## 🧾 License

This project is licensed under the MIT License.

---

## 🙋 Author

**Nibishaka Raphael**
Fullstack Developer & Cybersecurity Engineer
[Rwanda Coding Academy](https://rca.ac.rw)

---

## 🌐 Resources

- [Truffle Docs](https://trufflesuite.com/docs/)
- [Web3.js Docs](https://web3js.readthedocs.io/)
- [Ganache](https://trufflesuite.com/ganache/)
- [MetaMask](https://metamask.io/)
