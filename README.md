# 🌧️ Rain Fall Detection using LSTM

## 🚀 Introduction
This project implements **time-series forecasting** using **LSTM (Long Short-Term Memory)** to predict rainfall based on historical weather data from Australia. By leveraging deep learning models, this project aims to improve the accuracy of weather predictions for better planning and decision-making.

## 🎯 Objective
The primary goal of this project is to predict **rainfall** levels using historical weather data. The project aims to:
- Predict rainfall based on historical patterns.
- Utilize LSTM models for better time-series forecasting.
- Optimize the model performance with hyperparameter tuning.

## 📂 Dataset
- **Source:** [WeatherAUS dataset](https://www.kaggle.com/datasets/uciml/weather-dataset)
- **Instances:** ~10,000 rows of weather data from Australian cities
- **Features:** 23 variables, including:
  - **Response Variable:**
    - **Rainfall** (target variable)
  - **Predictor Variables:**
    - MinTemp, MaxTemp, Rainfall, WindGustSpeed, Humidity, Pressure, CloudCover, and more.

### 📊 Data Insights
- **Rainfall distribution:** A significant portion of records have **no rainfall**.
- **Temperature and Humidity:** Strong seasonal patterns were observed.
- **Missing Values:** Data contained missing values for several features like **RainToday**, **Humidity**, and **Pressure**.

## 🔍 Methodology

### 📈 Exploratory Data Analysis (EDA)
- **Visualizations**: Histograms and box plots to explore distributions.
- **Correlation analysis**: Explored correlations between predictors and the target variable (rainfall).

### 📊 Model Evaluation
- The LSTM model was evaluated using **Root Mean Squared Error (RMSE)**.



## 📍 Challenges
- Handling **missing data** for several features.
- Ensuring **efficient model training** due to large dataset size.
- Tuning the LSTM model's **hyperparameters** for better performance.

## 🚀 Future Improvements
- **Hyperparameter tuning** for improved LSTM accuracy.
- **Deep learning approaches** such as GRU (Gated Recurrent Units).
- **Deployment** as a web application to allow users to predict rainfall for any given city.

## ⚙️ Dependencies
- `numpy`
- `pandas`
- `matplotlib`
- `tensorflow`
- `scikit-learn`
- `keras`

## 📖 References
- Australian Bureau of Meteorology. (n.d.). *Australian Weather Data*.  
- Hochreiter, S., & Schmidhuber, J. (1997). *Long Short-Term Memory.*  
- WeatherAUS dataset. (n.d.). Retrieved from [Kaggle](https://www.kaggle.com/datasets/uciml/weather-dataset).

## 👨‍💻 Author
- **Srikanth Banoth**
