# Wine Quality Prediction App

This **Wine Quality Prediction** Streamlit app predicts the quality of wine based on its physicochemical properties using a pre-trained RandomForest model.

## Overview

The app allows users to input values for various wine characteristics (like acidity, sugar, pH, etc.) and returns a quality prediction on a scale of 1 to 10. The model was trained using a dataset of wine samples and aims to help winemakers assess their product quality more effectively.

## Features

- **Interactive Input**: Users can adjust wine property sliders and input fields.
- **Prediction**: The app predicts wine quality using a RandomForest model.
- **Visualization**: Graphical representation of wine quality distribution.

## App Preview

Here’s a screenshot of the app in action:

![Wine Quality Prediction - Main Screen](my_streamlit_app/screenshots/Screenshot_2024-09-18_194339.png)
![Wine Quality Prediction - Input Screen](my_streamlit_app/screenshots/Screenshot_2024-09-18_194503.png)
![Wine Quality Prediction - Result Screen](my_streamlit_app/screenshots/Screenshot_2024-09-18_194532.png)

## Screenshots 

### App Overview

![App Overview](my_streamlit_app/images/Screenshot%202024-09-17%20212847.png)

## Memory Usage

This app was optimized for memory efficiency. Here's an updated look at the memory footprint:
- **Model Size**: The RandomForest model is stored as a pickle file (`wine_quality_model.pkl`), which consumes around **XX MB**.
- **App Runtime Memory**: During prediction, memory usage is minimized through streamlined data handling and efficient Pandas operations.

## Data Description

The dataset used for this app includes the following columns:
- **Fixed Acidity**
- **Volatile Acidity**
- **Citric Acid**
- **Residual Sugar**
- **Chlorides**
- **Free Sulfur Dioxide**
- **Total Sulfur Dioxide**
- **Density**
- **pH**
- **Sulphates**
- **Alcohol**
- **Quality**: (Target Variable)



