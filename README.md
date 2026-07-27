 Weather Prediction using Machine Learning -

A Python project that predicts tomorrow's maximum temperature using historical weather data and compares three machine learning algorithms.

 What This Project Does:
1. Downloads 3 years of daily historical weather data for any given location using the free Open-Meteo API.
2. Trains and compares 3 models:
   - Linear Regression
   - Decision Tree Regressor
   - Random Forest Regressor
3. Evaluates models based on R² Score, MAE, and RMSE.
4. Uses the best-performing model to predict tomorrow's max temperature in °C.

Technologies Used:
- Python 3
- pandas & numpy (data cleaning & preparation)
- scikit-learn (ML model training & evaluation)
- requests (fetching API data)

 How to Run:

1. Install the required libraries:
   ```bash
   pip install pandas numpy scikit-learn requests matplotlib

EXAMPLE OF THE OUTPUT :

==================================================
WEATHER PREDICTION USING MACHINE LEARNING
==================================================
Enter Latitude : 11.2588
Enter Longitude: 75.7804

Downloading historical weather data...
Data downloaded successfully.
Total records: 1094

==============================
MODEL COMPARISON
==============================

Linear Regression
-------------------------
R² Score : 0.7821
MAE      : 1.15 °C
RMSE     : 1.48 °C

Decision Tree
-------------------------
R² Score : 0.6104
MAE      : 1.52 °C
RMSE     : 1.98 °C

Random Forest
-------------------------
R² Score : 0.8145
MAE      : 1.04 °C
RMSE     : 1.36 °C

==============================
Best Model : Random Forest

==================================================
PREDICTING TOMORROW'S MAXIMUM TEMPERATURE
==================================================
Model Used         : Random Forest
Predicted Max Temp : 31.42 °C
