# LSTM for Stock Price Forecasting – Univariate & Multivariate Time Series

This project explores the use of Long Short-Term Memory (LSTM) networks for predicting stock prices using univariate and multivariate time series. It applies Keras and TensorFlow utilities on real-world stock datasets.

---

## 🔍 Project Breakdown

### 📈 1. Univariate LSTM Forecasting
- Forecasted the “Open” price using previous 60 days of open prices.
- Used a new stock other than Apple, extending data until Nov 2, 2023.
- Visualized predictions vs. actual prices.

### 🔁 2. Using `tf.keras.utils.timeseries_dataset_from_array`
- Refactored the code to use the built-in timeseries utility.
- Ensured same accuracy and behavior as manual feature creation.

### 📊 3. Multivariate Time Series Forecasting
- Used a 5-dimensional input sequence (Open, High, Low, Close, Volume).
- Maintained 60-day window size and predicted only the Open price.
- Compared training loss and test accuracy with the univariate model.

---

## 📁 Files Included

- `lstm-univariate-stock-forecasting.html`
- `lstm-timeseries-dataset-api-version.html`
- `lstm-multivariate-stock-forecasting.html`
- `lstm-stock-prediction-overview.docx`

---

## 🛠 Tools Used

- Python 3.x  
- TensorFlow / Keras  
- Yahoo Finance (via `yfinance`)  
- `tf.keras.utils.timeseries_dataset_from_array`  
- Google Colab

---

> This project helped refine sequence modeling, time series dataset handling, and multivariate forecasting with LSTM networks.
