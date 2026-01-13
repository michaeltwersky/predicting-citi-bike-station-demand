# Forecasting Citi Bike Station Demand to Improve Efficiency of Operational Rebalancing

## Introduction

To address the operational bottleneck of rebalancing stations during rush hours, this study forecasts bike demand for Citi Bike stations in New York City.

## Goal

My work aims to train a reliable machine learning model that accurately predicts bike demand between neighborhood clusters in Manhattan and Brooklyn. This model can be used to improve current rebalancing operations down to the 15-minute time interval.

## Description of the Data

Obtained directly from Citi Bike, historical weather data, and the City of New York's NYC Open Data, the data consists of three files:

- `contract.csv`: contract information

- `personal.csv`: the customer's personal data

- `internet.csv`: information about internet services

- `phone.csv`: information about telephone services


## Tools

- Python
  - Pandas
  - Numpy
  - DateTime
  - ARIMA
  - SARIMAX
  - Plotly
  - MatPlotLib
  - Seaborn
  - SciKit-Learn
  - XGBoost

## Examples of Charts

![alt text](https://github.com/michaeltwersky/Data_Projects_TripleTen/blob/main/Sprint%2017%20-%20Final%20Project/Images/Image%201.png)



### Data

Download all files from the [v1.0 release page](https://github.com/michaeltwersky/applied-ml-project/releases/tag/data)

#### Setup Instructions
1. Download the datasets using the links above
2. Place them in the `data/` folder
3. Run citibike_data.ipynb
