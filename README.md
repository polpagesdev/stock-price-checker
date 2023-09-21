# Stock Price Checker
RESTful API that allows users to get the current price of a stock.

The API can be accessed by sending a GET request to the following URL, with the stock symbol in the query string:
https://stock-price-checker.freecodecamp.rocks/api/stock-prices?stock={stock_symbol}

For example, to get the current price of Google stock, you would send the following request:
https://stock-price-checker.freecodecamp.rocks/api/stock-prices?stock=GOOG

The response will be a JSON object with the following properties:
{
  "stock": "GOOG",
  "price": 786.90
}

The API is implemented using the Express framework and Node.js. The stock price data is obtained from the IEX Cloud API.

You can see the live version of the code and running app in my Repl: https://replit.com/@polpages1999/stock-price-checker?v=1
