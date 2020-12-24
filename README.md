# Algorithmic-Trading-Strategy
---
## Building a program that uses the dual moving average crossover to determine when to buy and sell stocks 

I have analysed 3 stocks here 

- ADANI GREEN (NSE)
- BITCOIN (IN USD)
- ETHEREUM (IN USD)

Moreover using this model I bought 2 shares in adani green as a test at Rs 886 on an average, its currently trading at 1040.56 as on 25th Dec so its kinda good for analyzing when to buy and sell some stocks

So, you can use your stock data for this model.

if you dont know how to , you can download historical stock by using yfinance python module as : -

```python
import yfinance as yf 
data = yf.download("AAPL", start="2018-01-01", end="2019-12-31")
#This is for downloading apple (stock symbol : AAPL) data from 1st jan 2018 to 31st December 2019
```
