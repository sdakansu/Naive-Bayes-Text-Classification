# Naive-Bayes-Text-Classification

## Input
There are train and test datasets. Input format is following:
id,text,label

Dataset is obtained from [SuDer](https://github.com/suverim/suder) Turkish News Collections. 

## Preprocessing
* Lowercase conversion
* Category --> Integer
* Tokenize

## TFIDFVectorizer
Term Frequency - Inverse Document Frequency is a type of word representation according to word frequency and document frequency. It converts words to numerical vectors. Each vector represents a word. Therefore we can obtain a vector space that represents words. For more information, click [here](https://medium.com/nlpgurukool/tfidf-vectorizer-5421f1528402). Also package is accessible [here](https://scikit-learn.org/stable/modules/generated/sklearn.feature_extraction.text.TfidfVectorizer.html).

## GridSearchCV
GridSearchCV finds the best combination of given parameters. It is used for both Naive Bayes and Logistic Regression. For more information, you can click [here](https://scikit-learn.org/stable/modules/generated/sklearn.model_selection.GridSearchCV.html). 

## Results
Results are measured through test data. Naive Bayes has an accuracy of 0.702 and logistic regression has an accuracy of 0.824.

## Dataset
