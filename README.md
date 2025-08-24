# Solana Keypair Extractor: A Local Utility for Developers
This repository contains a lightweight, client-side HTML script designed to assist Solana developers in extracting keypair files. The tool extracts the Base58-encoded private and public keys from a standard `id.json` keypair file, which contains a 64-byte `Uint8Array`.

This utility is intended for developers who require a secure and transparent method to access their Base58 keys for various development or wallet-importing purposes, without relying on external services or web-based applications that may handle sensitive data.

> ### ⚠️ Security Warning
> Your `id.json` keypair file **contains the private key to your wallet** and therefore grants direct control over your funds. Copying or uploading it to a website, even for conversion, is a significant security risk.

This script is intentionally designed as a simple, single-file HTML document to be run locally in your browser. This approach ensures that your private key data never leaves your computer. We strongly recommend that all users:

1. **Examine the code carefully** before use.
2. Run the script **offline**.

This tool is provided as a transparent alternative to online services, but it is the user's responsibility to exercise caution and maintain control over their private key information.

## Usage Instructions
To use this extractor, follow the steps below. No internet connection is required after downloading the file.
1. **Save the file**: Download or save the provided code as a `.html` file.
2. **Open in browser**: Open the file directly in your web browser.
3. **Find your keypair**: Locate your `id.json` file. It's usually in `~/.config/solana/` or `%APPDATA%\Solana\`.

Paste and copy: Copy the entire contents of your `id.json` file and paste it into the text box. The Base58-encoded keys will appear automatically.
