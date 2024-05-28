# Goldman_Sachs_Stock_DA
This project involves analyzing historical stock data for Goldman Sachs from May 4, 1999, to July 22, 2021. The analysis covers various aspects such as trends in adjusted close prices, trading volumes, and correlations between different stock metrics.

## Getting Started
To get started with this project, you will need to have the Goldman Sachs stock dataset. Ensure that your dataset file (GS.csv) is placed in the project directory. You can then run the provided Python scripts and Jupyter notebook to perform the analysis.

## Prerequisites
To run the code in this project, you will need to have Python 3.x installed along with the following packages:

pandas
seaborn
matplotlib
You can install these packages using pip:

pip install pandas seaborn matplotlib

## Running the Analysis
To run the analysis, simply execute the provided Jupyter notebook (EDA-Visualization.ipynb). The code will load the data, perform various analyses, and generate visualizations to provide insights into the stock performance of Goldman Sachs.

## Results
The results of the analysis provide several insights:

Adjusted Close Price Trend:

The highest adjusted close price was recorded in 2021.
The lowest adjusted close price occurred during the 2008 financial crisis.
Volume of Trades:

2008 experienced the highest trading volumes, particularly in September, reflecting market volatility during the financial crisis.
The highest volume of trades in a single day was on September 18, 2008.
Weekly Adjusted Close Price in 2021:

The weekly average of adjusted close prices showed an upward trend, indicating strong market performance in 2021.
Open and Close Price Difference:

Analysis revealed periods of both positive and negative differences between open and close prices on a weekly basis.
Correlation Analysis:

Strong positive correlations were found between Open, High, Low, Close, and Adjusted Close prices. Volume had a weaker correlation with these prices.

## Conclusion
The analysis provides valuable insights into the historical performance and volatility of Goldman Sachs' stock. While the logistic regression model may not be the best for predicting stock performance, the visualizations and correlation analysis offer a comprehensive overview of the stock's behavior. Future work could explore other machine learning models, such as random forests or neural networks, to improve predictive performance.
