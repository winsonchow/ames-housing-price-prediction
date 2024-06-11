# Ames Housing Price Prediction

## Table of Contents
1. [Project Overview](#project-overview)
2. [Dataset Description](#dataset-description)
3. [Installation and Setup](#installation-and-setup)
4. [Project Structure](#project-structure)
5. [Data Preprocessing](#data-preprocessing)
6. [Model Development](#model-development)
7. [Evaluation Metrics](#evaluation-metrics)
8. [Results](#results)
9. [Challenges and Improvements](#challenges-and-improvements)
10. [Future Work](#future-work)
11. [Contributing](#contributing)
12. [License](#license)
13. [Acknowledgements](#acknowledgements)

## Project Overview
This project aims to build a regression model to predict housing prices using the Ames dataset. The objective is to explore various regression techniques and evaluate their performance.

## Dataset Description
The Ames dataset consists of 2,930 samples with 79 explanatory variables describing various aspects of residential homes in Ames, Iowa. Key features include overall quality, year built, and total square footage.

## Installation and Setup
To set up the project environment, follow these steps:
1. Clone the repository: `git clone https://github.com/winsonchow/ames-housing-price-prediction.git`
2. Navigate to the project directory: `cd ames-housing-price-prediction`
3. Install the required libraries: `pip install -r requirements.txt`

## Project Structure
- `data/`: Contains the dataset files.
- `ames_housing_regression_model.ipynb`: Jupyter notebook with data exploration, data preprocessing, model development and model training.
- `README.md`: Project documentation.

## Data Preprocessing
Data preprocessing steps include handling missing values, encoding categorical variables, and splitting the data into training and testing sets.

## Model Development
The project explores various regression models, including Linear Regression, Decision Trees, and Random Forest. Feature selection techniques are applied to improve model performance.

## Evaluation Metrics
The models are evaluated using Mean Absolute Error (MAE), Mean Squared Error (MSE), Root Mean Squared Error (RMSE), and R-squared (R²) score.

## Results
The Random Forest model achieved the best performance with an RMSE of 0.144598 and an R² score of 0.881069. Visualizations comparing actual vs. predicted values are provided in the results section.

## Challenges and Improvements
Challenges included handling missing data and optimizing model performance. Future improvements could involve incorporating more features, implementing feature scaling, hyperparameter tuning and exploring advanced regression techniques.

## Future Work
Potential future work includes adding more features, trying different regression algorithms, and improving model performance with advanced techniques.

## Acknowledgements
Special thanks to Professor Dr.Tan for his guidance and support.

