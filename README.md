# Spam-Email-Filter

The increase in the number of unwanted emails known as spam emails. A need for the development of more reliable and effective anti-spam filters.

In general, all email communications are labelled as “Ham” or “Spam.” In a mailbox, Ham communications are intended or safe acceptable messages, whereas Spam messages are trash, unwanted mass, or commercial messages. This filtering or categorization of email communications into Ham and Spam aids in separating them and automating the deletion of spam messages. 

The new things I learned while doing this case studies are countvectorizer, multinomialNB classifier.
# Feature Extraction Text:
In natural language processing (NLP), feature extraction is a fundamental task that involves converting raw text data into a format that can be easily processed by machine learning algorithms.
The common techniques for feature extraction in NLP, including CountVectorizer, TF-IDF, word embeddings, bag of words, bag of n-grams, HashingVectorizer, Latent Dirichlet Allocation (LDA), Non-negative Matrix Factorization (NMF), Principal Component Analysis (PCA), t-SNE, and Part-of-Speach (POS) tagging.

# CountVectorizer:
Countvectorizer is a method to convert text to numerical data. It makes it easy for text data to be used directly in machine learning and deep learning models such as text classification.
CountVectorizer is a great tool provided by the scikit-learn library in Python. It is used to transform a given text into a vector on the basis of the frequency (count) of each word that occurs in the entire text. 

# MultinomialNB:
Naive Bayes classification is a classical machine learning technique to predict a discrete value. There are several variations of naive Bayes (NB) including Categorical NB, Bernoulli NB, Gaussian NB and Multinomial NB. The different NB variations are used for different types of predictor data.

The multinomial Naive Bayes classifier is suitable for classification with discrete features (e.g., word counts for text classification).
The classification aims to assign fragments of text (i.e. documents) to classes by determining the probability that a document belongs to the class of other documents, having the same subject.
Each document consists of multiple words (i.e. terms), that contribute to an understanding of a document’s contents. A class is a tag of one or multiple documents, referring to the same subject.


# Sources:
There are many websites on the internet which provides a good understandable explanation with examples and I have mentioned the websites I referred here https://towardsdatascience.com/multinomial-na%C3%AFve-bayes-for-documents-classification-and-natural-language-processing-nlp-e08cc848ce6, https://scikit-learn.org/stable/modules/generated/sklearn.naive_bayes.MultinomialNB.html, https://www.geeksforgeeks.org/using-countvectorizer-to-extracting-features-from-text/, https://towardsdatascience.com/basics-of-countvectorizer-e26677900f9c, https://medium.com/@eskandar.sahel/exploring-feature-extraction-techniques-for-natural-language-processing-46052ee6514, https://scikit-learn.org/stable/modules/feature_extraction.html.
