# Credit_Risk_Analysis
![image](https://user-images.githubusercontent.com/67808057/98490406-46dcc400-21e6-11eb-9313-c4e6c113ddd7.png)


## Overview 
This project uses machine learning to create prediction models for a classification problem of credit risk. Credit risk is an inherently unbalanced classification problem because good loans easily outnumber risky loans. Different techniques are used to train and evaluate models with unbalanced classes.


## Results


- **BACKGROUND INFO:**

![image](https://user-images.githubusercontent.com/67808057/98490277-e2216980-21e5-11eb-8317-bca04cb370cd.png)

  - Precision Score= (Predicted True/ (Predicted True + False Positive)
  
    -People that were positive, we want to know the likelihood of actually being positive.
    
  - Recall Score= (Predicted True/ Predicted True + False Negative)
  
    -Person knows has a good loan status, but wants to know what the loan officer will give. 
    

**BalancedRandomForestClassifier**

<img width="801" alt="Screen Shot 2020-11-08 at 4 39 58 PM" src="https://user-images.githubusercontent.com/67808057/98489026-1e9e9680-21e1-11eb-8cff-5eff0737c642.png">
    
  
- Accuracy_score (r_squared)= .79
- Precision= .99
- Recall= .85
 

**Ensemble AdaBoost Classifier**

<img width="799" alt="Screen Shot 2020-11-08 at 4 47 27 PM" src="https://user-images.githubusercontent.com/67808057/98489289-31659b00-21e2-11eb-8725-33b01bc332c5.png">


- Accuracy_score (r_squared)= .91
- Precision= .99
- Recall= .93



**Naive Random Oversampling w/ Logistic Regression**

<img width="783" alt="Screen Shot 2020-11-08 at 4 51 00 PM" src="https://user-images.githubusercontent.com/67808057/98489386-aa64f280-21e2-11eb-88b1-1690bff4d644.png">

- Accuracy_score (r_squared)= .68
- Precision= .99
- Recall= .68


**SMOTE Oversampling w/ Logistic Regression**

<img width="791" alt="Screen Shot 2020-11-08 at 4 53 20 PM" src="https://user-images.githubusercontent.com/67808057/98489478-ffa10400-21e2-11eb-9169-9bce628df054.png">

- Accuracy_score (r_squared)= .66
- Precision= .99
- Recall= .69

**ClusterCentroids Undersampling w/ Logistic Regression**

<img width="814" alt="Screen Shot 2020-11-08 at 4 54 57 PM" src="https://user-images.githubusercontent.com/67808057/98489527-3119cf80-21e3-11eb-80fb-e93835233699.png">

- Accuracy_score (r_squared)= .60
- Precision= .99
- Recall= .53


**Combination (Over and Under) Sampling w/ Logistic Regression**

<img width="792" alt="Screen Shot 2020-11-08 at 4 56 42 PM" src="https://user-images.githubusercontent.com/67808057/98489590-7d650f80-21e3-11eb-8a97-d9f3d872ba1c.png">

- Accuracy_score (r_squared)= .66
- Precision= .99
- Recall= .64


## Summary
The best model to predict the unbalanced classification problem of credit risk is the **Ensemble AdaBoost Classifier** and the Balanced Random Forest Classifier because of high precision, recall, and accuracy scores close to 1 which is ideal for this prediction problem. It is recommended, however, to consider the Ensemble AdaBoost Classifier due to its higher overall scores for a classification prediction. 


 
