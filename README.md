# 20-Supervised-Learning
Credit Risk Analysis

For this project at the University of Pennsylvania Bootcamp we were tasked with training a supervised algorithm to predict the risk of providing loans to people labeled either healthy loans or high-risk loans.  For the code I used past lessons as reference to create the supervised machine learning model. Classification of the credit risk lets lenders know whether they are making the right decision or not.  

Looking at the data: 
•	The accuracy of the logistic regression model is at 99%.
•	The precision of the model was 100% for the healthy loans where it was only 86% for the high-risk loans.  
•	The recall for the healthy loans was 100% where the recall for the high-risk loans was only 90%.
•	The f1-score is a combination of the recall and the precision scores to determine the whether the model was well-balanced or not.  The f1-score for the healthy loans was 100% where it was 88% for the high-risk loans.  

I would most likely not recommend the model that I have created to a lending company.  While the accuracy of the results was high when looking at the confusion matrix in the code there was a high number of false-positive results and a high number of false-negative results.  Those are values that were predicted high-risk and their actual values were healthy loans or values that were predicted to be healthy loans and ended up being high-risk loans.  Since there were many those values in the confusion matrix a lending company might end up giving out loans to those who shouldn’t get them or even deny those who should be allowed to borrow.  
