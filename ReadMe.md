Getting and Cleaning Data.

This is the solution of the Assessment Project for the Course Getting and Cleaning Data.

This is what the exercise said:

>The purpose of this project is to demonstrate your ability to collect, work with, and clean a data set. The goal is to prepare tidy data that can be used for later analysis. You will be graded by your peers on a series of yes/no questions related to the project. You will be required to submit: 1) a tidy data set as described below, 2) a link to a Github repository with your script for performing the analysis, and 3) a code book that describes the variables, the data, and any transformations or work that you performed to clean up the data called CodeBook.md. You should also include a README.md in the repo with your scripts. This repo explains how all of the scripts work and how they are connected.  

>One of the most exciting areas in all of data science right now is wearable computing - see for example this article . Companies like Fitbit, Nike, and Jawbone Up are racing to develop the most advanced algorithms to attract new users. The data linked to from the course website represent data collected from the accelerometers from the Samsung Galaxy S smartphone. A full description is available at the site where the data was obtained: 

>http://archive.ics.uci.edu/ml/datasets/Human+Activity+Recognition+Using+Smartphones 

>Here are the data for the project: 

>https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip 

> You should create one R script called run_analysis.R that does the following. 
> 1. Merges the training and the test sets to create one data set. 
> 2. Extracts only the measurements on the mean and standard deviation for each measurement.  
> 3. Uses descriptive activity names to name the activities in the data set 
> 4. Appropriately labels the data set with descriptive variable names.  
> 5. From the data set in step 4, creates a second, independent tidy data set with the average of each variable for each activity and each subject.
>Good luck!

>Please upload the tidy data set created in step 5 of the instructions. Please upload your data set as a txt file created with write.table() using row.name=FALSE (do not cut and paste a dataset directly into the text box, as this may cause errors saving your submission).

How it make works
-----------------

Set up the path with `setwd(my_path)`. `my_path` is the path where you have the file `run_analsis.R`. if you don't have the folder `UCI HAR Dataset` in `my_path`, the script will be downloaded in a file called `Dataset.zip` and unzip in `my_path` (You should have the library `unzip` installed in your machine for R).

You can run the script run_analysis.r

It will generate a file called `tidy.txt`