# Getting-And-Cleaning-Data
# Week 4 Peer Graded Assignment 
This repo was created to finish the assignment for week 4 of Getting and Cleaning Data Coursera course.
	First, download and unzip the data file into your R working directory.
  	Second, download the R source code into your R working directory.
  	Finally, execute R source code to generate tidy data file.

# Dataset
	https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip  

# Files
	CodeBook.md: a code book that describes the variables, the data, and any transformations or work that I performed to clean up the data
	run_analysis.R: performs the data preparation and then followed by the 5 steps required as described in the course project’s definition:
		-Merges the training and the test sets to create one data set.
    		-Extracts only the measurements on the mean and standard deviation for each measurement.
    		-Uses descriptive activity names to name the activities in the data set
    		-Appropriately labels the data set with descriptive variable names.
  	From the data set in step 4, creates a second, independent tidy data set with the average of each variable for each activity and each subject.
  	FinalData.txt is the exported final data after going through all the sequences described above.
