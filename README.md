# project1

## Project title: 
### Currency Analysis
![currency-analysis](https://user-images.githubusercontent.com/84065878/131076093-57d70b53-5156-47e6-8c16-632527291c7b.png)

## Project description:
### Analyzing top ten traded currency pairs and giving visualization with key data metrics and providing a potential trading signal.


## Questions to ask are:
###  - What problem does the app attempt to solve? Attempting to create a momentum strategy by using historical data, the RSI indicator, and comparing the selected currency pair with come other top traded currency pairs using the same base currency.



### - How does the app solve this problem at a high-level? We have used tradermate, the main currency pair we focused on was AUDUSD solved by extracting 12 months data from the last trading day using daily data, from that we sliced the data to give us 6 month and 3 month trends, as well as retrieving 1 month data using hourly data. We correlated this with NZD, CAD, EUR, GBP to find any similarities and/or patterns. We used the python library Talib to run an RSI measure on our yearly data to be able to give us a buy, hold or sell signal. The strategy is well known and widely used, being if the RSI gets over ‘70, it is over bought and its time to sell, and if it falls below 30, its over sold and time to sell.

### - What steps were taken to build the app? Registered for API key, read and understood API/SDK documentation. Pulled the data into the code. We saved the data into a CSV file so that we were not pulling as much data due to limited access on the API. We also did this in case we lost any data, we were still able to run our program. We created visual charts to see overall patterns and trends of the pairs, calculated daily returns and correlation. Also showed descriptive statistics to get an overall view of AUDUSD. We used the python library Talib to run an RSI measure on our yearly data to be able to give us a buy, hold or sell signal. The strategy is well known and widely used, being if the RSI gets over ‘70, it is over bought and its time to sell, and if it falls below 30, its over sold and time to sell. 

## Analysis Currencies

 - EUR/USD (Euro/US Dollar)
- NZD/USD (New Zealand Dollar/US Dollar)
- GBP/USD (British Pound/US Dollar)
- USD/CAD (US Dollar/Canadian Dollar)
- AUD/USD (Australian Dollar/US Dollar)

## Data formating
<img width="646" alt="-1" src="https://user-images.githubusercontent.com/84065878/131076171-4bffd833-7082-4fb7-bf81-44548cfb0c91.png"><img width="765" alt="-2" src="https://user-images.githubusercontent.com/84065878/131076196-33c68261-5373-4628-b342-2904148428f0.png">

## Correlation between pairs
<img width="767" alt="-3" src="https://user-images.githubusercontent.com/84065878/131076235-06c0e3ae-8d93-4639-9028-4c90d8c5251d.png">

## Short term 20 day simple moving average
<img width="414" alt="-4" src="https://user-images.githubusercontent.com/84065878/131076320-bd27dbac-d14c-42c5-ac3b-79c9775809e2.png">

## Trading Signal
#### Using the RSI indicator, we have a buy signal
<img width="255" alt="-5" src="https://user-images.githubusercontent.com/84065878/131076337-ad43228b-ae0b-4189-a5d7-c47b5b10a0b1.png">
