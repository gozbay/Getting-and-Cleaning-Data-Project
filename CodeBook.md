##Getting and Cleanind Data Project
Additional information about the variables and data
Data Source:https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip 
#Data Set Information
The experiments have been carried out with a group of 30 volunteers within an age bracket of 19-48 years. Each person performed six activities (WALKING, WALKING_UPSTAIRS, WALKING_DOWNSTAIRS, SITTING, STANDING, LAYING) wearing a smartphone (Samsung Galaxy S II) on the waist. Using its embedded accelerometer and gyroscope, we captured 3-axial linear acceleration and 3-axial angular velocity at a constant rate of 50Hz. The experiments have been video-recorded to label the data manually. The obtained dataset has been randomly partitioned into two sets, where 70% of the volunteers was selected for generating the training data and 30% the test data. 
The sensor signals (accelerometer and gyroscope) were pre-processed by applying noise filters and then sampled in fixed-width sliding windows of 2.56 sec and 50% overlap (128 readings/window). The sensor acceleration signal, which has gravitational and body motion components, was separated using a Butterworth low-pass filter into body acceleration and gravity. The gravitational force is assumed to have only low frequency components, therefore a filter with 0.3 Hz cutoff frequency was used. From each window, a vector of features was obtained by calculating variables from the time and frequency domain.

x_train, y_train, x_test, y_test, subject _train and subject_test contain the data from the downloaded files. 
All data is merged.
The mean and standard deviation measures are taken from the the whole dataset and given the correct names to the columns as in the features.txt
Activity names and IDs are taken form activity_labels.txt abd they are substituted in the dataset.

##Tidy Data Set
An independent tidy data set, Tidy.txt, is created and contains the average of each variable for each activty and each subject.
#Identifiers
subject : The ID of the test subject
activity : The type of activity performed when the corresponding measurements were taken
#Activity Labels
WALKING 
WALKING_UPSTAIRS 
WALKING_DOWNSTAIRS 
SITTING  
STANDING 
LAYING

#Variable Units
Activity variable is factor type
Subject variable is integer type
All other variables are numeric type 
