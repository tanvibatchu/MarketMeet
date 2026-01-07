# MarketMeet Robo Advisor 📈  
*A Python-based equity portfolio advisor and optimization engine*
---

## 🧠 Overview

**MarketMeet** is a Python-based investment advisory and portfolio optimization project that constructs a **$1M CAD equity portfolio** designed to closely track major benchmarks (TSX / S&P 500) while minimizing risk.

The project integrates real-world market data and applies **multi-factor screening, correlation analysis, and custom optimization logic** to generate a final portfolio allocation with full risk analytics.

---

## 🚀 Key Features

- 📊 **Market Data Integration**  
  - Pulls historical equity price data using **Yahoo Finance (yfinance)**  
  - Supports Canadian and U.S. equities  

- 🧮 **Multi-Factor Stock Screening Model**
  - Expected returns  
  - Volatility (standard deviation)  
  - Beta relative to TSX / S&P 500  
  - Covariance with benchmarks  
  - Correlation matrices & heatmaps  

- 📈 **Risk Analytics**
  - Portfolio variance and volatility  
  - Correlation analysis across holdings  
  - Benchmark tracking behavior  

- ⚙️ **Custom Portfolio Optimization**
  - Constructs a **$1,000,000 CAD equity portfolio**  
  - Optimization algorithm minimizes variance  
  - Outputs final portfolio weights and allocation  

---

## 📁 Project Structure

---

## 🧩 Tech Stack

- **Language:** Python  
- **Data:** Yahoo Finance (`yfinance`)  
- **Analysis:** NumPy, Pandas  
- **Visualization:** Matplotlib, Seaborn  
- **Finance Concepts:**  
  - Portfolio variance  
  - Beta & covariance  
  - Correlation heatmaps  
  - Benchmark tracking  

---

## 🛠️ How It Works

1. Load equity universe from CSV  
2. Pull historical price data via Yahoo Finance  
3. Compute financial metrics (returns, volatility, beta, covariance)  
4. Screen stocks based on benchmark alignment  
5. Run optimization algorithm to minimize portfolio variance  
6. Generate final portfolio allocation with risk analytics  

---

## ▶️ Running the Project

1. Clone the repository:
2. Install dependencies
3. Open & Run notebook

```bash
git clone https://github.com/tanvibatchu/MarketMeet.git
cd MarketMeet


pip install yfinance pandas numpy matplotlib seaborn

jupyter notebook MarketMeet.ipynb
