# Bike_Sharing_Algorithm

## Overview
This project implements a **Bike Sharing Algorithm** designed to optimize the usage and distribution of bikes across a city’s bike-sharing network. The algorithm aims to:
- Ensure bikes are distributed across stations efficiently.
- Minimize wait times for users.
- Maximize bike availability and reduce congestion at stations.
- Predict future demand based on historical data.

---

## Features

- **Real-time bike distribution**: Adjusts bike allocation based on the current demand and supply at different stations.
- **Predictive demand forecasting**: Utilizes historical data to predict bike usage patterns.
- **Optimization for station load balancing**: Ensures that stations are neither over-crowded nor under-served.
- **User experience enhancement**: Aims to minimize user waiting time by recommending nearby stations with available bikes.

---

## Prerequisites
- **Python 3.x**
- **Install dependencies:**
  You can install the necessary dependencies using **pip**.
- **Required Libraries**
  The following Python libraries are used in this project:
  - pandas
  - scikit-learn
  - matplotlib
  - seaborn
### Dataset: 
The dataset **bike_sharing_data.csv** contains the following columns:
- **timestamp** - timestamp field for grouping the data
- **cnt** - the count of a new bike shares
- **t1** - real temperature in C
- **t2** - temperature in C "feels like"
- **hum** - humidity in percentage
- **wind_speed** - wind speed in km/h
- **weather_code** - category of the weather: 1 = Clear; mostly clear but have some values with haze/fog/patches of fog/ fog in vicinity, 2 = scattered clouds / few clouds, 3 = Broken clouds, 4 = Cloudy, 7 = Rain/ light Rain shower/ Light rain, 10 = rain with thunderstorm, 26 = snowfall
- **is_holiday** - boolean field - 1 holiday / 0 non-holiday
- **is_weekend** - boolean field - 1 if the day is weekend
- **season** - category field meteorological seasons: 0-spring ; 1-summer; 2-fall; 3-winter.

---

## Usage
### 1. Clone the Repository:
```bash
git clone https://github.com/ptrishita/Bike_Sharing_Algorithm.git
```
### 2. Load the dataset:
The dataset is expected to be in CSV format. Ensure that you have a file named "bike_sharing_data.csv" in the project directory or update the path in the code.
### 3. Run the script:
```bash
python InstructIQ_Bike_Sharing_Algorithm.ipynb
```
This will run the entire process, including data loading, preprocessing, model training, and evaluation.
