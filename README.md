# Prerequisites
Node.js v16 or higher
A wallet private key with testnet tokens
Basic understanding of DeFi and Uniswap V3


# Installation

```
git clone https://github.com/papa-multi/0g-swap-auto.git
cd 0g-swap-auto
```

```
screen -S 0gswap
```

```
npm install
```

# Create a .env file:

```
nano .env
```

```
WALLET_PRIVATE_KEY=your_private_key_here
SWAP_DELAY=60
MIN_BALANCE_FOR_SWAP=0.1
```

# Run the bot:

```
node main.js
```

# Disclaimer
This is a testnet bot. Use at your own risk.
