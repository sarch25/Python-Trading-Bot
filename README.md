# Python Live Trading Bot

## Summary
This live trading bot uses a clear and uncomplicated approach to evaluate real-time market data and produce long and short signals based on the High, Low, Open, and Close values of the last three candles. It was developed using Python code and integrates the Oanda API, Yahoo Finance, and Pandas. The bot's goal is to automate the process of taking positions in the market by utilizing engulfing patterns as entry triggers. It is made to adapt to different financial instruments. 

For example, a long position is indicated if the current candle opens below the two preceding candles and closes above them; a short position is indicated if the candle opens above and closes below. And an automated trade will be made. This is not financial advise.

![Screenshot 2024-04-07 083556](https://github.com/sarch25/Python-Trading-Bot/assets/130470960/7493874c-af8d-4472-9cb7-3ea65502e604)

### Skills Learned

- Integration of APIs and financial data sources for market analysis and trade execution
- Application of technical analysis concepts into Python code, such as engulfing patterns, for generating trading signals
- Automation of trading processes to streamline the execution of trades based on predefined strategies
- Adaptation of trading strategies to different financial instruments, allowing for versatility and scalability

### Tools Used

- Python: Programming language used for coding the trading bot
- Oanda API: Brokerage API utilized for accessing market data and executing trades
- Yahoo Finance: Source of financial market data used for analysis
- Pandas: Python library used for data manipulation and analysis

## Images

#### This Python script is for generating trading signals based on bearish and bullish candlestick patterns. It extracts Open and Close price data from the current and previous periods to identify specific conditions for each pattern. The function returns a signal (1 for bearish, 2 for bullish, and 0 for no clear pattern) and appends the results to a list for further analysis.

![Screenshot 2024-04-04 100636](https://github.com/sarch25/Python-Trading-Bot/assets/130470960/46482be7-003e-4c70-be09-867a43acc6a5)
#

#### The BlockingScheduler from the APScheduler library is configured to execute the trading_job function at specified intervals, running every hour on weekdays (mon-fri) at specific minutes (1, 16, 31, and 46). 
#### Below the code, is a example output that demonstrates a trading transaction, including details such as the order type, instrument (EUR/USD), and the number of units traded. This setup ensures trades are executed systematically at predefined times.

![Screenshot 2024-04-17 262850](https://github.com/sarch25/Python-Trading-Bot/assets/130470960/61e368a9-a319-49a8-b7a7-352ea0cac8c0)

![Screenshot 2024-04-07 083030](https://github.com/sarch25/Python-Trading-Bot/assets/130470960/2a0d5b60-4752-40c9-8e98-24ab59ac3439)


![Screenshot 2024-04-07 083556](https://github.com/sarch25/Python-Trading-Bot/assets/130470960/7493874c-af8d-4472-9cb7-3ea65502e604)

Every screenshot should have some text explaining what the screenshot is about.

Example below.

*Ref 1: Network Diagram*
