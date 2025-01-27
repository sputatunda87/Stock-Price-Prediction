# Stock-Price-Prediction

These Jupyter notebooks provide an in-depth analysis of stock prices using advanced data science techniques. The focus is to first apply Dynamic Time Warping (DTW) within a k-means clustering framework to understand stock performance patterns and group similar stocks based on their historical price movements. Then it aims to predict stock prices using various machine learning techniques, focusing on Linear Regression, Support Vector Regression (SVR), and Long Short-Term Memory (LSTM) models. The analysis is performed on historical stock data from Yahoo Finance.

## Files:

1) Stocks_Cluster.ipynb: The Jupyter notebook containing clustering of stocks and visualisation of elbow method.
2) Stock_Price_Prediction.ipynb: Jupyter notebook containing the code and methodology for training and evaluating the models.
3) stocks_final.csv: This contains a yfinance download of the stock data.


## Data:

File 1 includes daily closing prices of various stocks from Yahoo Finance, covering multiple years to present a comprehensive view of stock behavior.

File 2 contains data used in this project consists of historical stock prices including Open, High, Low, Close, and Adjusted Close prices, sourced from Yahoo Finance. The analysis is done using freely available data; no proprietary or confidential information is utilized.



## Methodology:

Clustering Setup: Utilises the TimeSeriesKMeans clustering method with Dynamic Time Warping (DTW) as the distance metric. This method is particularly adept at handling the alignment and comparison of time-series data which vary in phase.
Elbow Method: To determine the optimal number of clusters, the elbow method is applied by plotting the total within-cluster sum of squares (inertia) against the number of clusters.
Data Preprocessing: The data is first cleaned and preprocessed to handle missing values and ensure consistency in the dataset.
Feature Engineering: New features are engineered from the raw stock prices to enrich the model's input and potentially enhance the clustering results.


## Setup:

To run this project, you will need Python installed on your system along with the following libraries:

pandas
numpy
yfinance
datetime 
ta
pandas_datareader 
scipy
statsmodels
matplotlib
seaborn
plotly
prettytable
sklearn
tensorflow
keras
warnings
tslearn

You can install these packages via pip.


## Running the Notebook:

Download the files into your local machine.
Navigate to the directory containing the project files.
Start the Jupyter notebook server

Open the Stocks_Cluster.ipynb notebook first to run the cells sequentially to understand the clustering of stocks.

Open the Stock_Price_Prediction.ipynb notebook and run the cells sequentially to understand the stock price prediction analysis.

## Note:

File 1 takes a long time to execute.

The models and predictions provided in this project are for academic purposes only and should not be used as financial advice or as a basis for real-time investment decisions.


## Future Work:

Explore different clustering algorithms and their impact on stock categorization.
Apply the clustering results to develop a more robust trading strategy.
Integrate more diverse data sources like fundamental indicators and macroeconomic factors.
Generate buy-sell signals for algorithmic trading

