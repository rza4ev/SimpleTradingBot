# SimpleTradingBot
At the start of the project, data preparation and calculations were performed using a CSV file named BTCUSDTCSV. These steps include reading, processing and analyzing the data required for the project.
Reading and importing Data:
The BTCUSDTCSV file was uploaded to the DataFrame using the read_csv() function of the pandas library used in the project. This step ensured that the data to be used in the project was made available in the program.
Column Sorting and Data Cleaning:
Separated the relevant columns (Open, Close, High, Low etc.) from the DataFrame. These columns were used in the calculation and analysis of the trading strategy. Also, cleaning operations were performed against any missing or erroneous data in the data.
Moving Average Calculations:

50-day (SMA50) and 200-day (SMA200) simple moving averages were calculated using the ta.ma() function. These moving averages formed the basis of the trading strategy and played an important role in determining the trading signals.
Transactions performed
The operations section was performed after the completion of data preparation and calculations. These steps ensured the implementation of the trading strategy and the observation of its results.
Identifying Buy and Sell Signals:
The intersection points of SMA50 and SMA200 were analyzed and buy and sell signals were identified. Buy signals were determined when the SMA50 crossed the SMA200 upwards, and sell signals were determined when the SMA50 crossed the SMA200 downwards.
Implementation and Monitoring of Results:

Transactions were carried out in accordance with the determined buy or sell signals. In each transaction, details such as the amount of crypto bought or sold, the time of the transaction, and the results obtained from the transaction were tracked. These steps provided an evaluation of the effectiveness of the trading strategy.
These operations cover the process from data preparation to the purchase and sale operations. As a result, the performance of the transaction strategy was evaluated and the project results were obtained.

 Result:
******  STARTING *******
2019-04-25 04:00:00 is that time 0.018467220683287166  BUYING BTC
********
2019-10-27 04:00:00 is that time 0.018467220683287166  selling BTC
********
Last result: 170.45244690674053
2020-02-19 04:00:00 is that time 0.016769041803134623  BUYING BTC
********
2020-03-26 04:00:00 is that time 0.016769041803134623  selling BTC
********
Last result: 111.97410280750523
2020-05-22 04:00:00 is that time 0.012347383878251475  BUYING BTC
********
2021-06-20 04:00:00 is that time 0.012347383878251475  selling BTC
********
Last result: 438.1311122683894
2021-09-16 04:00:00 is that time 0.009104702299213372  BUYING BTC
********
2022-01-15 04:00:00 is that time 0.009104702299213372  selling BTC
********
Last result: 392.0481168160358
2023-02-08 04:00:00 is that time 0.01686920641054591  BUYING BTC
********
2023-09-13 04:00:00 is that time 0.01686920641054591  selling BTC
********
...

 initial amount in the wallet=100$
Sum of proceddure:11
Sum of comission 3.2692648542686054
Sum of wallet 435.901980569147$

