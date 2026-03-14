<h1 align=center><code>AUR-20 (Aureus Ordinals)</code></h1>

<div align=center>
  <a href="https://github.com/sipherapex/AUR-20-protocol/releases">
    <img src="https://img.shields.io/github/v/release/sipherapex/AUR-20-protocol?color=d4af37&label=version" alt="release version">
  </a>
  <a href="https://github.com/sipherapex/AUR-20-protocol/actions">
    <img src="https://img.shields.io/github/actions/workflow/status/sipherapex/AUR-20-protocol/ci.yaml?branch=master" alt="build status">
  </a>
  <a href="https://github.com/sipherapex/AUR-20-protocol/releases">
    <img src="https://img.shields.io/github/downloads/sipherapex/AUR-20-protocol/total.svg?color=gold" alt="downloads">
  </a>
  <a href="https://discord.gg/YOUR_DISCORD_INVITE">
    <img src="https://img.shields.io/discord/YOUR_DISCORD_ID?logo=discord&label=Discord" alt="chat on discord">
  </a>
  <a href="https://t.me/AureusCore">
    <img src="https://img.shields.io/badge/Telegram-Chat-blue?logo=telegram" alt="chat on telegram">
  </a>
</div>

<br>

`AUR-20` is an index, block explorer, and command-line wallet specifically engineered for the **Aureus Core ($AURE)** SHA-256 blockchain. It implements the **Ordinal Theory** for Aureus, enabling the inscription of digital artifacts and the deployment of Runes on a secure Layer-1.

> **Warning:** AUR-20 is highly technical and experimental software. Use it at your own risk.

## 🏛️ What is Aureus Ordinal Theory?

Ordinal theory imbues "Units" (the satoshis of Aureus) with numismatic value, allowing them to be collected and traded as unique digital artifacts. 

- **Inscriptions:** Native, 100% on-chain NFTs stored in the Aureus witness data.
- **Runes/Tokens:** UTXO-based fungible tokens with zero network bloat.
- **Sovereign Assets:** Your art and tokens live as long as the Aureus Core network exists.

## 🚀 Quick Start (Pre-built Binaries)

For those who want to start immediately, we provide **Pre-built Binaries** in the [Releases](https://github.com/sipherapex/AUR-20-protocol/releases) section.

1. Download the version compatible with your OS (Linux/Windows).
2. Extract the file.
3. Run `./ord --version` to verify the installation.

## ⚙️ Installation & Building

### Prerequisites
- **Aureus Core Node:** You must have a synced `aureusd` node running with `-txindex=1`.
- **Rust:** Required for building from source (v1.79.0+).

### Building from Source
```bash
# Clone the protocol
git clone [https://github.com/sipherapex/AUR-20-protocol.git](https://github.com/sipherapex/AUR-20-protocol.git)
cd AUR-20-protocol

# Build the release
cargo build --release
The binary will be available at ./target/release/ord.

🛡️ Wallet Security
ord relies on Aureus Core for private key management.

Important: Do not use your primary mining wallet with ord. Keep a separate wallet for inscriptions.

Always use the --name flag to specify your wallet: ord wallet --name my_inscriptions create.

🌐 Official Resources
Website: aureuscoin.site

Ord Explorer: ord.aureuscoin.site

Core GitHub: Aureus Core

Rust Library: Aureus Rust Lib

💰 Support the Research
Aureus Core and the AUR-20 Protocol are open-source and community-funded. Your donations support server costs, development, and the expansion of the Aureus Empire.

Donate Bitcoin (BTC):
124Knwzrib1wwv5VFrCdiMEs7HTZrRkXdS

Donate Aureus ($AURE):
aur1qg5gd2zhsx757wjfkxc7ew8m4rp5vxl0mkaelek

🤝 Community
Join the sovereign movement and chat with fellow researchers:

Discord: https://discord.gg/gfaFPDxnqS

Telegram: https://t.me/AUREUS_AUR

Stay Sovereign. Stay Aureus. 🔱
