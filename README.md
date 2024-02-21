# Analyzing Wine Quality: Central Tendencies & ML
 
## Overview
This project focuses on analyzing wine quality using a dataset containing various chemical properties of wines. The goal is to explore the dataset, understand its central tendencies, and develop machine learning (ML) models to predict wine quality based on these features.

## Dataset
The [dataset](../main/Wine%20Quality%20Dataset.csv) used in this project contains information on various chemical properties of wines, such as fixed acidity, volatile acidity, citric acid, residual sugar, chlorides, free sulfur dioxide, total sulfur dioxide, density, pH, sulphates, alcohol, and quality. The quality column represents the target variable, indicating the quality rating of the wine.

## Project Structure
- `Analyzing Wine Quality - Central Tendencies and ML.ipynb`: Jupyter notebook containing all the code and analysis for data exploration, preprocessing, model development, and evaluation.

## Methodology
1. **Data Exploration**: Initial exploration involved examining central tendencies of the dataset, including mean and median values, to understand the distribution of features. Visualizations such as histograms and Q-Q plots were utilized to assess the normality of data distributions.

2. **Data Preprocessing**: Data preprocessing steps included handling missing values, encoding categorical variables (if any), and scaling numerical features as required.

3. **Model Development**: Machine learning models, including Linear Regression, Gradient Boosting Regression, and Random Forest Regression, were developed to predict wine quality based on the provided features.

4. **Model Evaluation**: Evaluation metrics such as Mean Squared Error (MSE) were used to assess model performance. Feature importance analysis was conducted to identify significant predictors contributing to wine quality predictions.

## Results
- The ML models demonstrated varying levels of performance in predicting wine quality, with ensemble methods (Gradient Boosting and Random Forest Regression) outperforming Linear Regression.
- Gradient Boosting Regression and Random Forest Regression exhibited lower Mean Squared Error (MSE) compared to Linear Regression.
- Feature importance analysis highlighted significant predictors contributing to wine quality predictions.

Here's a summary of the observations supporting this conclusion:

**Mean Squared Error (MSE):** The MSE obtained from both Gradient Boosting Regression and Random Forest Regression models (approximately 0.345) was lower than that of Linear Regression (approximately 0.569). A lower MSE indicates better performance in terms of predicting quality ratings, as the predicted values are closer to the actual values on average.

**Feature Importance:** When analyzing the importance of features, Gradient Boosting and Random Forest models typically consider a wider range of interactions and nonlinear relationships compared to Linear Regression. This allows them to capture more complex patterns in the data, leading to better predictive performance.

**Top Predictions:** The top wines predicted by both Gradient Boosting and Random Forest Regression models likely exhibit higher quality ratings compared to those predicted by Linear Regression, as indicated by the higher predicted values for these models.

## Future Work
- Explore additional ML algorithms and hyperparameter tuning techniques to further improve model performance.
- Incorporate additional features or external datasets to enhance predictive capabilities.
- Deploy the best-performing model as a web application or API for real-time predictions.

## Requirements
- Python 3
- Jupyter Notebook
- Libraries: pandas, numpy, matplotlib, seaborn, scikit-learn
