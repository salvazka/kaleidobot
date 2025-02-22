## Join My Telegram Channel:
- https://t.me/Drophunterxyzz

## Kaleido Mining Bot
•Kaleido Mining Bot is an automated script for mining KLDO tokens from Kaleido Finance Testnet. It enables multi-wallet mining while following Kaleido's latest security measures to avoid bans and rate limits.

## Register
- https://kaleidofinance.xyz/testnet?ref=1BDVMN0E

## 📌 Key Features
✅ **Session Management**
•Saves each wallet's mining session in a session_{wallet}.json file.
•Resumes previous sessions upon restart.

✅ **Auto-Retry & Error Handling**
•Exponential Backoff: If an API error occurs, the script retries with an increasing delay.
•Status Code Handling: Handles 400, 401 errors (permanent failure) and 429, 5xx errors (retry with delay).

✅ **Mining Status & Earnings Tracking**
•Displays mining statistics

✅ **Referral Bonus System**
•Automatically detects and applies referral bonuses to mining earnings.

✅ **Cross-Platform Compatibility**:
•Works on Windows, macOS, Linux, *Android (run with ubuntu proot/chroot).

## ⚙️ Installation

1. Clone the repository:
   ```bash
   git@github.com:salvazka/kaleidobot.git
   ```
2. Install dependencies:
   ```bash
   npm install
   ```
3. Edit the wallets.json file using nano/vim, then add your wallet addresses (one per line):
   ```bash
   nano wallets.json
   ```
4. Run Bot
   ```bash
   npm run start
   ```

## 🔄 Updating the Script

**To keep your bot up-to-date with the latest improvements and fixes, simply run the following command in your project directory:**

```bash
   git pull origin main
```

## 📜 License

**This project is available under the [MIT](https://github.com/salvazka/kaleidobot/blob/main/LICENSE) License. Feel free to use and modify it as needed.**
