# Regression with a Mohs Hardness Dataset
## Aim
To predict the Mohs hardness of a mineral, given its properties.
## Link to the competition
[\<click!\>](https://www.kaggle.com/competitions/playground-series-s3e25)
## Score
MedAE = 0.479
## Approach
    1. brief EDA
    2. data preprocessing
    3. evaluate approach (regression, classification, combined approach, partial regression)
    4. feature engineering (clustering with different group of features)
    5. evaluate the basic models for regression approach
    6. create the ensembles of best-performing basic models for regression approach
    7. define the best regressor model
    8. evaluate the basic models for classification approach
    9. create the ensembles of best-performing basic models for classification approach
    10. define the best classifier model
    11. combine the best regressor model and the best classifier model and get the predictions
## Used techniques
### Libraries
    1. pandas
    2. numpy
    3. itertools
    4. matplotlib
    5. seaborn
    6. sklearn
    7. xgboost
    8. lightgbm
    9. catboost
### Preprocessing
    1. EDA
    2. Target reforming
    3. Feature engineering
    4. Clustering by different features groups
    5. Normalization
### Learning
    1. Logistic Regression
    2. Logistic Regression with Kernel Approximation
    3. Linear Regression
    4. HistGBM Classifier and Regressor
    5. Extra Tree Regressor
    6. XGBM Classifier and Regressor 
    7. LightGBM Classifier and Regressor
    8. CatBoost Classifier and Regressor 
    9. Ensembles
    10. Cross-Validation
    11. Hyperparameter optimization
