# Regression-Analysis-with-Python-using-the-Ames-Housing-Dataset

# Boston Housing Prices Prediction

This project aims to predict housing prices in the Boston area using linear regression and explore potential improvements in model performance with data preprocessing and cross-validation. This repository provides a complete data science workflow, from data exploration and preprocessing to model selection, evaluation, and result visualization.

## Project Overview

The goal of this project is to predict the sale price of houses using various features available in the dataset, including information on location, size, condition, and more. This work focuses on using **Linear Regression** as the baseline model for predictions, with flexibility to expand into more advanced models.

## Key Features

- **Data Loading and Exploration**: Loads the Boston housing dataset and performs initial exploratory data analysis (EDA), including heatmap visualizations to explore feature correlations.
- **Data Preprocessing**: Converts categorical features into numeric form, imputes missing values, and scales features to optimize model performance.
- **Model Training and Evaluation**: Trains a Linear Regression model to predict house prices and evaluates model performance using metrics such as Mean Squared Error (MSE) and R² Score.
- **Cross-Validation**: Employs cross-validation to validate model performance and ensure robustness.
- **Result Visualization**: Visualizes the relationship between actual and predicted prices for easy comparison.

## Project Structure

1. **Setup and Imports**: Imports necessary libraries and functions for data handling, model training, and evaluation.
2. **Data Loading**: Loads the dataset using `fetch_openml`, specifically the Boston housing dataset, and checks data types.
3. **Exploratory Data Analysis (EDA)**: Performs EDA with a correlation heatmap.
4. **Data Preprocessing**: Prepares data by handling missing values, converting categorical variables, and scaling.
5. **Model Training and Evaluation**: Fits a Linear Regression model, makes predictions, and calculates MSE and R².
6. **Cross-Validation**: Evaluates model performance with cross-validation.
7. **Visualization**: Plots actual vs. predicted values to visualize model performance.

## Results

- **Mean Squared Error (MSE)**: MSE provides an insight into the average error in our predictions.
- **R² Score**: The R² score reflects how well our model explains the variance in the dataset.
- **Cross-Validation**: Cross-validated R² scores ensure model robustness.

## Getting Started

To run this project, ensure you have Python 3.8+ and the necessary dependencies installed. Clone the repository and run the main script.

```bash
git clone https://github.com/your-username/Boston-Housing-Prices.git
cd Boston-Housing-Prices
```

### Dependencies

Install dependencies:

```bash
pip install -r requirements.txt
```

