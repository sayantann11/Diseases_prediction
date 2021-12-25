# Diseases_prediction
**Methods and Methodology:**

**We have used jupyter notebook for the project.**

Import all the necessary libraries.

![](RackMultipart20211225-4-4pak87_html_e85bd877b56dcfd.png)

Data pre-processing and splitting the data to train and test data. The test size is kept to be 25% of the total data.

![](RackMultipart20211225-4-4pak87_html_86690cde20140f5c.png)

We performed logistic regression first and then plotted the train and test accuracy of logistic regression

![](RackMultipart20211225-4-4pak87_html_47612a03c92e83c5.png)

We performed SVM next, the best model was proved to be rbf, with gamma = 1 and C= 25.

![](RackMultipart20211225-4-4pak87_html_b7d252230a816d29.png)

KNN Classification was performed varying the parameters n\_neigbhours, algorithm and metric.

![](RackMultipart20211225-4-4pak87_html_27fb89cc06635277.png)

Decision tree is done with varying criterion, splitter, maximum features and depth.

![](RackMultipart20211225-4-4pak87_html_408e8a6ca27f2b0b.png)

Random forest model with parameters n\_estimators, minimum sample leaf

![](RackMultipart20211225-4-4pak87_html_d1549cb08e909082.png)

XGBoost model

![](RackMultipart20211225-4-4pak87_html_9da00bc0f82c8025.png)

Cross validation for all the models is performed to find the best model.

The graph has also been plotted of all the cross validation models.

![](RackMultipart20211225-4-4pak87_html_6c5d740351d6842c.png)

![](RackMultipart20211225-4-4pak87_html_c422a62eb5e15a68.png)

As through cross validation we can observe that SVM and decision tree is having the max accuracy as compared to other, so in order to find the best model we will compute F1 score Also ,as logistic regression is taking more run time as compared to other model thus we will be ignoring Logistic Regression model.

F1 score has also been calculated to assess which model is better in the six.

![](RackMultipart20211225-4-4pak87_html_3af1b455b756f800.png)

At the end, we also added the doctor and contact information of particular prognosis.

![](RackMultipart20211225-4-4pak87_html_5100496c5f589547.png)

![](RackMultipart20211225-4-4pak87_html_4ca92a269bf41fd2.png)

**OUTPUTS/ RESULTS:**

The best model out of the six models has been calculated

Finding the best model

![](RackMultipart20211225-4-4pak87_html_c53f28e32ec2af0d.png)

The accuracy of the decision tree model was plotted. The graph was plotted between y predicted and y test.

![](RackMultipart20211225-4-4pak87_html_251fe1334a248aed.png)

![](RackMultipart20211225-4-4pak87_html_5235ed0fcbe0cf6e.png)

The graphs have been plotted for every model for better visualization of the data.

**LOGISTIC REGRESSION:**

![](RackMultipart20211225-4-4pak87_html_f2ff1da6afd43994.png)

**SVM MODEL:**

![](RackMultipart20211225-4-4pak87_html_e97256ae258eeda2.png)

**KNN CLASSIFICATION MODEL:**

![](RackMultipart20211225-4-4pak87_html_c7c9f23240660c5a.png)

**DECISION TREE:**

![](RackMultipart20211225-4-4pak87_html_ae57bfddb45ccaa9.png)

**RANDOM FOREST:**

![](RackMultipart20211225-4-4pak87_html_af24b3020958c198.png)

**XGBOOST**

![](RackMultipart20211225-4-4pak87_html_c1ebdc6e8837b999.png)
