# Predict_Rating_Scores_with_Text_Reviews-


Reading the data file “Womens-Clothing-E-Commerce-Reviews.csv” in pandas.

The documentation states that the dataset consists of 23,486 rows and 11 features. The features include:

Clothing ID: Integer Categorical variable that refers to the specificpiece being reviewed.
Age: Positive Integer variable of the reviewers age.
Title: String variable for the title of the review.
Review Text: String variable for the review body.
Rating: Positive Ordinal Integer variable for the product score granted by the customer from 1 Worst, to 5 Best.
Recommended IND: Binary variable stating where the customer recommends the product where 1 is recommended, 0 is not recommended.
Positive Feedback Count: Positive Integer documenting the number of other customers who found this review positive.
Division Name: Categorical name of the product high level division.
Department Name: Categorical name of the product department name.
Class Name: Categorical name of the product class name.



Reporting the results of Mean Absolute Error and Root Mean Square Error on both Training dataset and Test dataset:

1. split the dataset with the ratio 8-to-2 for the training set and the test set.
2. Using the ‘glove.6B.50d.txt’ as the word embedding tool.
3. Using the first 100 words of each review as the input of the model.
4. Using the 100 LSTM nodes in the layer.
5. Optimizing the model for 20 epochs. 
