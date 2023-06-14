# Detecting_fake_news this is a demo learned from a Data Science blog on NLP:
## Fake News
A sort of sensationalist reporting, counterfeit news embodies bits of information that might be lies and is, for the most part, spread through web-based media and other online media.

This is regularly done to further or force certain kinds of thoughts or for false promotion of products and is frequently accomplished with political plans.

Such news things may contain bogus and additionally misrepresented cases and may wind up being virtualized by calculations, and clients may wind up in a channel bubble.
##  Tfidf Vectorizer
TF (Term Frequency):  In the document, words are present so many times that is called term frequency. In this section, if you get the largest values it means that word is present so many times with respect to other words. when you get word is parts of speech word that means the document is a very nice match.

IDF (Inverse Document Frequency): in a single document, words are present so many times, but also available so many times in another document also which is not relevant. IDF is a proportion of how critical a term is in the whole corpus.

collection of word Documents will convert into the matrix which contains TF-IDF features using  TfidfVectorizer.
## About the Project
DATA Analysis:
Explaination about the dataset.

In this python project, we have used the CSV dataset. The dataset contains 7796 rows and 4 columns.

This dataset has four columns,

title: this represents the title of the news.
author: this represents the name of the author who has written the news.
text: this column has the news itself.
label: fake and real.
The dataset is open-sourced and can be found here.
