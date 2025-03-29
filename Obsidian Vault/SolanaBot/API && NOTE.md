### API

Trades
- Past 24 Hour Trades by Pool Address
	get https://pro-api.coingecko.com/api/v3/onchain/networks/{network}/pools/{pool_address}/trades

This endpoint allows you to **query the last 300 trades in the past 24 hours based on the provided pool address**

Trending
- Trending Search List
	get https://pro-api.coingecko.com/api/v3/search/trending

This endpoint allows you **query trending search coins, nfts and categories on CoinGecko in the last 24 hours**.

Search
- Search Queries
	get https://pro-api.coingecko.com/api/v3/search

This endpoint allows you to **search for coins, categories and markets listed on CoinGecko**.

Exchange Rates
- BTC-to-Currency Exchange Rates
	get https://pro-api.coingecko.com/api/v3/exchange_rates

This endpoint allows you to **query BTC exchange rates with other currencies**.

Exchanges
- Exchanges List with data
	get https://pro-api.coingecko.com/api/v3/exchanges

This endpoint allows you to **query all the supported exchanges with exchanges’ data (id, name, country, .... etc) that have active trading volumes on CoinGecko**.
- Exchange Data by ID
	get https://pro-api.coingecko.com/api/v3/exchanges/{id}

This endpoint allows you to **query exchange’s data (name, year established, country, .... etc), exchange volume in BTC and top 100 tickers based on exchange’s id**.
- Exchange Volume Chart by ID
	get https://pro-api.coingecko.com/api/v3/exchanges/{id}/volume_chart

This endpoint allows you to **query the historical volume chart data with time in UNIX and trading volume data in BTC based on exchange’s id**.

Coins
- Coins List with Market Data
	get https://pro-api.coingecko.com/api/v3/coins/markets

This endpoint allows you to **query all the supported coins with price, market cap, volume and market related data**.
- Coin Data by ID
	get https://pro-api.coingecko.com/api/v3/coins/{id}

This endpoint allows you to **query all the coin data of a coin (name, price, market .... including exchange tickers) on CoinGecko coin page based on a particular coin id**.
- Coin Historical Data by ID
	get https://pro-api.coingecko.com/api/v3/coins/{id}/history

This endpoint allows you to **query the historical data (price, market cap, 24hrs volume, etc) at a given date for a coin based on a particular coin id**.
- Coin Historical Chart Data by ID
	get https://pro-api.coingecko.com/api/v3/coins/{id}/market_chart

This endpoint allows you to **get the historical chart data of a coin including time in UNIX, price, market cap and 24hrs volume based on particular coin id**.
- Coin Historical Chart Data within Time Range by ID
	get https://pro-api.coingecko.com/api/v3/coins/{id}/market_chart/range

This endpoint allows you to **get the historical chart data of a coin within certain time range in UNIX along with price, market cap and 24hrs volume based on particular coin id**.

Contracts
- Coin Historical Chart Data by Token Address
	get https://pro-api.coingecko.com/api/v3/coins/{id}/contract/{contract_address}/market_chart

This endpoint allows you to **get the historical chart data including time in UNIX, price, market cap and 24hrs volume based on asset platform and particular token contract address**.
- Coin Historical Chart Data within Time Range by Token Address
	get https://pro-api.coingecko.com/api/v3/coins/{id}/contract/{contract_address}/market_chart/range

This endpoint allows you to **get the historical chart data within certain time range in UNIX along with price, market cap and 24hrs volume based on asset platform and particular token contract address**.

Simple
- Coin Price by IDs
get https://pro-api.coingecko.com/api/v3/simple/price

This endpoint allows you to **query the prices of one or more coins by using their unique Coin API IDs**.
- Coin Price by Token Addresses
	get https://pro-api.coingecko.com/api/v3/simple/token_price/{id}

This endpoint allows you to **query a token price by using token contract address**.

### Note
Remove [pro-] from the begining of the api link to use the demo version

