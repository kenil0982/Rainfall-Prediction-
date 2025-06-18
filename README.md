# 🌧️ Rainfall Prediction Using Historical Weather Data

## 📌 Overview
This project analyzes historical weather data to identify patterns and predictors of rainfall. By examining features such as temperature, humidity, wind, and pressure, the project aims to understand the conditions that lead to precipitation and (optionally) predict rainfall using basic machine learning techniques.

## 🛠 Tools & Technologies
- **Python**
- **Pandas & NumPy** for data preprocessing and analysis  
- **Matplotlib & Seaborn** for visualization  
- **Scikit-learn** (optional, if machine learning is used)  
- **Jupyter Notebook**  

## 🗂 Dataset Overview
The dataset includes daily weather observations with the following key features:

### 🔑 Sample Columns:
- `Date`, `Events` (rain, fog, etc.)
- **Temperature:** `TempHighF`, `TempAvgF`, `TempLowF`  
- **Dew Point:** `DewPointHighF`, `DewPointAvgF`, `DewPointLowF`  
- **Humidity:** `HumidityHighPercent`, `HumidityAvgPercent`, `HumidityLowPercent`  
- **Pressure:** `SeaLevelPressureAvgInches`, `SeaLevelPressureLowInches`  
- **Visibility:** `VisibilityHighMiles`, `VisibilityAvgMiles`, `VisibilityLowMiles`  
- **Wind:** `WindHighMPH`, `WindAvgMPH`, `WindGustMPH`  
- **Precipitation:** `PrecipitationSumInches`

## 📊 Key Objectives
- Explore weather conditions leading to rainfall  
- Identify which variables are most correlated with precipitation  
- Visualize rainfall trends across time and weather patterns  
- (Optional) Predict whether it will rain based on meteorological data


## 🔍 Key Insights
- Higher humidity and lower visibility strongly align with rainy days  
- Pressure drop often precedes rainfall events  
- Wind gusts and average wind speed show mild correlation with precipitation

## 📈 Visuals Used
- Line plots of daily rainfall over time  
- Bar plots of monthly average rainfall  
- Heatmap showing feature correlations  
- Boxplots comparing weather variables on rainy vs. non-rainy days

## ✅ Optional ML Component
If machine learning was used:
- Built a classification model to predict rainfall based on weather inputs
- Evaluated model using accuracy, precision, and confusion matrix
- Feature importance revealed top indicators for rainfall prediction

## ✅ Future Enhancements
- Add time series modeling (e.g., ARIMA or Prophet) for rainfall forecasting  
- Build an interactive dashboard using Streamlit  
- Include more years of data for stronger temporal insights


*This project is built for learning and analytical practice, not for real-time weather prediction.*
