# HousingPrices
Machine Learning Model for to predict Sale Prices of Houses in Ames Iowa

This project takes in a train and test file with 79 explanatory variables and SalesPrice.

The files are loaded into pandas dataframes and Missing values are replaced with zeros.

PCA and RFECV are run to determine which features to use in predicting SalesPrice.

Finally, Machine learning models are trained using updated dataframes and predictions are output to results files.
