# Stock Market Analysis and Prediction

## Overview
This project uses **Python** to analyze and predict stock prices using **Yahoo Finance (yfinance)**. It retrieves historical stock data and applies **technical indicators** (Moving Averages, RSI, Bollinger Bands) to analyze trends. It also predicts stock prices using a **Linear Regression model** instead of deep learning (LSTM) for compatibility with all Python versions.

## Features
- **Retrieve Stock Data**: Download historical stock prices from Yahoo Finance.
- **Calculate Technical Indicators**:
  - Simple Moving Averages (SMA)
  - Relative Strength Index (RSI)
  - Bollinger Bands
- **Train a Machine Learning Model**:
  - Linear Regression for stock price prediction
- **Visualize Stock Trends**:
  - Line chart for stock price movement
  - Actual vs. Predicted stock prices

## Project Structure
```
\stock-market-analysis
│── README.md  # Project documentation
│── stock_predictor.ipynb  # Jupyter Notebook with full code
```

## Installation
### **1. Clone the repository**
```sh
git clone https://github.com/your-username/stock-market-analysis.git
cd stock-market-analysis
```

### **2. Create a virtual environment (optional but recommended)**
```sh
python -m venv env  # Windows
env\Scripts\activate  # Windows
source env/bin/activate  # Mac/Linux
```

### **3. Install dependencies**
```sh
pip install pandas numpy matplotlib scikit-learn yfinance jupyter
```

## Usage
### **Run the Jupyter Notebook**
```sh
jupyter notebook
```
Open `stock_predictor.ipynb` and run the cells to fetch data, analyze trends, and make predictions.

## Sample Visualizations
### **Stock Price with Moving Averages**
![Stock Price](https://github.com/lehlonolo27/stock-market-analysis/blob/main/output.png)

### **Actual vs. Predicted Stock Prices**
![Prediction](https://github.com/lehlonolo27/stock-market-analysis/blob/main/output2.png)

## Dependencies
- Python 3.x
- pandas
- numpy
- matplotlib
- scikit-learn
- yfinance
- jupyter

## Future Improvements
- Add more **machine learning models** (e.g., Random Forest, XGBoost)
- Implement **more indicators** (MACD, ADX)
- **time series forecasting** (ARIMA, Prophet)

## License
This project is open-source under the **MIT License**.

## Contact
For any questions, reach out via [GitHub Issues](https://github.com/lehlonolo27/stock-market-analysis/issues).

