# 🏡 Task 3: House Price Prediction using Linear Regression

## 🔍 Objective
The objective of this task is to predict house prices based on features such as number of rooms, lot area, year built, and other relevant variables using a **Linear Regression** model.

## 📊 Dataset
The dataset used contains various features of residential houses, which may include:
- Lot Area
- Overall Quality
- Year Built
- Total Rooms
- Garage Area
- Neighborhood
- Sale Price (target variable)

The dataset was split into **training** and **test** sets to evaluate model performance.

## 🧠 Approach
1. **Data Loading and Exploration**
   - Read the dataset using `pandas`
   - Performed exploratory data analysis (EDA) and handled missing values

2. **Feature Engineering**
   - Selected numeric and relevant categorical features
   - Used one-hot encoding for categorical features
   - Scaled/normalized numerical data where needed

3. **Model Building**
   - Used **Linear Regression** from `sklearn.linear_model`
   - Trained the model using the training data

4. **Model Evaluation**
   - Predicted house prices on the test set
   - Evaluated model using the following metrics:
     - **Mean Absolute Error (MAE)**
     - **Mean Squared Error (MSE)**
     - **Root Mean Squared Error (RMSE)**
     - **R² Score**

## 📈 Evaluation Results

| Metric    | Value         |
|-----------|---------------|
| MAE       | 970043.40     |
| MSE       | 1.75 × 10¹²   |
| RMSE      | 1,324,506.96  |
| R² Score  | 0.6529        |

> The model explains ~65% of the variance in house prices, indicating decent predictive performance for a baseline linear regression model.

## 🛠️ Libraries Used
- `pandas`
- `numpy`
- `matplotlib`
- `seaborn`
- `scikit-learn`

## 📌 Conclusion
This task demonstrated the application of **Linear Regression** for a real-world regression problem. Further improvements could involve:
- Feature selection
- Regularization techniques (Ridge, Lasso)
- Advanced models like Random Forest or XGBoost

