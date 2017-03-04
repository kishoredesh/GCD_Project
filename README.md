##Getting and Cleaning Data - Course Project
```This is the course project for the Getting and Cleaning Data course```


There is R script named as run_analysis.R which does the following task:<br>
1. set current working directory <br>
2. Download the dataset if it does not already exist in the current working directory  <br>
3. Load the activity and feature info from zip file dataset  <br>
4. Loads both the training and test datasets from zip file and keeping only  <br>
   those columns which reflect a mean or standard deviation <br>
5. Loads the activity and subject data for each dataset, and merges those columns with the dataset <br>
6. Merges the two datasets  <br>
7. Converts the activity and subject columns into factors  <br>
8. Creates a tidy dataset that consists of the average (mean) value of each variable for each subject and
activity pair. <br>


```The end result is shown in the file "tidy.txt".```


