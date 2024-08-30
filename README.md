## Capital Asset Pricing Model (CAPM) Web Application
# Overview
This project is a web application that calculates and visualizes the Capital Asset Pricing Model (CAPM) for selected stocks. The app is built using Python and Streamlit, allowing users to analyze the relationship between expected returns and risk (as measured by Beta) for different stocks.

# Features
Stock Selection: Users can select up to 4 stocks from a predefined list, including TSLA, NFLX, MSFT, MGM, AMZN, NVDA, and GOOGL.
Historical Data: The app fetches historical stock price data from Yahoo Finance for the selected number of years.
SP500 Benchmark: The S&P 500 is used as the benchmark index to calculate Beta values for the selected stocks.
Interactive Visualizations: Users can view the price trends of selected stocks, both raw and normalized, through interactive plots.
Beta Calculation: The app calculates the Beta value for each stock, indicating its volatility relative to the S&P 500.
Expected Return Calculation: Using the CAPM formula, the app computes the expected return for each stock based on its Beta value.
# Web Application
The web application is live and can be accessed here.
https://capm-app-app-ntdnexfa8rcxmgrkbswadi.streamlit.app/

# Technologies Used
Python: Backend logic and data manipulation.
Streamlit: Web application framework for building interactive dashboards.
Yahoo Finance API: For fetching historical stock price data.
Pandas: Data manipulation and analysis.
Plotly: For creating interactive visualizations.
# Usage
Select up to 4 stocks from the provided list.
Choose the number of years for historical data.
The app will display stock price trends, calculate Beta values, and provide expected returns based on the CAPM model.
# Conclusion
This project provides a user-friendly interface for investors and analysts to assess the risk and expected return of different stocks using the CAPM framework.
