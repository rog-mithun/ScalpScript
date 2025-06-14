# ⚡ ScalpScript – Nifty 50 Intraday Scalping Strategies

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)

**ScalpScript** is a Pine Script-based indicator and strategy combo for **Nifty 50 intraday traders**. It helps scalpers make informed entry and exit decisions by combining **volatility filtering**, **moving average crossovers**, and **trend confirmation logic** — all within TradingView's charting platform.

---

## 📌 Key Features

- 📉 **VHF + VMA Indicator** for scalping-friendly signal filtering
- 🔁 **VWMA + EMA Strategy** for trend-confirmed backtestable trades
- 🚨 Built-in alert system for Buy/Sell triggers
- 🧠 Noise reduction using Vertical Horizontal Filter (VHF)
- 📊 Plots support visual clarity for real-time decisions
- 🧪 Strategy Tester compatible for backtesting and optimization

---

## 🛠️ Tech Stack

### Scripts:
![Pine Script](https://img.shields.io/badge/Pine--Script-v6-green?style=flat&logo=tradingview)

### Platform:
![TradingView](https://img.shields.io/badge/Platform-TradingView-1e1e1e?style=flat&logo=tradingview&logoColor=blue)

---

## 📁 Project Structure

| File Name                    | Description                                               |
|-----------------------------|-----------------------------------------------------------|
| `Nifty Scalping(VHF + VMA).ps`    | Scalping indicator using Vertical Horizontal Filter and Variable Moving Average |
| `Nifty Scalping(VWMA + EMA).ps`    | Backtestable intraday strategy using Volume Weighted Moving Average and Exponential Moving Average         |
| `README.md`                 | Documentation for the project                             |
| `LICENSE`                   | MIT License file                                          |

---

## 🚀 How to Use on TradingView

1. Open [https://tradingview.com](https://tradingview.com)
2. Go to **Pine Editor** (bottom panel of any chart)
3. Paste the contents of either `.pine` file
4. Click **Add to Chart**
5. Use **Strategy Tester** (for strategy) or customize alerts (for indicator)

---

## 📈 Script Logic Summary

### 🔸 `VHF + VMA` Indicator
- **Buy Signal**: Price crosses above VMA and VHF > threshold
- **Sell Signal**: Price crosses below VMA and VHF > threshold
- **Inputs**: VMA length, VHF length, VHF threshold

### 🔸 `VWMA + EMA` Strategy
- **Long Entry**: Price above both EMA and VWMA, EMA > VWMA
- **Short Entry**: Price below both EMA and VWMA, EMA < VWMA
- **Exits**: Custom take profit and stop loss in points

---

## 💻 Code Previews

> (Add screenshots or GIFs showing the indicator and strategy on a Nifty 5-min chart.)

---

## 🙏 Acknowledgements

📊 Inspired by real-time intraday scalping strategies used in Indian markets  
💡 Thanks to TradingView for their brilliant Pine Script environment

---

## 📖 License

This project is licensed under the [MIT License](LICENSE) © 2025 Mithunsankar S
