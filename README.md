### Project Overview

 Haptik is one of the world's largest conversational AI platforms. It is a personal assistant mobile app, powered by a combination of artificial intelligence and human assistance. It has its domain in multiple fields including customer support, feedback, order status and live chat.

We have with us the dataset of Haptik containing the messages it receives from the customers and which topic(class) the messages refer to.

In this project we created a model predicting which class a particular message belongs to using NLP. We also tried to use techniques like LSA (Latent Semantic Analysis) and LDA (Latent Dirichlet Allocation) to assign topics to new messages.

The dataset consists of message column along with the different column associated with the topic they could associated with it.

We had with us two variations of the same dataset

Train data(40000 rows)

Test data(10000 rows) 


### Learnings from the project

 Tokenization, TFIDF Vectorization
LSI, LDA model building
Coherence Score for optimum number of tppics


### Approach taken to solve the problem

 - Data cleaning to reduce various columns into one column 'Category'
- Classification models to predict category classes. (Logistic Regression, MultinomialNB, LinearSVM)
- Train and test data for training and validation
- Topic Modelling using LSI and LDA


