# NVIDIA (NVDA) Stock Analysis - Jan to Jun 2024

## Data Source
This analysis will use historical daily closing price data for NVIDIA (NVDA) retrieved from Yahoo Finance for the period January 1, 2024 to June 1, 2024.

## Analysis Technique
From researching common Python methods for stock analysis, the **Simple Moving Average (SMA) crossover strategy** appears particularly relevant for analyzing NVDA's performance. This technique involves calculating two moving averages with different time windows (e.g., 30-day and 100-day SMAs) and analyzing where they cross over each other. When the shorter-term SMA crosses above the longer-term SMA, it typically indicates a bullish trend, while the opposite crossover suggests a bearish trend. This method helps smooth out price volatility and identify underlying trends in the data.

## TODO
- Implement the Simple Moving Average crossover analysis technique using the fetched historical data.
- Visualize the closing prices alongside 30-day and 100-day moving averages.
- Analyze crossover points to identify potential buy/sell signals during the study period.