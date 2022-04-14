# Framingham-dataset
# Objective
Predict if a person will have CHD (Chronic Heart Disease)

# Libraries Used
1. Pandas
2. Scikit Learn
3. Matplotlib
4. Numpy
5. Seaborn
6. Missingno
7. Imblearn
8. SMOTE
9. K Means

# Algorithms Used
1. LogisticRegression
2. RidgeClassifier
3. RandomForestClassifier
4. SVC
5. SMOTENC
6. K Means

# Data cleaning
Imputed with Median
1. CigsPerday

Imputed with Mean
1. totChol
2. BMI
3. heartRate

Imputed with Mode
1. BPMeds

Imputed with Iterative imputer( MICE)
1. Glucose

Dropped Nulls
1. Education




# Data Transformation
1. One hot encoded the Education column
2. Used balanced weights in the training for the class as it is an imbalanced dataset
3. Used SMOTE to balance the dataset
4. Standard scaled data for distance algorithms

# EDA
1. Checked the distribution plot of the features to gain insights and help in imputation methods

# Hyper Parameter Tuning
Used gridsearch CV for hyper parameter tuning

# Cross Validation
k fold cross validation

# Performance Criteria
Selected the best performing model, used scoring parameter as F1 score and Recall (As recall is more important here than precision since we are dealing with detection of diseases)

# Best Model performance
## Ridge Classifier
### Performance - Recall = 725, 63% and F1 score = 80%, 42% classwise
![alt text](https://github.com/sanketmore1234/Sustainability-Machine-Learning-Challenge/blob/main/Randomforest_DHI.jpg?raw=true)

