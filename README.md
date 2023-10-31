# Engulf Indicator

This is a TradingView Pinescript v5 indicator that detects engulfing patterns in price movements and signals potential trend reversals. It is based on the concept of candlestick analysis and average true range (ATR).

## Author

This indicator is created by Cahit Karahan (theomgdev), a software engineer and a passionate trader. You can follow me on Github.

## How it works

The indicator calculates the ratio of the body size to the wick size of each candle and compares it with the ATR value. The higher the ratio, the more likely the candle is an engulfing one. The indicator plots the ratio as an area chart and also draws two horizontal lines at 1 and -1 levels. When the ratio crosses above 1, it indicates an engulfing signal. When the ratio crosses below -1, it indicates an engulfing aftermath.

## How to use it

You can use this indicator to identify potential entry and exit points for your trades. For example, if you are in a long position and the indicator crosses below -1 or above 1, you may consider closing your position or tightening your stop loss. Conversely, if you are in a short position and the indicator crosses above 1 or below -1, you may consider closing your position or trailing your stop loss, because **higher deviation means end of engulfing and potential trend reversal**.

You can also adjust the ATR length and the upper and lower band values according to your preference and trading style. The default values are 14 for ATR length, 1 for upper band, and -1 for lower band.

## Disclaimer

This indicator is for educational and entertainment purposes only. It is not financial advice and it does not guarantee any results. You should always do your own research and analysis before making any trading decisions. Trading involves risk and you may lose more than your initial investment.