Portfolio Optimization and Stock Price Predictor
This project focuses on the intersection of finance and data science to create user-friendly portfolio optimization tools. The primary approach is based on the Efficient Frontier theory, a cornerstone of Modern Portfolio Theory. The project further aims to acknowledge the limitations of this traditional optimization approach.

Features:
Portfolio Optimization: Leverage Efficient Frontier theory to find optimal weights for user-provided stock portfolios.
User-Friendly Interaction: Utilizes a simple GUI dialog to gather user input on tickers and their respective weights.
Risk-adjusted Performance Measurement: Compute Sharpe ratio using real-time 10-year treasury rates.
Visual Representation: Graphical representation of optimized portfolios based on maximum Sharpe ratio and minimum volatility.
Note: Predictive functionalities with ARIMA and machine learning models will be added in future updates.

Dependencies:
pandas
numpy
yfinance
pypfopt
matplotlib
fredapi
tkinter
