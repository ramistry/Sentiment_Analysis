# NocturnalNeuro
Repo for creating ANN for classifying.


## 1. Background and Motivation
<br />
This project aims to build a robust sentiment analysis model to classify reviews into Positive, Neutral, or Negative sentiments using a variety of machine learning techniques. 
The project explores different feature extraction methods and evaluates their individual and combined performances..
<br />
<br />
## 2. Key objectives

-Build models using TF-IDF, Word2Vec embeddings, and their combination for sentiment classification.
-Compare the performance of these approaches using logistic regression.
-Highlight techniques that contribute most to improving sentiment classification.
<br />

## 3. Dataset

The dataset used contains customer reviews with the following key columns:
`text`: The gender of the individual (M/F).

`rating`: The star rating assigned to the review (1–5).

`sentiment`: Derived from the rating as follows:
* Positive: Ratings 4–5.
* Neutral: Rating 3.
* Negative: Ratings 1–2.


## 3. Structure
The project repository is structured as follows:

*`TF-IDF with N-grams:` 
** Extracts word-level features (unigrams, bigrams, trigrams).
** Captures term frequency and importance in the corpus.

*`Word2Vec Embeddings`:
**Learns dense vector representations of words.
**Combines word embeddings to create document-level embeddings by averaging word vectors.

*`Combined Features:`
** Combines scaled Word2Vec embeddings with TF-IDF features to capture both semantic and frequency-based relationships.

## 4. Models
* `Logistic Regression:`
**   Used for all experiments (TF-IDF, Word2Vec, and Combined Features).
