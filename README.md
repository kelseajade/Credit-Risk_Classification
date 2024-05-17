# Credit-Risk_Classification
 
Overview of the Analysis
The goal of this analysis was to develop a machine learning model capable of prediction loan risks of individuals in a peer to peer lending company. The model classified loans as a healthy low-risk loan or a high-risk loan. The dataset contained details about the loan. The model predicted 18,765 instances of healthy loans and 619 high-risk instances. The data was split into testing sets and training sets. The model was evaluated using accuracy, precision, recall, and F1-score. Confusion matrices were also used to understand the distribution of predictions. 

Results
* Machine Learning Model: Logistic Regression 
Accuracy: 0.99
Precision and Recall Scores:
Healthy Loans (0):
Precision: 1.00
Recall: 0.99
F1-Score: 1.00
High-Risk Loans (1):
Precision: 0.85
Recall: 0.95
F1-Score: 0.89


Summary
The logistic regression model has the high accuraccy and has close precision and recall for both high-risk and healthy loans. The context of the machine learning usage is important as it is more important to minimize false positives or negatives for certain topics such as medical and business dependency. For loans it would be important to minimize false positives but also to identify as many high-risk loans as possible.This model would be a reliable choice for a lenging service to use for loan classification. 
