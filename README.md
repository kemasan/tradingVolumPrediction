
# TradingVolumePrediction

This project aims to predict the next day's and next week's trading volume of cryptocurrencies using a Supervised Machine Learning model. 
The model utilizes historical trading data and features such as date-related information to make predictions.

Project components:
 - README.md: This file, providing project documentation and instructions.
 - ARBtradingVolumePrediction.ipynb: Python script containing data analysis, model training, and visualization.
    
Requirements:
 - Flipside account (API)
 - Coingecko API 
 - python, pip, jupyter notebook (any other working environment)

Instruction:
 - create an SQL query to fetch historical trading data on Flipside
 - create and activate a virtualenv

Working notebook
Data Source: 
This analysis uses data from the Flipside Crypto API, fetched from:

    "https://flipsidecrypto.xyz/api/v1/queries/50f51f57-95e8-4267-a404-3b2f0acfe93a/data/latest"

Step-by-Step Analysis:

- import Libraries & Load Data:
- import necessary libraries, fetch trader data from the API, and create a pandas DataFrame.

Data Processing
 Download Query Results:
 - Use the Flipside API to download the query results.
 - Load the query results into a Pandas DataFrame.

 Define Features and Target Variable:
 - Identify the features (independent variables) and the target variable (dependent variable) from the DataFrame.
 
 Split Dataset:
 - Split the dataset into training and testing sets. A common split ratio is 80% for training and 20% for testing.
 - Ensure that the split is random and maintains the distribution of the data.

Model Training and Evaluation
 Training the Model:
 - Train the model using the training dataset.
 
 Evaluating the Model:
 - Evaluate the model's performance using the testing dataset.
 - Use appropriate evaluation metrics: Mean Squared Error (MSE), Mean Absolute Error (MAE).
 
 Visualization:
 - Plot the predicted vs. actual trading volumes to visually assess the model's accuracy.
 
 Testing the Model:
 - Use the trained model to make predictions on new, unseen data.
 - Validate the predictions to ensure the model's robustness.


Running the Analysis:
- clone Repository: Clone this repository.
- execute Script: Run the script.
