# fake_news_detection_LSTM
Detecting Fake news with 98% Accuracy

# Download Dataset
!(https://www.kaggle.com/clmentbisaillon/fake-and-real-news-dataset)

=> Using Keras api
_______________________________________________________________________________________________
# Steps :

1. Load csv from fake and true file.
2. Basic NLP Preprocessing like Stemming, Stopwords removal, Deconcate words like can't to cannot,
   Removing punctuation.
3. Use Counter  to count no. of words in the text.
4. Using Keras->Tokenizer to  vectorize a text corpus, by turning each text into either a sequence of integer.
   !(https://keras.io/api/preprocessing/text/)
5. Using keras-> Padding to make sentence equal as LSTM only accepts sentences with same length, This will add 0 if required.
6. Defining a shallow LSTM model, which binds maximum number of words with 32 activation units. 
   ![alt text](https://github.com/zaid7860/fake_news_detection_LSTM/blob/master/Screenshot%202020-07-08%20at%2012.01.02%20AM.png?raw=true)

7. Training and calculating accuracy 
____________________________________________________________________________________________________
