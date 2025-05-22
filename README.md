# Momentum Strategy Backtest (AAPL)

This project implements a simple moving average crossover strategy on Apple (AAPL) stock.  
It buys when the 50-day SMA crosses above the 200-day SMA and sells when it crosses below.

## Key Learnings
- How to fetch data using `yfinance`
- How to compute rolling averages (SMA)
- How to build simple trading signals
- How to compare strategy vs. buy-and-hold
- How to visualise cumulative returns

## Output
![Strategy Plot](strategy plot.png)

The plot above compares the cumulative returns of the simple moving average (SMA) crossover strategy versus a buy-and-hold approach on Apple (AAPL) from 2015 to 2024.

- The **blue line** represents the cumulative return of simply holding AAPL continuously.
- The **orange line** represents the return of the SMA strategy, which enters the market when the 50-day SMA is above the 200-day SMA and exits otherwise.

While the buy-and-hold approach ultimately outperforms in this period, the SMA strategy shows **lower drawdowns** during market downturns — demonstrating its value as a basic trend-following risk management technique.

This backtest highlights both the **potential and limitations** of simple technical strategies when applied to equity markets.


## Tools Used
- Python
- Pandas
- Matplotlib
- yfinance


