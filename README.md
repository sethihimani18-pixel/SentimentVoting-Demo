# Sentiment-Based Voting Smart Contract

This project is a **voting smart contract influenced by sentiment analysis**, built on the **Flow blockchain**. Votes are weighted based on the simulated sentiment of the voter, allowing positive sentiment votes to count more heavily than negative or neutral ones.

---

## Features

- Voting influenced by sentiment analysis
- Positive sentiment votes carry more weight
- Simple winner calculation
- No input fields for voting; sentiment is pre-set or simulated

---

## Deployed Contract

- **Testnet Contract Address:** `0x1adAEF7E5F7Cb527905E2d250D6332BD5c8b52cB`

---

## Used/Deployed Contracts

- `SentimentVoting` (primary smart contract deployed at the above address)

---

## How to Use

1. Interact with the contract on Flow testnet.
2. Set sentiment for addresses if needed.
3. Call `vote()` to cast a vote influenced by sentiment.
4. Check results using `winner()` function.

---

## Notes

- This is a demo project for **Flow blockchain testnet**.
- Sentiment is currently simulated; in a production scenario, it can be integrated with off-chain sentiment analysis APIs.

