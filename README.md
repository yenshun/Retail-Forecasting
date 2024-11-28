# Retail-Forecasting

This repository contains various approaches to perform time-series forecasting using different machine learning models and tools. The project aims to predict sales effectively by leveraging historical data and advanced forecasting techniques. Snowflake is used for data management, enabling a seamless pipeline for data processing and integration with the forecasting models.

---

## Project Overview

Retail forecasting is a critical aspect of business strategy, enabling better decision-making through accurate predictions. This repository explores different models, including statistical methods and advanced machine learning techniques, to handle seasonal trends, non-linear patterns, and long-term dependencies in retail sales data.

---

## Technologies Used

- **Python**: For implementing and testing forecasting models.
- **Snowflake**: A cloud-based data warehouse used for scalable data storage and querying.
- **Snowflake-powered Jupyter Notebooks**: For interactive exploration and development.
- **Machine Learning Models**: ARIMA, Prophet, NeuralProphet, LSTM, CNN & LSTM, Snowflake Cortex.

---

## Notebooks and Models

### 1. Data Engineering Notebooks
   - **General**: Basic data preprocessing and data cleaning workflows.
   - **NeuralProphet & LSTM (NP:LSTM)**: Advanced data preprocessing for deep learning and hybrid models.

### 2. ARIMA ML Model
   - A statistical time series model capturing linear dependencies in data.

### 3. Prophet ML Model
   - Developed by Meta, it offers quick and interpretable forecasts using seasonality and trend decomposition.

### 4. NeuralProphet ML Model
   - A hybrid forecasting approach combining neural networks with Prophet to handle complex seasonality and trends.

### 5. LSTM ML Model
   - Long Short-Term Memory (LSTM) networks to uncover patterns in sequential data and long-term dependencies.

### 6. Snowflake Cortex Forecasting
   - Integrates Snowflake with forecasting tasks, testing its efficiency in handling large-scale datasets and streamlining forecasting workflows.

### 7. Prophet Recursive Model
   - An iterative method that uses Prophet for multiple forecasts. This approach aims to rerun the Prophet model 100 times for different store chains to evaluate the average performance and measure the time needed to execute the model.
