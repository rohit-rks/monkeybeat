# monkeybeat

_Generate an equi-weighted portfolio of 10 stocks randomly selected from the NIFTY500 universe and see if it beats the underlying index!_

Visit https://monkeybeat.market and have fun!

## Local Setup

- Clone the repo locally
- Run `docker-compose up` to start a local instance of Clickhouse DB.
- Run `make schema` which creates the database/tables.
- Run `make seed` which loads the database with initial data of last 3 years of stock prices in NIFTY500 universe.
- Run `make fresh` which builds the binary and runs it.
