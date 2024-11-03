# Stock Forecast App

## Description

The Stock Forecast App is a web application built using Streamlit that enables users to visualize and predict stock prices. This app utilizes historical stock data and advanced forecasting techniques using the Prophet library, allowing users to analyze trends and make informed decisions based on stock performance.

## Features

- **Real-time Stock Data**: Fetches the latest stock data for various companies.
- **Interactive Visualization**: Displays stock prices and trends using Plotly for an engaging user experience.
- **Forecasting**: Uses the Prophet model to predict future stock prices based on historical data.
- **Customizable Predictions**: Users can select the stock ticker and define the prediction period (1 to 4 years).

## Technologies Used

- **Python**: Programming language used for developing the app.
- **Streamlit**: Framework for creating the web application interface.
- **yfinance**: Library for downloading stock price data from Yahoo Finance.
- **Prophet**: Forecasting tool developed by Facebook for time series data.
- **Plotly**: Library for creating interactive plots.

## Installation

To run the app locally, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/stock-forecast-app.git
   cd stock-forecast-app

2. Create a virtual environment (optional but recommended):
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows use `venv\Scripts\activate`

3. Install the required packages:
   ```bash
   pip install streamlit prophet yfinance plotly
4. Run the application:
   '''bash
   streamlit run app.py
5. Open your web browser and navigate to http://localhost:8501.
