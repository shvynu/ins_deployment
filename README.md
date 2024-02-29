# Predictive Maintenance Analysis

This repository contains a Python script for performing predictive maintenance analysis using machine learning techniques. The script aims to predict machine failures based on various sensor readings and operational parameters.

## Overview

Predictive maintenance is a technique used to predict when equipment failure might occur so that maintenance can be performed just in time to prevent costly downtime. This script utilizes machine learning algorithms to analyze historical data and predict machine failures.

## Features

- Data loading and exploration
- Data cleaning and preprocessing
- Data normalization
- Test and train split
- Model training without balancing
- Tuning and balancing model with SMOTE
- Fitting the model with ADASYN oversampling
- ROC score without and with sampling for Decision Tree models
- ROC curve for Random Forest Classifier using ADASYN oversampling
- Plotting accuracy graphs for different models

## Requirements

- Python 3.9 or latest version available
- Libraries: pandas, numpy, matplotlib, seaborn, scikit-learn, imbalanced-learn, scikit-plot

## Usage

1. Clone the repository:

2. Navigate to the project directory:

3. Install the required dependencies:

4. Place your dataset named "data.csv" in the project directory, you can prefer this dataset if you want (https://www.kaggle.com/code/zakikurdya/predictive-maintenance)

5. Run the Python script:

6. Follow the prompts and input data as required.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.





