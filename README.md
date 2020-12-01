# DA_ML
Data Set used for analysis: Enron data Set
#Data analysis and machine Learning Assignment.
#Data set available on Kaggle: https://www.kaggle.com/wcukierski/enron-email-dataset

Assignment problem statement: 
To create a supervised classification pipeline to classify emails as spam or non-spam from the training data.
Approach used in assignment: 
•	The data set is organised into two parts one ham and other spam for pre-processing and cleaning. 
•	Check the total number of emails and verify total number of ham emails and spam emails.
•	Exploratory data analysis on training data set and get top 20 words in ham and spam emails.
•	Bar plot and box plot to compare ham and spam emails in training data.
•	Creating data frame from the list to get the data in tabular form for cleaning by first removing special characters from the text and get plain text.
•	Further cleaning by removing repeated words, most commonly used words and stop words.
•	To get the text data into numerical feature which can be used in machine learning by using Tfidf Vectorizer.
•	Get the details of how the data is based on the features extracted.
•	Spit the data into training and test set.
•	Use pickle to serialize machine learning algorithms and save the serialized format to a file.
•	Training of models based on the features extracted.
•	Calculation of  accuracy on validation data set by training supervised classification model.
•	The model with higher accuracy is used on test data set.
•	Saved model with good accuracy are tested and results are displayed in bar graph based on the metrics.


