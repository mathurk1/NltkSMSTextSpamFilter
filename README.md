# NltkSMSTextSpamFilter

Implemented a SMS Spam Filter using Natural Language Processing / NLTK and Machine Learning Algorithms to classify SMS text as ham (legit texts) or spam.

Obtained the data from <https://www.kaggle.com/uciml/sms-spam-collection-dataset>

A snapshot of the data:

v1 | v2
--- | ---
ham | Go until jurong point, crazy.. Available only in bugis n great world la e buffet... Cine there got amore wat...
ham | Ok lar... Joking wif u oni...
spam | Free entry in 2 a wkly comp to win FA Cup final tkts 21st May 2005. Text FA to 87121 to receive entry question(std txt rate)T&C's apply 08452810075over18's

We used nltk to tokenize the text, remove all stopwords (words that do not add any value in identifying weather the text is spam or legit)
and then ran the data through 

* Naive Bayes
* kNN
* SVM
* Random Forest
