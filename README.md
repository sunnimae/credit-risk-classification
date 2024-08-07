# credit-risk-classification
The purpose of this analysis to establish if Logistic Regression model is the right model to identify the ceditworthiness of borrowers.

Accuracy:
Score: 0.99
Description: The model correctly classifies 99% of all instances across both classes.

Precision:
Class 0 (Healthy Loan): 0.99 - When the model predicts a loan as healthy, it is correct 99% of the time.
Class 1 (High-Risk Loan): 0.91 - When the model predicts a loan as high-risk, it is correct 91% of the time.
Macro Average: 0.95 -The average precision across both classes, treating each class equally.
Weighted Average: 0.99 - The precision averaged across both classes, weighted by the number of instances in each class.

Recall:
Class 0 (Healthy Loan): 1.00 -The model identifies all healthy loans correctly with no false negatives.
Class 1 (High-Risk Loan): 0.85 - The model identifies 85% of the actual high-risk loans, missing 15%.
Macro Average: 0.92 - The average recall across both classes, treating each class equally.
Weighted Average: 0.99 - The recall averaged across both classes, weighted by the number of instances in each class.

Summary:
The model exhibits high overall accuracy (99%), indicating strong performance.
Precision is very high for healthy loans (99%) and good for high-risk loans (91%).
Recall is perfect for healthy loans (100%) but slightly lower for high-risk loans (85%).
The weighted averages for precision and recall are also very high, reflecting the model’s effectiveness across the dataset.

Recommendations:
Although this model performs very well in accuracy and identifying healthy loans, there is a 15% chance that high-risk loans are not correctly identified. Ideally, we would like the recall rate for class 1 to be higher, reducing the likelihood of high-risk loans being incorrectly identified as healthy.
