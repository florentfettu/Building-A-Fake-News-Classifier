# Building-a-Fake-News-Classifier

## Description

One of the things the Presidential Election Campaign of 2016 may be remembered for is the proliferation of fake news stories. Viral news hoaxes have been around for many years, but 2016 seems to be the year they exploded into the consciousness of the American public. Evaluating information has never been more important.

Our task was to classify whether a news was fake or real. The emphasis has been placed on the application of traditional techniques as Bag-of-words, Stemming or TF-IDF instead of state-of-the-art algorithm for sequential data. We’ve also implemented topic modelling and cosine similarity to better understand our results. 

## Scope of the project

* Text data preprocessing (extract the words, lowercase, remove stopwords, stemming)
* Application of TF-IDF (Term Frequency – Inverse Document Frequency)
* Use predictive models suited to text classification (Naive Bayes, SVM)
* Extract words most prone to discriminate between Fake and Real news through Logistic Regression coefficients
* Use NMF and LDA to see if certain specific topics would emerge and be more prevalent in Real vs Fake news
* Compare the results of ML algorithms with a DL approach, specifically a CNN model
