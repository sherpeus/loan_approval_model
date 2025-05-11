# Loan Prediction Model

This repository contains a machine learning model to predict loan approval based on a dataset from Kaggle. The model is trained using various features like income, credit history, and loan amount.

## Files

1. **loan_approval_model.pkl** - The trained model.
2. **requirements.txt** - List of necessary Python libraries.

## How to Use

1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/loan-prediction-model.git
2.
pip install -r requirements.txt

3.import pickle

# Load the model
with open('loan_approval_model.pkl', 'rb') as file:
    model = pickle.load(file)

# Use the model to predict loan approval
prediction = model.predict(input_data)

