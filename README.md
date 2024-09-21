# Wine Quality Analysis

## Project Overview

This project focuses on predicting wine quality using various classification models and determining the features that most influence wine quality. The dataset contains chemical properties of red wines, and wine quality is rated on a scale from 0 to 10.

### Key Steps
- **Data Preprocessing**: Handled missing values and standardized feature variables.
- **Feature Engineering**: Defined a binary classification problem where wines with a quality score of 7 or above are labeled as "good quality."
- **Modeling**: Compared five machine learning models: Decision Tree, Random Forest, AdaBoost, Gradient Boosting, and XGBoost.
- **Feature Importance**: Identified that alcohol, volatile acidity, and sulphates are the most important features contributing to wine quality.

### Results
- **Best Model**: Random Forest achieved the highest accuracy and f1-score in predicting good quality wines.
- **Feature Insights**: Good quality wines tend to have higher alcohol content, lower volatile acidity, and higher levels of sulphates.

## Conclusion
The Random Forest model performed the best, and the analysis provides valuable insights into the chemical characteristics of good quality wines.

