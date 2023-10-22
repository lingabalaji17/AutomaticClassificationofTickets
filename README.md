# Automatic Classification of Tickets


# Customer Complaints Classifier

This project aims to build a model capable of classifying customer complaints based on the products or services. The objective is to streamline the ticket resolution process by categorizing the complaints effectively.

## Topic Modelling

Performed topic modelling on the provided .json data. Since the data was unlabelled, the Non-negative Matrix Factorization (NMF) algorithm was applied. It successfully classified tickets into five clusters, namely:

1. Credit card / Prepaid card
2. Bank account services
3. Theft/Dispute reporting
4. Mortgages/loans
5. Others

Using the results of the topic modelling, a supervised learning model such as logistic regression, decision tree, or random forest can be trained. This trained model can effectively classify new customer support tickets into their relevant departments.
