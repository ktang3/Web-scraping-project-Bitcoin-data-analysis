# Web-scraping-project-Bitcoin-data-analysis

This is my first Data Science project in my life :)

## Introduction
Cryptocurrencies have been a trendy topic in recent years, it has more than $2 trillion captial in the market as recorded in August 2021. Which means a huge amount of capital are moving into the crpyto market and people seem to have a stronger confidence than before investing the crpytocurrencies.
In this project, we will take a dive into the most widely-known crpytocurrency, Bitcoin. Price of bitcoin has skyrocketed from $300 in 2015 to $60,000 in 2021, an exceptional upward movement over the years, 200 times, of the price in 2015.

Our aim is to scrape data from web and find some insight of bitcion value in previous years and hope this project can help you understand a little bit more about Bitcoin.


![alt text](https://cdn.i-scmp.com/sites/default/files/d8/images/canvas/2021/03/17/652592dc-d6f4-4c4b-858c-0f974e812f37_e72b9959.jpg)

## Libraries used: 
- BeautifulSoup
- Selenium
- Webdriver
- Pandas
- Seaborn
- Matplotlib


## Columns
1. Date
2. Open
3. High
4. Low
5. Close
6. Adj close
7. Volume

## Webscarping process
We have chosen Yahoo Finance website as our web-scraping source: (https://finance.yahoo.com/quote/BTC-USD/history?period1=1410912000&period2=1629849600&interval=1mo&filter=history&frequency=1mo&includeAdjustedClose=true)
Then, we utilized webdriver from selenium and BeautifulSoup to fetch the data from website. As it is quite messy when we first get the data, so some data cleaning and filtering need to be applied. We only grab the information we want as listed in columns above, date, open, high..etc. Eventually, a dataframe is created for analysis in a later time.

![Screen Shot 2021-12-09 at 8 51 36 PM](https://user-images.githubusercontent.com/88356863/145399883-e0b5d17e-6a3c-47e0-b5bf-28f83752b98a.png)



## Value of bitcoin 2014-2021
![Screen Shot 2021-09-23 at 10 01 27 PM](https://user-images.githubusercontent.com/88356863/134521449-33b5c04b-d13b-4c6d-a284-eb1eba5c93df.png)


## Volume of bitcoin 2014-2021
![Screen Shot 2021-09-23 at 10 08 50 PM](https://user-images.githubusercontent.com/88356863/134522728-43d7b332-974e-4c91-b584-be4e253f1647.png)


## Correlation 
![Screen Shot 2021-09-23 at 10 11 15 PM](https://user-images.githubusercontent.com/88356863/134523122-d7e0420b-23c5-42d5-b4e7-ad89cfcff963.png)


## Average trading volume each month
![Screen Shot 2021-09-23 at 10 12 49 PM](https://user-images.githubusercontent.com/88356863/134523465-5349df3d-5b43-479a-a26b-afe3b6710d5b.png)


## Conclusion
As from our analysis, it shows that long-term holding of bitcoin can be profitbale. On the other hand, short-term investment can be very risky since the price of bitcoin is volatile comparing to other investment types.

Last but not least, if you are already involving in crpytocurrencies or planning to invest in them, I wish you all the best of luck!


# Thank you for reading :)
