# House Price Prediction using Linear Regression

This project implements a simple *Linear Regression model* to predict house prices based on features like square footage (sqft), number of bedrooms, and number of bathrooms. The implementation is done using Python and scikit-learn.

## 📊 Project Overview

- *Goal:* Predict the price of houses using a linear regression model.
- *Features used:*  
  - Square Footage (sqft)  
  - Number of Bedrooms  
  - Number of Bathrooms  
- *Target Variable:*  
  - House Price (price)

## 🛠 Technologies Used

- Python
- pandas
- NumPy
- scikit-learn
- matplotlib

## 📁 Dataset

A sample dataset is created within the script. Each row represents a house with features and the corresponding price. You can also replace it with your own .csv dataset.

```python
data = {
    'sqft': [1500, 1800, 2400, 3000, 3500, 1200, 1700, 2100, 2600, 3200],
    'bedrooms': [3, 4, 3, 5, 4, 2, 3, 4, 3, 5],
    'bathrooms': [2, 3, 2, 4, 3, 1, 2, 3, 2, 4],
    'price': [300000, 400000, 450000, 600000, 650000, 200000, 320000, 430000, 480000, 610000]
}