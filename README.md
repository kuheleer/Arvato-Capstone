# Create a Customer Segmentation Report for Arvato Financial Solutions

## Summary: 

Three major steps in the project:

1. **Customer Segmentation Report**
Analysis of azdias data and demographics data is followed by identifying the principal contributors for assessing the customers of a company.

2. **Supervised Learning Model** -Based on the results of a previous project AdaboostClassifier has been chosen to carry out the analysis.

3. **Kaggle Competition**The chosen model is used to make predictions on the test data

## Data Files: <a name="files"></a>

1. `azdias.csv` - Demographics data for the general population of Germany (891,211 persons (rows) x 366 features (columns))

2. `customers.csv` - Demographics data for customers of a mail-order company (191,652 persons (rows) x 369 features (columns))

3. `mailout_train.csv` - Demographics data for individuals who were targets of a marketing campaign (42,982 persons (rows) x 367 (columns)

4. `mailout_test.csv` - Demographics data for individuals who were targets of a marketing campaign (test)42,833 persons (rows) x 366 (columns)

## Libraries Used:

1. sns
2. literal_eval
3. Imputer
4. StandardScaler
5. KMeans
6. StratifiedKFold
7. roc_auc_score
