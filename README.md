# Customer Segementation
This project is part of the *Udacity Data Science Nanodegree*. <br>
In this project, I applied unsupervised learning techniques to identify segments of the population that form the core customer base for a mail-order sales company in Germany. 

## About the Data:
- Udacity_AZDIAS_Subset.csv: Demographics data for the general population of Germany; 891211 persons (rows) x 85 features (columns).
- Udacity_CUSTOMERS_Subset.csv: Demographics data for customers of a mail-order company; 191652 persons (rows) x 85 features (columns).
- Data_Dictionary.md: Detailed information file about the features in the provided datasets.
- AZDIAS_Feature_Summary.csv: Summary of feature attributes for demographics data; 85 features (rows) x 4 columns

## Steps:
1. Preprocessing:
  * Assess missing data from columns and rows
  * Re-encode categorical and mixed type columns
  * Create a cleaning function
  * Scale and impute the data
2. Perform Dimensionality Reduction using PCA
3. Apply Clustering using KMeans
4. Compare Customer Data to Demographics Data
5. Report findings and conclusions from the clustering analysis to describe segments of the population that are relatively popular with the mail-order company, and those relatively unpopular with the company.
