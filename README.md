# 🎰 Web3 Gaming Platform

A decentralized Web3 gaming platform built on the Ethereum blockchain featuring:

- Mines
- Wheel of Fortune
- Blackjack
- High-Low Card Guessing Game
- Dice Roll
- Snakes and Ladders
- Maze
- Hangman
- Plinco

All games are integrated with **MetaMask** for secure wallet-based interactions and powered by smart contracts for fair and transparent gameplay.

---


## 🛠️ Features

- 🧠 **Smart Contract Logic**: All game logic is handled on-chain using Solidity.
- 🔐 **Wallet Integration**: Seamless MetaMask authentication and ETH transactions.
- 💵 **Real ETH Betting**: Place real ETH bets (testnet or mainnet).
- 🔁 **Streak Multipliers**: High-Low game with multipliers for correct streaks.
- 🎉 **UI Effects**: Confetti, sounds, and smooth animations for an immersive gaming experience.
- ⚖️ **Fairness Guaranteed**: Blockchain-based randomness and provable fairness.

---

## 🧰 Tech Stack

- **Frontend**: React + TailwindCSS
- **Blockchain**: Ethereum (Solidity Smart Contracts)
- **Wallet**: MetaMask (via Ethers.js)
- **Frameworks**: Hardhat(Node.js) / Truffle for contract development & deployment
  

---







---

## 🔧 Installation

### 1. Clone the repo

```bash
https://github.com/AnjaliPai16/Chance.git
cd Chance/new_hardhat-main
npm i
npm install react-confetti
npm hardhat compile
npm run dev
```
###in other terminal
```bash
npx hardhat node
```
###in other terminal
```bash
npx hardhat run scripts/deploy.js --network localhost
###for local host
npx hardhat run scripts/deploy.js --network monad_testnet
### for monad 
```
