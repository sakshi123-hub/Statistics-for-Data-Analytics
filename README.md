# Statistics-for-Data-Analytics
The analysis emphasizes the significance of these datasets in providing insights for researchers, meteorologists, data analysts, and medical practitioners to understand weather patterns and cardiovascular health trends, aiding in predictive modelling and risk assessment.

## Overview

This project encompasses the analysis and prediction of meteorological data using time series analysis and the prediction of cardiac conditions using logistic regression models. It leverages two distinct datasets: the Weather Revised Dataset and the Cardiac Dataset.

### Datasets

#### Weather Revised Dataset
The Weather Revised Dataset is an extensive database of meteorological observations including:
- `date`: Date of observation
- `maxtp`: Maximum air temperature in degrees Celsius
- `mintp`: Minimum air temperature in degrees Celsius
- `gmin`: Grass minimum temperature in degrees Celsius
- `rain`: Precipitation amount in millimeters
- `cbl`: Mean CBL pressure in hectopascals
- `wdsp`: Mean wind speed in knots
- `pe`: Potential evapotranspiration in millimeters
- `evap`: Evaporation in millimeters

#### Cardiac Dataset
The Cardiac Dataset is a carefully selected collection of health-related data relevant to cardiovascular health, including:
- `age`: Age of the individual
- `weight`: Weight of the individual
- `gender`: Gender of the individual
- `caseno`: Case number
- `fitness_score`: Fitness score of the individual
- `cardiac_condition`: Cardiac condition status

## Project Structure

- **data/**: Contains the datasets used in the project.
- **notebooks/**: Jupyter notebooks demonstrating the analysis and modeling processes.
- **src/**: Source code for data preparation, modeling, and evaluation.
- **results/**: Generated results, including plots and model evaluation metrics.
- **README.md**: Project overview and instructions.

## Requirements

- Python 3.x
- Jupyter Notebook
- Pandas
- NumPy
- Scikit-learn
- Statsmodels
- Matplotlib
- Seaborn

Install the required libraries using:

```bash
pip install pandas numpy scikit-learn statsmodels matplotlib seaborn
```

## Usage

### Time Series Analysis on Weather Data

1. **Data Preparation**:
   - Clean and preprocess the dataset to handle missing values, outliers, and inconsistent formatting.

2. **Preliminary Assessment**:
   - Perform an initial analysis to understand the basic characteristics and distributions of the data.

3. **Decomposition**:
   - Decompose the time series data to identify trends, seasonality, and residuals.

4. **Modeling with SARIMA**:
   - Apply the Seasonal Autoregressive Integrated Moving Average (SARIMA) model to forecast future weather conditions.
   - Evaluate the model using metrics such as Mean Absolute Error (MAE), Mean Squared Error (MSE), and Root Mean Squared Error (RMSE).

### Logistic Regression on Cardiac Data

1. **Data Preparation**:
   - Clean and preprocess the cardiac dataset to handle missing values and outliers.

2. **Train-Test Split**:
   - Split the dataset into training and testing subsets.

3. **Modeling**:
   - Fit a logistic regression model to predict the probability of cardiac events based on predictor variables.

4. **Evaluation**:
   - Evaluate the model using metrics such as accuracy, precision, recall, F1-score, and the area under the ROC curve (AUC-ROC).
   - Plot ROC curves, precision-recall curves, and the distribution of predicted probabilities.

## Results and Analysis

- **Weather Data**:
  - Detailed analysis of trends, seasonality, and residuals in the weather data.
  - Forecasting future weather conditions with SARIMA models.
  - Visualization of actual vs. predicted values and time series decomposition.

- **Cardiac Data**:
  - Identification of key risk factors for cardiac conditions.
  - Logistic regression model performance and evaluation.
  - Visualization of model coefficients, ROC curves, and predicted probabilities.

## Conclusion

The project demonstrates the application of time series analysis on meteorological data and logistic regression on cardiac data, providing valuable insights and predictions in their respective fields. The methodologies and models used highlight the importance of data-driven approaches in understanding and forecasting trends, patterns, and risk factors.
