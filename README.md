# gettingandcleaningdata
Getting and cleaning data project Coursera

This is the project for the Getting and Cleaning Data Coursera course. 
run_analysis.R does the following things -

Download the dataset in the working directory
Load the activity and feature info
Loads both the test and training datasets, mean or standard deviation columns are only kept 
Loads the activity and subject data for each dataset, and merges those columns with the dataset
Merges the two datasets
Converts the activity and subject columns into factors
Creates a tidy dataset that consists of the mean of each variable for each subject and activity pair.
Final result is stored in tidy.txt
