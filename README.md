# etf_portfolio

The data feed for this project comes from yahoo finance and can easily be swapped for data feeds from anywhere.

This project has two primary functions:

1) Return the allocation category for a single ETF. For example, VOO should return "Large Blend." This type of simple analysis is helpful 
when doing basic research on ETFs and need **quick** and readily available.

2) Return the allocation category for a portfolio of ETFS, one by one, in a table format, as well as sum up the total allocation breakdown
across the portfolio. For example, a portfolio consisting of SPY, VOO, and VB, will yield in the first table Large Blend, Large Blend, and
Small Blend. In the second table, it should yield the total weight allocated to large blend and small blend across the entire portfolio.

The function here takes in input in 1 of 2 ways:
  a) The user inputs one by one the ETF and the respective weight within the portfolio, clicking "q" once finished
  b) Uploading a CSV file that will automatically be calculated on and sorted through the tables
  
The goal here is to, again, provide a **quick** and easy breakdown of a portfolio without the need for any logins or 3rd party platforms. 
