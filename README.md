# Loan_Approval_Prediction
Project Description: Predicting Loan Approvals 💰
This project is a machine learning tool that predicts whether a person's loan application will be approved or not. It uses a dataset of past loan applications to learn what factors are most important for getting a loan.

The process is broken down into a few main parts:

1. Preparing the Data (Data Preprocessing)
First, the code cleans up the raw data. This involves:

Creating a new feature: It combines the applicant's income and the co-applicant's income into a single Total_Income column.

Filling in missing information: It automatically fills in any missing values in the dataset using smart guesses (like the average income or the most common marital status).

Converting text to numbers: It turns all the text categories (like Male/Female or Urban/Rural) into numbers that the computer can understand, which is a crucial step for the machine learning models.

2. Training Two Models 🤖
The project doesn't just use one model; it trains two different ones to see which performs better:

Logistic Regression: This is a simple but effective model that's great for "yes" or "no" questions. It figures out the odds of a loan being approved based on all the factors.

Random Forest Classifier: This is a more advanced model that uses a group of "decision trees" to make its prediction. It's often more accurate because it's like getting a second opinion from many different experts.

3. Evaluating the Results 👍
After training the models, the code checks how accurate they are.

Accuracy Score: This is a simple number that tells you the percentage of correct predictions the model made.

Confusion Matrix and Heatmap: This is a visual tool that shows you exactly where the model was right and where it was wrong. For each model, it creates a separate heatmap to show you:

How many loans were correctly predicted as "approved" (True Positives).

How many loans were correctly predicted as "denied" (True Negatives).

Where the model made mistakes (False Positives and False Negatives).

By comparing the heatmaps, you can easily see which model did a better job of predicting loan outcomes.
