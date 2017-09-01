# NODE40 Interview Programming Challenge
### Level 1

## Objective

In as much time as needed, produce a text price table of the recent price of Bitcoin and Dash from two separate sources (optionally, find a third). Note: The value of Dash is expressed in terms of percentage of Bitcoin in the APIs.


## Requirements

1. Sources:
    * Bitcoin (BTC/BTC) and Dash (DASH/BTC) <https://www.worldcoinindex.com/apiservice/json?key=<get a free key>>
    * Bitcoin <http://api.bitcoincharts.com/v1/weighted_prices.json> (use the percentage of BTC from source a to calculate the value of Dash in USD from source b)
2. Solution must be written in Java or Groovy. Groovy will be easier and is recommended.
3. Solution must have two run modes: prod and test. The production mode will display only the table. The test mode will print out meaningful debugging data to the operator and ultimately display the table. The mode may be set at runtime via an [optional] command line flag.
4. Be ready to explain your solution and decision making process.

## Optional

Fetch data from sources in parallel threads.
