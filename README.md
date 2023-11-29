# Rupees-Price-Prediction using LSTM

## Overview

This project focuses on predicting the exchange rate of US Dollar to Indian Rupees (USD/INR) using Long Short-Term Memory (LSTM) networks. The dataset spans from 2003 to 2021 and is available on Kaggle [here](https://www.kaggle.com/meetnagadia/us-dollar-inr-rupee-dataset20032021).

## Data Preprocessing

### Handling Missing Values

The dataset contains missing values, and they have been addressed using an appropriate imputation technique to ensure the integrity of the data.

### Feature Scaling

To normalize the data and make it suitable for LSTM models, the MinMaxScaler has been applied.

## Model

LSTM has been chosen as the predictive model due to its ability to capture long-term dependencies in sequential data. Other models could be explored based on personal preference and experimentation.

## Evaluation

The overall accuracy of the model has been determined to be 82%, showcasing the effectiveness of the LSTM architecture in predicting the USD to INR exchange rates.

## Kaggle Notebook

The Kaggle notebook for this project can be found [here](https://www.kaggle.com/meetnagadia/rupees-price-prediction-using-rnn-lstm/notebook).

## Dependencies

Make sure to have the necessary dependencies installed to run the code successfully. You can use the `requirements.txt` file or install them manually using:

```bash
pip install -r requirements.txt
```

## Results
The results of the prediction, along with visualizations, can be found in the notebook. Additionally, there are plots using matplotlib to illustrate the model's performance.

## Contributing
Contributions to improve the project are welcome. Feel free to open issues or pull requests.
