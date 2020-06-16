# Kaggle-Salary-Predictions

This is the notebook for the salary prediction brackets using the Kaggle 2018 DS and ML Challenge. 
The dataset used for the following project was used from the Kaggle website.

Tell a Data Story about a Subset of Data Science Community from 2018 Kaggle ML & DS Survey

Through the project, I did the following: 
1. Data Cleaning: 
i. Deletion of unnecessary features, like those which have > 50% of NaN or Null. 
ii. Impute missing data (Categorical & Numerical)by using mode after investigating data trends & relationship between features. 
iii. Convert cleaned data into 0 & 1 by using one hot encoding for the purpose of ML. 

2. Exploratory Analysis and Visualization: 
i. Nationality vs annual compensation visualization, for the purpose of draw a conclusion on high paid countries i the field of data science. 
ii. Level of education vs annual compensation, for the purpose of draw conclusion on level education effect annual compensation of data scientist. 
iii. Visualize feature importance with respect to annual compensation by using Regularized Regression Ridge. 

3. Feature Selection by using Mutual Info Classifier. 

4. Prediction Implementation by using Lasso Regression, Ridge Regression, Random Forest and Decision Tree. 

5. Bias Variance trade off analysis for R2 score values. 

6. Hyperparameter Tuning with grid_search and Cross validation for 10 Folds.
