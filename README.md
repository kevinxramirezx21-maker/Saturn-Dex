# Saturn DEX — Next-Gen Perpetual Futures & Prediction Markets on Solana

![Saturn DEX Hero](https://via.placeholder.com/1200x400/0a0a18/8b3dff?text=Saturn+DEX)  
*(Replace with a screenshot of your live app once deployed)*

## Overview

**Saturn DEX** is a sleek, non-custodial decentralized trading platform built for **perpetual futures** and **binary prediction markets** on **Solana**. 

It combines a stunning dark/purple cyberpunk UI with real-time price feeds, multi-wallet support (Phantom, Backpack, Solflare, Trust Wallet, etc.), and a seamless trading experience. The protocol is designed to give users full control of their assets while offering powerful tools for leveraged trading and short-term price predictions.

### Key Features

- **Perpetual Futures Trading**
  - Long / Short positions with up to 100× leverage
  - Market, Limit, Stop orders
  - Real-time order book, depth, and funding rates
  - Live price updates via CoinGecko (easy to upgrade to Pyth/Drift oracles)

- **Prediction Markets**
  - Bet on top cryptocurrencies (BTC, ETH, SOL, BNB, DOGE) in **5 min / 15 min / 30 min** intervals
  - Binary outcomes: **Above** or **Below** a strike price
  - Automatic resolution with visual countdowns
  - Lost bets deposit funds to an EVM treasury address (demo → future cross-chain implementation)

- **Wallet Integration**
  - Native support for **Phantom**, **Backpack**, **Solflare**, **Trust Wallet**, and more
  - Real SOL balance display after connection
  - Secure transaction signing (ready for Drift perp orders)

- **Beautiful UI/UX**
  - Responsive cyberpunk design with Orbitron + Space Grotesk fonts
  - Dark & Light themes
  - Live candlestick-style chart (Canvas-based)
  - Market list, ticker bar, positions panel, and more

- **Tech Stack**
  - Pure vanilla HTML + CSS + JavaScript (single `index.html` for easy deployment)
  - Solana Web3.js for wallet connection
  - CoinGecko API for live prices
  - Future: `@drift-labs/sdk` for real on-chain perpetuals

## Live Demo

[View Saturn DEX →](https://kevinramirez21-maker.github.io/Saturn-Dex)  
*(Update this link after GitHub Pages is enabled)*

## How to Run Locally

1. Clone the repository:
   ```bash
   git clone https://github.com/kevinramirez21-maker/Saturn-Dex.git
   cd Saturn-Dex
