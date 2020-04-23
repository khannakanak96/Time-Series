
# About Financial Network
Financial data consists of the number of transactions, bids, pricing and traded stocks worldwide.
It is one of the largest datasets available to researchers. This collection of data has made possible for researchers to predict the future from historical data. One of the sources of financial data is Yahoo! Finance shows a wide expanse of historical data. So, in the first part of the assignment I took the following steps:

Connected with yfinance service as yahoo finance does not exist anymore. Initialize the start and end date to get historical data.
Then I computer the transactional volume by multiplying the volume and adjusted close
Using the company list csv downloaded the historical data for 90+ tickers
Calculated the returns and computed basic statistics on the stock data and after that built a correlation network. 
Minimum spanning trees which is just like a BFS algorithm, it helps us to look at network structure. Using the correlation computed we get similarity of any n stock with respect to other stocks. The graph is plotted by computing the distance between two vertices

# Clustering 
Before performing any kind of analysis on our dataset the first step is to perform exploratory data analysis which can be done by using describe and info functions. Then we compute missing values. 
Found the movement in data by calculating the difference between opening and closing price of the stock. Then normalized the data and then performed PCA dimensionality reduction then predicting the labels 
RESULT: After performing k means we can see that the same kind of companies are in the same clusters.

# Linear Regression Analysis
Created a new dataframe with adjusted close and date. Split the data into 80:20 ratio of training and testing.
Result: Predicted the stock prices with 97% confidence. 

# Time-Series
 I have constructed a linear regression model to predict the return of a ticker, given the returns of an index (SPY).  I have sourced the data, assemble it into a useful form, and transform it as needed.  Finally, I used sklearn to build the model and evaluate it using the RMSE Performance metric.
