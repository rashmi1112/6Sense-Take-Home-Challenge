# 6Sense-Take-Home-Challenge

**Instructions to run**

1. Open the .ipynb file in Jupyter Notebook.
2. Download the 'training.tsv' and 'test.tsv' files in the same folder.
3. Update the paths wherever reading the above mentioned files.
4. Run the notebook cells.

Thank you for taking the time out of your schedule to work on this takehome. Included in the zip file is training data is pulled from raw logs. 

It has three columns that record user activity over time:
user_id: A hash that uniquely identifies the user.
activity_date: The date of the activity
activity_type: The type of activity

6sense would like to predict which users have a high chance of a FUTURE purchase given the user's PAST activities.

Using the training data, build a model that predicts which user_id's will make a purchase in the future.
Score the test data with the model you've created and sort the top 1,000 user_id's from most to least likely to purchase.

Please submit the following:
* Answers to the following questions:
	1. How did you approach the time-based aspect of the problem?
	2. Describe which activity types you believe are most useful in predicting which user will purchase in the future.
	3. If you had more time, what else would you do?
* Provide a file (csv, tsv, or similar) containing the top 1,000 user_id's most likely to convert.
* Your code that you used to generate your answers

We will be evaluating your submission on the following criteria:
1. EDA
2. Feature engineering
3. Model building
4. Model performance
5. Answers to the questions
