# Getting and Cleaning Data - Week 4 Assignment

The run_analysis.R script does the following

1. Download and unzip the "UCI HAR Dataset" directory if it does not already exists in the working directory.

2. Load the features and activity label file.

3, Extract only measurements that contain mean() or std().
	
3. Load and combine the 3 files for the training datasets.
	* y_train.txt: training labels
	* X_train.txt: training data
	* subject_train.txt: subjects in training dataset

4. Load and combine the similar 3 files for the testing datasets. 

5. Combine the 2 datasets for those measurements that contain mean() or std().

6. Assign descriptive variable names to the combined dataset.

7. Convert the activity and subjectID columns into factor variables.

8. Create a tidy dataset ("tidy.txt) with the average of each variable for each subject-activity pair.



