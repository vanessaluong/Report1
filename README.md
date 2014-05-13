## Report1
==================================================================
The data and analyses here is based on the following research:

"Human Activity Recognition Using Smartphones Dataset"
Version 1.0

Jorge L. Reyes-Ortiz, Davide Anguita, Alessandro Ghio, Luca Oneto.
Smartlab - Non Linear Complex Systems Laboratory
DITEN - Universit‡ degli Studi di Genova.
Via Opera Pia 11A, I-16145, Genoa, Italy.
activityrecognition@smartlab.ws
www.smartlab.ws
==================================================================

The data includes measurements of six activities (WALKING, WALKING_UPSTAIRS, WALKING_DOWNSTAIRS, SITTING, STANDING, LAYING) conducted by 30 volunteers within an age bracket of 19-48 years.

Accelerometer and gyroscope data was captured at a constant rate of 50Hz, including 3-axial linear acceleration and 3-axial angular velocity.

* After merging training set and testing into full data set, names of all features were imported to R, and applied as column name of full data data frame
* Only the measurements on the mean and standard deviation for each measurement are analysed by using grep function to select "mean()" and "std()" to subset the full data
* The activity column was revalue to make it understandable
* To make column name of the data valid, all punctuations will be removed, and some brief words will be transform into understandable words
* Finally, the average of each feature will be calculated by activity and subject.
