### Table of Contents

1. [Installation](#installation)
2. [Project Motivation](#motivation)
3. [Project Description](#description)
4. [Project Outcome](#outcome)
5. [File Descriptions](#files)
6. [Licensing](#licensing)

## Installation <a name="installation"></a>

This code will easily run with the default anaconda packaged libraries. Still, I am mentioning the important ones below:
- Pandas
- Numpy
- Math
- Maplotlib
- Datetime
- ipywidgets

## Project Motivation<a name="motivation"></a>

This project was done out of curiosity to see how does algorithmic trading works.

## Project Description<a name="description"></a>

This is a trading system based on the below Technical Indicators using Python and Jupyter widgets

- Buy when Close price goes above ‘X’ Days Simple Moving Average (SMA).
- Sell when Close price goes below ‘X’ Days Simple Moving Average (SMA).

Note: X is the window size, which is being taken as the user input.

## Project Outcome<a name="outcome"></a>

The project gives following values on a stock and the entire portfolio level:

1. Total P/L
2. Number Of Trades
3. Mean Return Per Trade
4. Profit Factor

The project gives the insight with the help of visualisation plots:

1. The time based trend of the closing stock along with the Simple Moving Average's line.
2. Technical indicators to show buy & sell calls.
3. P&L of every stock for the entire portfolio.

## File Descriptions <a name="files"></a>

1. Technical Indicators.ipynb - Notebook having python code of the entire project
2. close_price (1) (2).csv - Dataset having 20 stocks 10 years daily Close Price (Sample Dataset)

## Licensing <a name="licensing"></a>

Feel free to use the above code as you would like! 