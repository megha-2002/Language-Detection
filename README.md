# Language-Detection
Detection of texts and classification of languages.

19AIE205 PYTHON FOR MACHINE LEARNING

Language detection is an important part of Natural Language Processing in which the task is to identify the language of a text. 
Natural Language Processing is a subset of AI, where the goal is to understand natural human language and enable interaction between humans and computers
NLP is an emerging field of importance and has several applications (HealthCare, Text Classification, Advertisements(Sentiment Analysis) )
We have taken a dataset from Kaggle which contains text details of 17 different languages 
Using the text details we have created a model which could detect a given language 
This is a Multinomial classification problem so we have used Logistic Regression and Multinomial Naive Bayes Classifier

Logistic Regression -Used to classify the observations using different types of data and can easily determine the most effective variables used for the classification. 
Multinomial Naive Bayes Classifier implements the naive Bayes algorithm for multinomial distributed data. It is one of the two classic naive Bayes variants used in text classification  

Evaluation metric :-  Accuracy Score

The dataset we took consists 2 columns and 11055 rows
The first column has text  , second column has the language corresponding to the text. 
A total of 17 different languages are present in the dataset

IMPLEMENTATION STEPS

Text Preprocessing - Removed the unwanted characters, punctuations, numbers and many other noisy data.
Train-Test split - Data Frame is split into train and test set. The train set is used to build the model
Converting words to Vectors - Model cannot understand raw form so we need to convert it into vectors. We used TF-IDF vectorizer which creates vectors from the text containing information on the more important words and the less important ones as well. 
Prediction and model evaluation- We used logistic regression and Multinomial Naive bayes.
Evaluation is done using accuracy score.

OBSERVATION

Accuracy for logistic regression is more than that of Naive Bayes. 
For Naive Bayes the training time considerably less than Logistic Regression.  
The model performs well when Logistic Regression is used for the classification.  
