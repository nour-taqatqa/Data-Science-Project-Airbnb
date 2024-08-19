# Data-Science-Project-Airbnb

**Goal**:
Build machine learning models to predict the prices of Airbnb listing, as well as predict the status of the hosts (super host or non-superhost).

Dataset was taken from Kaggle: https://www.kaggle.com/

**Insight into the dataset and machine learning process:**
- Included 5000 observations and over 23 columns.
- Data was uncleaned, so many functions were custom designed to transform categorical infomration into numbers.
- Missing values were imputation using KNN
- Transformed the reponse variable to its logarithmic version after an analysis of other polynomial and exponenetial versions of it - plotting the observations over the fitted logarithmic, exponential, etc function was useful
- Cross validation was used with every model to tune paramters of model, some parameters were tuned in a greedy way to manage computational costs and some were tuned in an optimal way simultaneously
- Both regression and classification models were implemented 

Models used: 
- Simple linear regression
- KNN
- Decision Tree
- Random Forest
- AdaBoost
- XGBoost
- CatBoost
- LightGBoost

Tools used:
- Jupyter Notebook

