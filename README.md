# Fake News Detection

# Dataset Information
Two datasets: df_fake and df_true.
Columns: 'title', 'text', 'subject', 'date', 'class'.
Additional column 'class': 0 for fake, 1 for true. 

# Data Preparation
Removed the last 10 rows for manual testing from both datasets.
Merged manual testing dataframes for fake and true news, saved to CSV.

# Model Building
Used four classification models: Logistic Regression, Decision Tree, Gradient Boosting, and Random Forest.
Achieved high accuracy for all models (e.g., 99.55% for Gradient Boosting).

# Model Testing with Manual Entry
Provided a function for manual testing of news.
Input a news text, and it predicts whether it's fake using all four models.

# Example Manual Testing
Entered a news text about the failure of US foreign policy and economic issues.
All models predict it as "Fake News."

# Libraries

<li>pandas
<li>matplotlib
<li>seaborn
<li>scikit-learn

# Algorithms

<li>Logistic Regression
**Best Model Accuracy:** 95.00
<li>Decision Tree Classification
**Best Model Accuracy:** 99.46
<li>Gradient Boosting Classifier
**Best Model Accuracy:** 99.55
<li>Random Forest Classifier
**Best Model Accuracy:** 99.15


