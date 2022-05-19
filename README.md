# CryptoInvestor

Install the below dependencies: 

1. npm install request 
2. npm install promise
3. npm install parser
4. npm install await
5. npm install yargs



Given no parameters, return the latest portfolio value per token in USD
node fecthCyptoData.js --date=15/7/2019 --token=BTC

Given a token, return the latest portfolio value for that token in USD
node fecthCyptoData.js --date=15/7/2019

Given a date, return the portfolio value per token in USD on that date
node fecthCyptoData.js --token=BTC

Given a date and a token, return the portfolio value of that token in USD on that date
node fecthCyptoData.js

