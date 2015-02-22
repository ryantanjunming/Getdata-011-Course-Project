# Getting And Cleaning Data Course Project

This repo hosts the files relating to the project in the Johns Hopkins Coursera Course: Getting and Cleaning Data.

Dataset obtained are from the the [Human Activity Recognition Using Smartphones](http://archive.ics.uci.edu/ml/datasets/Human+Activity+Recognition+Using+Smartphones) - [DATASET-ZIP](https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip)


## Project Goals

Create one R script called run_analysis.R that does the following:

1. Merges the training and the test sets to create one data set.
2. Extracts only the measurements on the mean and standard deviation for each measurement. 
3. Uses descriptive activity names to name the activities in the data set
4. Appropriately labels the data set with descriptive variable names. 
5. From the data set in step 4, creates a second, independent tidy data set with the average of each variable for each activity and each subject.


## Files:

* `CodeBook.md` describes the variables, the data, and any transformations or work that you performed to clean up the data.

* `run_analysis.R` is the R Programming script and contains all the code required to perform the analysis

* `activity_final_data.txt` is the Step 5 write.table() output tidy dataset, with default " "(space) separator 