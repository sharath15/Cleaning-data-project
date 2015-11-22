# Cleaning-data-project

The run_analysis.R code does the folloiwng:

1. Downloads the compressed file to getdata.zip and unzips UCI HAR Dataset in the working directory if these are not already present
2. Loads the feature and activity
3. Loads training and test datasets. Holds only those columns which reflect a mean or standard deviation
4. Loads activity and subject data for each dataset (merging respective columns) and Merges the two datasets
5. Converts the activity and subject columns into factors
6. Creates a tidy dataset that consists of the average (mean) value of each variable for each subject and activity pair.
7. Result saved in "tidy.txt" using write.table() (with row.name =False)
