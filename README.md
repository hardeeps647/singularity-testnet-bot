# Singularity Finance Testnet

Welcome to the **Singularity Finance Testnet**! 🚀 Follow the instructions below to get started with the testnet, claim tokens, and set up the bot.

---

## 🌟 Quick Links

➡️ **Claim Faucet**: [https://faucet-testnet.singularityfinance.ai/](https://faucet-testnet.singularityfinance.ai/)

➡️ **Connect New Wallet**: [https://singularityfinance.ai/testnet](https://singularityfinance.ai/testnet)


---

## 🛠️ How to Participate

1. **Get Test SFI Tokens** 💰
2. **Swap**: SFI > wSFI or other assets 🔄
3. **Stake 50%** 📈
4. **Claim Reward** 🎉
5. **Bridge SFI** 🌉
6. **Complete Daily Onchain Task & Social Media Task** 📲
7. **Done** ✅
8. **LFG!** 🎯

---

## 🤖 BOT Features

- Multi-Account Support 👥
- Proxy Support 🌐
- Private Key (PK) & Seed Phrase Support 🔑
- Daily Bridge 🌉
- Daily Wrap & Unwrap 🔄
- Daily Stake & Unstake 📈📉
- Daily Claim Staking Reward 🎁
- Setup & Configure Easily ⚙️

---

## 🖥️ Setting up the BOT

### Linux

1. Clone the project repository:
   ```bash
   git clone https://github.com/hardeeps647/singularity-testnet-bot.git && cd singularity-testnet-bot
   ```

2. Install dependencies and set up:
   ```bash
   npm install && npm run setup
   ```

3. Configure your accounts:
 ```bash
   cp accounts/tmp_accounts.js accounts/accounts.js
   nano accounts/accounts.js
   ```

4. Configure the bot settings:
   ```bash
   cp config/config_tmp.js config/config.js
   nano config/config.js
   ```

5. Run the bot:
   ```bash
   npm run start
   ```

### Windows

1. Open Command Prompt or PowerShell.

2. Clone the project repository:
   ```bash
   git clone https://github.com/hardeeps647/singularity-testnet-bot.git
   ```

3. Navigate to the project directory:
   ```bash
   cd singularity-testnet-bot
   ```

4. Install dependencies and set up:
   ```bash
   npm install && npm run setup
   ```

5. Configure your accounts:
   - Navigate to the `accounts` directory.
   - Open `accounts.js` and set up your accounts.

6. Configure the bot settings:
   - Navigate to the `config` directory.
   - Adjust the `config.js` file as needed.

7. Start the bot:
   ```bash
   npm run start
   ```

---

## 🔄 Updating the BOT

To update the bot, follow these steps:

1. Pull the latest changes:
   ```bash
   git pull
   ```
   If you encounter errors:
   ```bash
   git pull --rebase
   ```
   Or:
   ```bash
   git stash && git pull
   ```

2. Update dependencies:
   ```bash
   npm update
   ```

3. Start the bot.

4. Check logs for errors if needed:
   ```bash
   cat log/app.log
   ```

---

## ⚠️ IMPORTANT NOTES

1. **DWYOR** (Do Your Own Research) 🔍
2. Always use a **new wallet** when running the bot. 🛡️
3. **Not responsible for any loss of assets.**
4. If you encounter SQL-related errors, try deleting `database.db`.
5. Any errors during transactions will be retried until successful.
6. The Singularity Dashboard may have a delay — just let the bot run in the background.

---

## 🌟 Contribute

Feel free to fork the repository and contribute by adding new features. Thank you for your support! 🙌
