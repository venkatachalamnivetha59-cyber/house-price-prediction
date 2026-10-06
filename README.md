# House Price Prediction

## 📌 Project Overview

This project predicts house prices using Machine Learning.

The project uses the Kaggle House Prices dataset and applies Linear Regression to predict the sale price of houses based on selected features.

## 🎯 Objective

The main objective is to build a machine learning model that can predict house prices from property-related features.

## 🛠️ Technologies Used

- Python
- Google Colab
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Linear Regression

## 📊 Dataset

The dataset contains information about residential properties and their sale prices.

Target variable:

`SalePrice`

Selected features used in this project:

- `GrLivArea` - Above ground living area
- `BedroomAbvGr` - Number of bedrooms
- `FullBath` - Number of full bathrooms

## 🔄 Project Workflow

1. Load the dataset
2. Explore the dataset
3. Select relevant features
4. Check for missing values
5. Split the dataset into training and testing data
6. Train a Linear Regression model
7. Generate predictions
8. Evaluate the model
9. Visualize actual vs predicted prices

## 🤖 Machine Learning Model

The project uses **Linear Regression**.

The dataset was divided into:

- 80% Training data
- 20% Testing data

## 📈 Model Evaluation

The Linear Regression model achieved:

| Metric | Result |
|---|---:|
| Mean Absolute Error | 35,788.06 |
| Mean Squared Error | 2,806,426,667.25 |
| R² Score | 0.6341 |

The R² score of approximately **63.41%** indicates that the model explains around 63% of the variation in house prices.

## 📁 Files

- `house_price_prediction.ipynb` - Complete Google Colab notebook containing data analysis, model training, prediction, and evaluation.

## 🚀 Future Improvements

The model can be improved by:

- Using more features
- Handling categorical variables
- Feature engineering
- Trying Random Forest
- Trying Gradient Boosting
- Hyperparameter tuning
- Comparing multiple machine learning models

## 👩‍💻 Author

Nivetha V
