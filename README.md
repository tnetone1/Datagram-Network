# Datagram-Network



NOTE: Keep in mind, this is for TESTNET only. The Datagram team will provide more info as things develop. I do not work for the team and this is my contribution to the community. Not financial advice and always do your own research.



# 🧠 Datagram Network - Testnet Node Setup Guide

Welcome to the **Datagram Network Testnet Node** setup guide. This repository helps you quickly get started with running a Datagram node on a Linux VPS (e.g. Ubuntu).

> ✅ Earn **250 points every 6 hours** while your node stays online!
> First off, use my referral link here: https://dashboard.datagram.network?ref=840978636

Create an account or sign in with your Gmail account.
---

## 🚀 Quick Start

### 1. Download the Datagram CLI Binary

First, download the `datagram-cli` binary from the [Datagram Dashboard](https://dashboard.datagram.network?ref=840978636):

> 📦 Visit: [https://dashboard.datagram.network?ref=840978636](https://dashboard.datagram.network?ref=840978636)

If you already have the binary on your local machine, proceed to the next step.

---

### 2. Upload to Your VPS (optional)

If you're starting from your local system and want to move the binary to your VPS:

scp ~/Downloads/datagram-cli-x86_64-linux username@your_server_ip:/root/
Or, if you've stored the binary in this GitHub repo, you can download it directly:

wget https://raw.githubusercontent.com/tnetone1/Datagram-Network/main/datagram-cli-x86_64-linux
chmod +x datagram-cli-x86_64-linux

---

### 3. Make the Binary Executable
SSH into your VPS and set execute permission:


chmod +x datagram-cli-x86_64-linux

---


### 4. Get Your License Key
Go to your Datagram Wallet Licenses.

Copy your license key from the Licenses tab.

---

### 5. Run the Node
Start the node using your license key:


./datagram-cli-x86_64-linux run --key YOUR-LICENSE-KEY
Replace YOUR-LICENSE-KEY with the one you got from your dashboard.

### 6. Verify Node Status
After running, go to your dashboard — your node should show as "Connected".

As long as it remains online, you’ll earn 250 points every 6 hours.
