# SC1015 Project (Group 5)

## Written below is the overall flow of our presentation and an overview of our work. More details can be found in the comments in our notebook and we talk through our whole process in our video presentation.

# Problem Statement

### Our project aims to see if machine learning algorithms can accurately predict for cardiovascular disease and tell us what are the factors that contribute most to the presence.

### The dataset that we used was [this]('https://www.kaggle.com/datasets/sulianova/cardiovascular-disease-dataset')

# Data Preparation

### We applied outlier removal and one hot encoding on our dataset

### Details can be found in our ipynb notebook and explanation in our presentation video

# Exploratory Data Analysis

### We utilized methods we learnt during the Data Science section of the course to observe any distinctive patterns across the 2 different cardio classes

### From observation, we were able to come up with some hypothesis that certain variables will play a bigger role in determining for the presence of cardiovascular diseases compared to other variables.

### We carried out these operations for both continuous and discrete variables.

# Machine Learning Algorithms / Hyperparameter Tuning

### We used a total of 5 algorithms as listed in our presentation.

### For our training, we carried out a nested cross validation.

### This helped our model to see a more diverse combination of data and helped eliminate any potential overfitting and information leakage during hyperparameter tuning.

### We also showcased the accuracy metric for the models we decided to use

# Insights

### We observed the feature importances of our trained and tuned models to check our initial hypothesis formed from our EDA to decide which features play a role in determining for cardiovascular disease.

### Additionally, we also look at the confusion matrix and realize that our models have further room for improvement.

# Machine Learning models used

- Logistic Regression
- Decision Tree Classifier
- Random Forest Classifier
- XGBClassifier
- KNeighborsClassifier

# Conclusion

### We can conclude that people who are older, with higher cholesterol and higher blood pressure should take measures early to prevent cardiovascular disease.

# What we learned

### Hyperparameter Tuning

### Nested Cross Validation

### Different models such as XGBClassifier and KneighborsClassifier

### How to infer feature importances from models and their significance to our project
