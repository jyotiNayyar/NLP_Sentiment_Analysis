# NLP_Sentiment_Analysis

NLP - Group Project

In this project, we aim to build supervised models for sentiment analysis on Amazon Customer Reviews Dataset (Video Games category) using NLP. The findings show that the best scikit-learn models to conduct sentiment analysis on our selected dataset are Multiclass Logistic Regression and Linear Support Vector Machine with TF-IDF vectorization. A BERT model was fine-tuned, and it outperformed the scikit-learn models on the same task, even with a relatively smaller training set.

The project structure is as mentioned below -

Exploratory_Data_Analysis_Code.ipynb : The python file is used to do exploratory analysis on the amazon reviews dataset. The code helps in performing tasks like creating word clouds, exploring length of reviews and review context across sentiments. 
Scikit_learn_modelling.ipynb : The python file is used to train scikit-learn models for sentiment prediction.
Code_Transformer_modelling.ipynb : The python file is used to train BERT for sentiment prediction on our dataset.
