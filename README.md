# energy_bill

Using the data in the file CE802_P2_Data.csv contained in the CE802_P2_Data.zip archive, you are required to perform a comparative study of the following machine learning proce- dures:
• a Decision Tree classifier;
• at least two more ML techniques to predict if a new customer is prone to suffer from energy
rising prices.
You will notice that one of the features, is missing for some of the instances. You are therefore required to deal with the problem of missing features before you can proceed with the prediction step. As a baseline approach, you may try to discard the feature altogether and train on the remaining features. You are then encouraged to experiment with different imputation methods.
AENERGY uses Python internally and therefore Python with scikit-learn is the required lan- guage and machine learning library for the problem. For this task, you are expected to submit a Jupyter Notebook called CE802_P2_Notebook.ipynb containing the Python code used to perform the comparative analysis and produce the results, as well as the code used to perform the predictions described in task “b” below.
b) Prediction on a hold-out test set. An additional dataset, CE802_P2_Test.csv, is provided inside the CE802_P2_Data.zip archive. Binary outcomes are withheld for this test set (i.e. the “Class” column is empty). In this second task, you are required to produce class predictions of the records in the test set using one approach of your choice among those tested in task “a” (for example the one achieving the best performance). These data must not be used other than to test the algorithm trained on the training data.

a) Investigate the performance of a number of machine learning procedures on this dataset. Using the data in the file CE802_P3_Data.csv contained in the CE802_P3_Data.zip archive, you are required to perform a comparative study of the following machine learning proce- dures:
• Linear Regression;
• at least two more ML techniques to predict the value of the variation in annual expenditure
for each customer ( in £/year ).
The company AENERGY uses Python internally and therefore Python with scikit-learn is the required language and machine learning library for the problem. For this task, you are expected to submit a Jupyter Notebook called CE802_P3_Notebook.ipynb containing the Python code used to perform the comparative analysis and produce the results as well as the code used to perform the predictions described in task “b” below.
b) Prediction on a hold-out test set. An additional dataset, CE802_P3_Test.csv, is provided inside the CE802_P3_Data.zip archive. Target values are withheld for this test set (i.e. the “Value” column is empty). In this second task, you are required to produce predictions of the records in the test set using one approach of your choice among those tested in task “a” (for example the one achieving the best performance). These data must not be used other than to test the algorithm trained on the training data.
As part of your submission you should submit a new version of the file CE802_P3_Test.csv in CSV format with the missing “Value” column replaced with the output predictions obtained using the approach chosen. This second task will be marked based on the mean squared error on the test set.

**Distribution Plot**

<img width="445" alt="image" src="https://github.com/kanishk-garg97/energy_bill/assets/39979689/8e6ee776-e46e-4669-a152-2d71e0b4746d">

**Correlation Matrix of features in dataset**

<img width="541" alt="image" src="https://github.com/kanishk-garg97/energy_bill/assets/39979689/536bc8d4-3992-4ef1-a44f-3784008e5453">

**Decision Tree with its Accuracy**

<img width="788" alt="image" src="https://github.com/kanishk-garg97/energy_bill/assets/39979689/4c7867e7-058e-4117-b522-5fece4270829">

**Confusion Matrix using Random Forest Classifier**

<img width="471" alt="image" src="https://github.com/kanishk-garg97/energy_bill/assets/39979689/beaa51c0-248c-4417-9af5-c65070d19442">

**Confusion Matrix using Support Vector Classifier**

<img width="435" alt="image" src="https://github.com/kanishk-garg97/energy_bill/assets/39979689/354bdba9-9da8-4d60-89fb-50a86f24d0e8">

**Confusion Matrix using Decision Tree**

<img width="436" alt="image" src="https://github.com/kanishk-garg97/energy_bill/assets/39979689/c3f4c6f1-22c9-4766-b921-c7bfb66be9c1">









