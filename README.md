# Transaction Fraud Detection

Use single decision tree, random forest, logistic regressions on variables selected by Lasso and RFE to detect fraud transactions.

## Description

Since the explosion of wire transactions and online banking, financial fraud has been on the rise. 
According to a report by TransUnion, a consumer credit reporting agency, global digital fraud attempts in the financial services sector have risen 149% in the first four months of 2021 compared to the last four months of 2020. 
In the U.S., digital fraud attempts have risen 109% in the first four months of 2021. 
Furthermore, a recent study from Juniper Research stated that businesses in eCommerce, airline ticketing, money transfer, and banking services would have an expected loss over $200 billion between 2020 and 2024.
In addition, Juniper Research found that digital money transfer fraud is growing, especially in emerging markets. Due to advances in technology, fraudsters have increased their avenues of attempting fraud as well as increased sophistication in their attempts. 


As the financial services industry continues to find new ways to interact with consumers, fraud analytics is an increasing area of importance.
Our study is designed to explore transaction fraud in the context of banking services by promoting a statistical model that can make binary decisions on whether transactions are fraudulent based on key characteristics. 

## Getting Started

### Data source

You can download the transaction.csv dataset from Kaggle https://www.kaggle.com/ealaxi/paysim1

### Installing

If you want to run the project locally, make sure to install python and corresponding dependencies.

## Authors

* Zengxiaoran Kang
* Kazy Atausha

## Acknowledgments

Inspiration, code snippets, etc.
* Fraudulent transaction definition reference - https://www.creditcards.com/credit-card-news/glossary/term-fraudulent-transaction/
* Data source: https://www.kaggle.com/ealaxi/paysim1
* Paper reference: https://www.sciencedirect.com/science/article/abs/pii/S0065245820300851
* Article reference:
  * Digital Fraud - https://newsroom.transunion.com/suspected-financial-services-digital-fraud-attempts-rise-nearly-150-worldwide-as-prevalence-of-digital-transactions-increase/
  * online payment Fraud - https://www.juniperresearch.com/press/online-payment-fraud-losses-to-exceed-200-billion
* Methods reference: 
  * Rpart - https://www.rdocumentation.org/packages/rpart/versions/4.1-15/topics/rpart
  * Random forest - https://towardsdatascience.com/why-random-forests-outperform-decision-trees-1b0f175a0b5
  * Random forest, OOB - https://scikit-learn.org/stable/modules/generated/sklearn.ensemble.RandomForestClassifier.html
  * Logistic regression - https://scikit-learn.org/stable/modules/generated/sklearn.linear_model.LogisticRegression.html
  * Rfe - https://machinelearningmastery.com/rfe-feature-selection-in-python/
  * Lasso - https://www.publichealth.columbia.edu/research/population-health-methods/least-absolute-shrinkage-and-selection-operator-lasso
  * Anomaly detection methods - https://towardsdatascience.com/anomaly-fraud-detection-a-quick-overview-28641ec49ec1
  * Variable Selection methods - https://web.stanford.edu/~hastie/ISLRv2_website.pdf


