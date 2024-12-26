# A transparent framework for credit risk scoring and fraud detection integrating probabilistic modeling and explainable ai 

Fraudulent activities in financial institutions pose significant risks, making effective detection 
and management of such threats a critical priority.  This study presents an innovative 
framework for credit risk assessment and fraud detection, addressing the limitations of 
traditional systems such as FICO scores. Recognizing the evolving strategies of fraudsters to 
evade detection, the proposed approach utilizes logistic regression to predict the probability of 
charge-off events. These probabilities are then transformed into a Risk Score using a novel 
scoring formula, which quantifies the likelihood of charge-off on a scale from 0 to 1000, with 
higher scores indicating greater risk. Advanced techniques, including Monte Carlo simulations, 
were employed to refine the Risk Score and select the best-performing model, ensuring robust 
and reliable predictions. The logistic regression model demonstrated higher accuracy (83%), 
precision (85%), recall (83%), and AUC-ROC scores (89%) compared to other models. A key 
focus of this framework is explainability and transparency. Through exploratory data analysis 
(EDA) and the coefficients of the logistic regression model, we identified that variables such 
as delinquency status, number of defaults accounts and applications submitted during odd 
hours are the most impactful for predicting charge-off status, serving as strong indicators of 
potential fraudulent risk.  Using Explainable AI (XAI) techniques, specifically LIME (Local 
Interpretable Model-Agnostic Explanations), the model provides clear insights into the features 
driving each prediction. Validation against traditional FICO-based classification methods 
highlights the effectiveness of the proposed framework. The Risk Score framework 
demonstrates significant improvements across multiple metrics, increasing the detection rate 
of high-risk cases from 70% to 80% in test data. By integrating probabilistic modelling with 
interpretable decision-making, this study enhances both the accuracy of fraud detection and 
credit risk assessment while building trust through transparent and explainable risk 
classifications. 
