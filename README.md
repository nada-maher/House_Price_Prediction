# House_Price_Prediction
🏠 California Housing Price Prediction

This project predicts median house values in California districts using the California Housing Dataset.
It compares Linear Regression and Random Forest models to evaluate performance.

📌 Project Workflow

Data Loading & Cleaning

Load housing.csv.

Handle missing values (total_bedrooms filled with median).

Create new engineered features:

rooms_per_household

bedrooms_per_room

population_per_household

Exploratory Data Analysis (EDA)

Correlation heatmap for feature relationships.

Scatter plot of latitude vs longitude colored by house price.

Preprocessing

One-hot encode categorical variable (ocean_proximity).

Scale numeric features using StandardScaler.

Modeling

Linear Regression: Baseline model.

Random Forest Regressor: Advanced ensemble method.

Evaluation Metrics

MAE (Mean Absolute Error)

RMSE (Root Mean Squared Error)

R² Score

Visualization

Actual vs Predicted price plot (for Random Forest).


📊 Results
Model	MAE	RMSE	R²
Linear Regression	~50,000	~70,000	~0.6
Random Forest	~25,000	~45,000	~0.8

✅ Random Forest outperforms Linear Regression in accuracy and prediction stability.

Feature importance plot.

Future Improvements

Add cross-validation for more reliable metrics.

Try Gradient Boosting models (XGBoost, LightGBM).

Hyperparameter tuning with GridSearchCV or RandomizedSearchCV.

Deploy model with Streamlit or Flask API.

Author: Nada Maher Mohamed Elhady 


