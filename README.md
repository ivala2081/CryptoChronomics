# Seasonality Analysis and Trading Strategy for BTC/USDT

![BTC/USDT](https://img.shields.io/badge/Cryptocurrency-BTC/USDT-blue) 
![Python](https://img.shields.io/badge/Python-3.8%2B-green) 
![License](https://img.shields.io/badge/License-MIT-yellow)

This project explores **seasonality patterns** in the BTC/USDT market and develops a **hybrid trading strategy** combining buy-and-hold and active trading. Using advanced techniques like Fourier Transform, LSTM modelling, and Gradient Boosting, we uncover hidden patterns in hourly price data and build a robust trading system.

---

## **Why This Project?**

Cryptocurrency markets are highly volatile and influenced by complex factors, including seasonality. By analyzing historical price data, we can identify recurring patterns (e.g., hourly, daily, or weekly trends) that inform better trading decisions. This project not only uncovers these patterns but also implements a **data-driven trading strategy** to capitalize on them.

---

## **Key Features**

- **Seasonality Analysis:** Identify recurring patterns in BTC/USDT prices using Fourier Transform and autocorrelation.
- **Machine Learning Models:** Predict price movements using LSTM and Gradient Boosting models.
- **Trading Strategy:** Develop a hybrid strategy combining buy-and-hold and active trading with risk management.
- **Visualizations:** Generate insightful plots, including heatmaps, cumulative returns, and residual analysis.

---

## **Methodology**

1. **Data Collection:** Fetch hourly BTC/USDT price data from Binance API.
2. **Preprocessing:** Clean and normalize data, and calculate features like volatility and moving averages.
3. **Seasonality Analysis:** Use Fourier Transform and autocorrelation to detect dominant frequencies and patterns.
4. **Modeling:**
   - **LSTM:** Capture temporal dependencies for price forecasting.
   - **Gradient Boosting:** Interpret feature importance and predict returns.
5. **Trading Strategy:** Implement a hybrid strategy with dynamic risk management (e.g., stop loss, take profit).
6. **Evaluation:** Compare the hybrid strategy’s performance against a buy-and-hold baseline.

---

## **Results**

- **Seasonality Patterns:** Strong hourly and weekly trends were identified, with specific hours (e.g., 12 PM UTC) showing higher returns.
- **Model Performance:** The LSTM model achieved a test loss of **0.000034**, demonstrating its ability to capture complex temporal dependencies.
- **Trading Strategy:** The hybrid strategy outperformed buy-and-hold in certain market conditions, with a **40.74% win rate** and **0.01% average profit per trade**.

---

## **How to Use**

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/your-username/seasonality-analysis-project.git
   cd seasonality-analysis-project
