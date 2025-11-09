# Spot Volume Crypto Tracker

This free Spot Volume Crypto Tracker script lets you scrape high spot volume crypto tokens from CoinGecko, CoinMarketCap, LiveCoinWatch, and CoinRanking, whose 24-hour trading volume flipped their market cap or is greater than 75% of their market cap. And large caps' volume is >= 50% of their market cap. 

**It is tweakable**; if you know your way around Python, HTML, and CSS, then you can easily customize it to meet your preferred criteria, be it 4 hrs, 6 hrs, 12 hrs, or 24 hrs.

# Demo

![Demo Screenshot] (https://raw.githubusercontent.com/traderabba/Spot-Volume-Crypto-Tracker/refs/heads/Assets/screenshot.jpg)

# Features

- No complex work required
- Faster execution
- Clear summary during execution
- Redundancy filtering
- Cross verification for data efficiency
- High verification count = high efficiency
- Tweakable

# Installation Guide

Follow the steps below to successfully implement the scraper:

1. Install the **Pydroid3** app and install the "**requests**" library in the PIP section.

2. Import the scraper version of your choice.

3. For **Scraper v1**, you only need the CoinMarketCap API key from https://pro.coinmarketcap.com/signup/ and  replace API_CODE_GOES_HERE with it.

4. For **Scraper v2**, get API keys from the following platforms and replace them with "your_cmc_api_key_here," "your_lcw_api_key_here," and "your_cr_api_key_here" in the script.
 - https://pro.coinmarketcap.com/signup/
 - https://www.livecoinwatch.com/tools/api
 - https://coinranking.com/api

5. Now, run the script; details will emerge during the run, and after completion, it will save the results in a CSV file and a very responsive HTML file in the **Download** folder of your device.

6. You can view the CSV file using the CSV Viewer app and export it to PDF.

# Version 2.0 Change Log
