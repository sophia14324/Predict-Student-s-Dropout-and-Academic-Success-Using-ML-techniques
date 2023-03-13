# Predict Student's Dropout and Academic Success Using ML techniques

The goal of this project is to predict student's dropout and academic success using machine learning techniques. The dataset used in this project is the [Predict students' dropout and academic success](https://www.kaggle.com/datasets/thedevastator/higher-education-predictors-of-student-retention). The dataset contains information about students' demographics, family background, academic performance, and whether they dropped out or not.

## Methods
The following machine learning algorithms were used in this project:

*Logistic regression*

*Decision trees*

*Random forest*

*K-nearest neighbors (KNN)*

The data was first preprocessed by encoding categorical variables, dropping irrelevant columns, and splitting into training and testing sets. EDA was perfomed to determine the relationship between the features and the Target variable. The data was also scaled using min-max scaling.

**Hyperparameter Tuning** was performed for each algorithm using grid search with cross-validation (GridSearchCV). Model performance was evaluated using accuracy, precision, and recall.

## Results
The results showed that the Logistic Regression algorithm had the highest accuracy and recall score, followed by the decision tree algorithm with second highest accuracy score but lowest recall score. KNN had the lowest accuracy score. The choice of scaling method did not have a significant impact on the performance of the models.

## Conclusion
The Logistic Regression algorithm is the best model for predicting student dropout and academic success based on the given dataset. Further studies can be done to explore other algorithms and feature engineering techniques to improve the model performance.
