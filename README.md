# Iris Species Classification using Apache Spark

This project demonstrated a machine learning pipeline for classifying the IRIS species using **PySpark**.
By using Spark's **MLlib**, the project explores data processing and compare model performance of multiple classification algorithms such as:
1. **Logistic Regression (LR)** -  used as a baseline linear model for multiclass classification.
2. **Decision Tree (DT)** - used to capture the non-linear relationships and improve interpretabality.
3. **Random Forest (RF)** - used to improve the predictive accuracy and reduce overfitting.

Insights: 
- Feature Importance Analysis across all models has consistently identified Petal Length and Petal Width as the importance features in classifying the Iris Species.
- While, Sepal Dimension has lower predictive power compared to Petal Dimensions.
- The models were evaluated using the 'MulticlassClassificationEvaluator' based on:
  * Accuracy
  * Precision
  * Recall
  * F1 Score
