# From UToR challenge
# Background
The nonprofit foundation Alphabet Soup wants a tool that can help it select the applicants for funding with the best chance of success in their ventures. With your knowledge of machine learning and neural networks, you’ll use the features in the provided dataset to create a binary classifier that can predict whether applicants will be successful if funded by Alphabet Soup.

From Alphabet Soup’s business team, you have received a CSV containing more than 34,000 organizations that have received funding from Alphabet Soup over the years. Within this dataset are a number of columns that capture metadata about each organization, such as:

- EIN and NAME—Identification columns
- APPLICATION_TYPE—Alphabet Soup application type
- AFFILIATION—Affiliated sector of industry
- CLASSIFICATION—Government organization classification
- USE_CASE—Use case for funding
- ORGANIZATION—Organization type
- STATUS—Active status
- INCOME_AMT—Income classification
- SPECIAL_CONSIDERATIONS—Special considerations for application
- ASK_AMT—Funding amount requested
- IS_SUCCESSFUL—Was the money used effectively

# Handling Missing Data
I checked for missing data in the dataset. Fortunately, there were no missing values, so I did not need to impute or remove any records.

# Feature Scaling
To ensure that all features had the same scale, we applied feature scaling (standardization).

# Model Building
For this analysis, I selected a Logistic Regression model as it is a well-established algorithm for binary classification tasks like churn prediction. I split the dataset into training and testing sets and trained the model on the training data.

Results
Accuracy of the model was below 75% at training mode using X_train_scaled and is above 75% in testing mode using X_test.

Findings
In this project, I found out that increasing batch_size fasten up the computation. However, I have to increase the epoch to balance.

