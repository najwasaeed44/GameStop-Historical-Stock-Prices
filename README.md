<img src="https://i.ibb.co/bJcZLW5/ga-logo.png"  align="middle" width="800">

<br>
<br>
<br>
<h1> Project 4: GameStop Historical Stock Prices </h1>

**Table of Contents:**

- [**Acknowledgment**](#Acknowledgment)
- [**Overview**](#overview)
- [**What is about?**](#what-is-about)
	- [Problem Statement:](#problem-statement)

---

# Acknowledgment
- This data has been taken from [Kaggle](https://www.kaggle.com/hananxx/gamestop-historical-stock-prices) .

(4773, 7)

# **Overview**
- This data contains the name for `4773 day` with `7 features` .<br>
- The data suffers from permanent price discrepancies so it is difficult to get a better than average forecast.<br>


# **What is about?**

## Problem Statement
- GameStop's stocks have spiked in recent days since the Reddit group blew up the stock price. Now GameStop is up more than 1,700% since the start of January. So we will try to predict the stock market for it after everything happen in the market sales for the past months. And identify the adjclose_price for it.
---



## **Data dictionary**

|Feature|Type|Description|
|---|---|---|
|Date|datetime64|The date of trading|
|Open_price|int64|The opening price of the stock|
|High_price|int64|The highest price of that day|
|Low_price|int64|The lowest price of that day|
|Close_price|int64|The closed price of that day|
|Volume_price|int64|The amount of stocks traded during that day|
|Adjclose_price|int64|The stock's closing price has been amended to include any distributions/corporate actions that occur before the next days open|
