# bajajhfl-analysis
This project analyzes BAJAJHFL stock prices using time series techniques and ARIMA model. Data was preprocessed, tested for stationarity using ADF, and modeled using ARIMA. The model was used to forecast future stock prices and analyze trends.

Stock Price Analysis using ARIMA – BAJAJHFL
📌 Objective

To analyze and forecast stock prices using ARIMA model.

📥 Data Collection

Data was collected using Yahoo Finance via Python (yfinance library).

🧹 Data Preprocessing

Converted date column to datetime format

Handled missing values using forward fill

Visualized closing price trend

📉 Model Implementation

ADF test performed to check stationarity

Differencing applied

ACF & PACF plots used to determine parameters

ARIMA model applied

🔮 Forecasting

Predicted next 30 days stock prices

Forecast graph plotted

📊 Result

The model shows a (write: upward / downward / stable) trend in BAJAJHFL stock.

⚖️ AI Ethics & Responsible Usage

This project uses publicly available stock data and does not involve personal or sensitive information. Ethical practices were followed.
