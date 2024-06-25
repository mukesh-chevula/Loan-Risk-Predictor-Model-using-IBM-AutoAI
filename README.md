## Loan Risk Predictor Model using IBM Watson Studio - AutoAI

#### Problem Statement

The bank wants to protect itself from the risk of making loans that are never repaid.

* It’s preparing to launch a new website on which customers can submit requests for loans up to €10,000 and, if their credit is sound, get instant approval.
* The good news is that this will attract customers who want to apply for loans quickly, without a lot of fuss.
* The bad news is that it will give the bank almost no time to investigate each applicant’s credit risk, then reject those who might default on their loan, ultimately costing the bank millions of euros.
* The bank wants you to lead the development of an AI machine learning system that can rapidly predict the risk of granting a loan for each customer who applies.

#### The scope of this experiment

Using simulations of IBM Watson Studio, I built an AI machine learning model, train algorithms on the same data set of bank loans and defaults, then test them competitively, using additional data, to see which predicts defaults most accurately.

#### Data set

Click [Here](https://github.com/IBM/monitor-wml-model-with-watson-openscale/blob/master/data/german_credit_data_biased_training.csv) for the dataset

* I used data from a real German bank that’s fictionalized for this simulation.
* The file contains records of five thousand past loans.
* Each record includes ample data such as the customer’s credit rating, bank account balances, loan purpose, and more—and whether the borrower paid or defaulted on the loan.

#### Steps to follow to create a IBM Watson Studio Project:

Using IBM Watson Studio and a data set, we will simulate the following steps.

* Set up a new project in IBM Watson Studio.
* Create a learning model designed to predict whether an applicant is more likely to pay back or default on a loan.
* Train your model on 90% of your data set, including loan outcomes.
* Test the model on a test set of data (the remaining 10% of the data in the data set) to see which algorithm gives the best predictions.
* Save the final model with highest confidence as a Jupyter notebook.

#### Advantages of Using IBM Watson Studio Over Conventional Programming

#### 1. Ease of Use and Accessibility
- **User-Friendly Interface:** Simplifies data preparation, model building, and deployment.
- **No-Code/Low-Code Environment:** Allows many tasks to be done without extensive coding.

#### 2. Integrated Development Environment
- **All-in-One Platform:** Combines various tools and libraries in one place.
- **Cloud-Based:** Enables easy collaboration, scalability, and access to powerful computing resources.

#### 3. Automated Machine Learning (AutoAI)
- **AutoAI:** Automates tedious tasks like feature engineering, model selection, and hyperparameter tuning, saving time and improving efficiency.
