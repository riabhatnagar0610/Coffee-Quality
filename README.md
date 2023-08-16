# Coffee-Quality

![coffee beans](https://github.com/riabhatnagar0610/Coffee-Quality/blob/main/Coffee.jpg)

This project aims to analyze and predict the total cup points for coffee of different types and from various regions. It utilizes machine learning algorithms such as RandomForestRegressor and CatBoostRegressor to build predictive models.

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Dataset](#dataset)
- [Model Training](#model-training)
- [Evaluation](#evaluation)
- [Contributing](#contributing)


## Introduction

The Coffee-Quality project focuses on predicting the quality of coffee based on various features such as aroma, flavor, acidity, body, and balance. By analyzing the provided dataset and training machine learning models, this project aims to provide insights into the coffee quality and enable predictions for new samples. 

This project builds Random Forest and CatBoost Regressor models for prediction.

## Features

The Coffee-Quality project offers the following features:

- Dataset analysis and visualization
- Machine learning model training using RandomForestRegressor and CatBoostRegressor
- Predicting the total cup points for new coffee samples

The coffee cupping score developed by the Specialty Coffee Association goes from 0 to 100, and only coffees scoring 80 points or above get the “specialty coffee” badge of honor. Commercial-grade coffee scores anywhere from 60 to 80.

## Installation

To use this project, follow the steps below:

1. Clone the repository:

   ```
   git clone https://github.com/riabhatnagar0610/Coffee-Quality.git
   ```

2. Navigate to the project directory:

   ```
   cd Coffee-Quality
   ```

3. Install the required dependencies:

   ```
   pip install -r requirements.txt
   ```

## Usage

1. Ensure that you have completed the installation steps.

2. Open the Jupyter Notebook or any Python IDE of your choice.

3. Execute the code cells in the provided Jupyter Notebook (`coffee-quality.ipynb`) or run the Python scripts for the desired functionality.

4. Follow the instructions in the Notebook to interact with the project.

## Dataset

The dataset used can be found at [Kaggle](https://www.kaggle.com/datasets/fatihb/coffee-quality-data-cqi) and is present under the name `df_arabica_clean.csv` in this repository.

The dataset should be in CSV format and contain the necessary columns, including features and the target variable.

## Model Training

The model training process involves the following steps:

1. Load the dataset and perform exploratory data analysis (EDA) to understand the data.

2. Preprocess the data by handling missing values, encoding categorical variables, and scaling numerical features.

3. Split the dataset into training and testing sets.

4. Train the machine learning models using the provided dataset.

5. Optimize the models using hyperparameter tuning techniques if desired.

6. Save the trained models for future use.

The training code and details can be found in the Jupyter Notebook (`coffee-quality.ipynb`) and associated Python scripts.

## Evaluation

The evaluation of the trained models involves the following steps:

1. Load the saved models.

2. Prepare the test dataset, similar to the training dataset.

3. Evaluate the models on the test dataset using appropriate metrics such as mean squared error (MSE) or R-squared (R²) score.

4. Analyze and interpret the evaluation results to understand the performance of the models.

The evaluation code for RandomForest and CatBoost Regressor and other details can be found in the Jupyter Notebook (`coffee-quality.ipynb`).

## Contributing

Contributions to this project are welcome. If you find any bugs or have suggestions for improvements, please submit an issue or a pull request.
