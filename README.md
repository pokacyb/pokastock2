**FreeCodeCamp**- Information Security and Quality Assurance
------

Stock Price Checker

**Introduction**

Full stack JavaScript app which checks the Nasdaq stock prices in real time and updates a database.

**Example usage:**

`/api/stock-prices?stock=goog
/api/stock-prices?stock=goog&like=true
/api/stock-prices?stock=goog&stock=msft
/api/stock-prices?stock=goog&stock=msft&like=true`

**Example return:**

`{"stockData":{"stock":"GOOG","price":"786.90","likes":1}}`

`{"stockData":{"stock":"MSFT","price":"62.30","rel_likes":-1},"stock":"GOOG","price":"786.90","rel_likes":1}]}`

[live version](https://pokastock2.pokacyb.repl.co/)

**To do**
- Remove vulnerabilities
- Better the front end of the app
