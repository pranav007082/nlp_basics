# nlp_basics
notes of nlp

This repo is basically give some insight into nlp basics 

# NLP Pipeline
1.Data Acquisition : To get necessary data(raw) required to solve a given nlp problem

2.Text Extraction and cleanup : removing irrelevant information,correcting spell checks,etc..

3.Preprocessing:

i.Sentence tokenization:Breaking big para into sentences

ii.Breaking sentence into words

iii.Using Stemming and Lemmatization to convert words into their respective base words(eating->eat)

4.Feature Engineering : Converting words into numbers vector by some techniques

5.Model Building: Use a ML model

6.Evaluation: Evaluating current model and re iterate to preprocessing step so that we can make our model better.

7.final step: deployment and monitor and update.

# Text Representation

1.We cannot use label encoding and one hot enconding in feature engineering/text representation due to following issues:

i.dissimilar representations of similar words

ii.too much memory consumption(in case of one hot encoding)

iii.out of vocabulary issue

So it's better to use bag of words approach.