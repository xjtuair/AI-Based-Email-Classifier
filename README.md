AI-BASED-EMAIL-CLASSIFIER:
--------------------
This project includes text classification which is a multi-class classification where different classifiers are trained and tested using Python. The email classification is based on the content into three categories: Normal, Spam, and Fraud.

The classifiers used include Support Vector Machine (SVM), K-Nearest Neighbour, Multinomial Naïve Bayes, Decision Tree, Logistic Regression, SVM with Stochastic Gradient Descent classifier (SGD-SVM) and Logistic Regression with Stochastic Gradient Descent classifier (SGD-LR). All these classifiers are trained with features extracted using the TF-IDF vectorizer.
Further, ensemble classifiers including Random Forest (RF), AdaBoost, Bagging (BGC), Extra Trees and, Vote on various classifier combinations are trained in a similar manner. The effect of stemming on the model performance is also analyzed.
Finally, all the models' performances are evaluated based on standard evaluation metrics: Accuracy, Precision, Recall, F-Score, and Confusion Matrix.

PREREQUISITES:
--------------
<ul>
   <Li> Python 3.x. </li>
  <Li> Libraries: </li>
  <ul>
    <Li> Pandas </li>
    <Li> Sklearn </li>
    <Li> Nltk </li>
    <Li> Numpy </li>
    <Li> Matplotlib </li>
    <Li> String </li>
    <Li> re </li>
    <Li> Random </li>
  </Ul>
</Ul>

CODE BRIEF:
----------
The entire coding is done in Python3.5. The project involves two key Python files ‘Extract_email.py’ and ‘Email_Classification.py’ which handle the process of Data Extraction and, Text processing and classification respectively.

I. Extract_email.py:
This file handles the process of Data Extraction.

II. Email_Classification.py:
This file handles the entire process of email processing and classification.

1. Data Preprocessing:
Functions handle the removal of 