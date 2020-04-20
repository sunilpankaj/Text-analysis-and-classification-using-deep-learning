# Text-analysis-and-classification-using-deep-learning
Text analysis, word embedding, classical machine learning and deep learning for text classification. 

Packages:
1. Python3 ,numpy, pandas 
2. Tensorflow2 
3. NLTK 
Problem Stantement:
Classify sentiment (Positive, Negative, Neutral) of the tweet.

What each file has:
1. Data : Tweets.csv
2. Text_Embeddings_ML.ipynb

   a. Clean text
   
   b. data visualization
   
   c. Create Embeddings (one hot encoder, TF-IDF, Word2Vec)
   
   d. Embeddings Visualization using Truncate_SVD (similar to pca)
   
   e. Model : Logistic Regression and CNN.
   
3. Text_classification_DL.ipynb
   
   a. Create Word2Vec Embeddings
   
   b. Classification using 
      1. LSTM
      2. CNN + LSTM
      3. GRU
      4. Bidirectional LSTM
      5. Deep LSTM
   
   c. Model weights extraction
   
Please note notebooks are provided to use and understand listed all the methods, model are not trained to get best accuracies.

I have used google colab.

Reference for CNN based classifiaction (https://arxiv.org/pdf/1408.5882.pdf)

CNN Architecture: 

![CNN_Architecture](https://github.com/sunilpankaj/Text-analysis-and-classification-using-deep-learning/blob/master/CNN_text_classification.png)

![CNN Explaination](https://github.com/sunilpankaj/Text-analysis-and-classification-using-deep-learning/blob/master/CNN_Explaination.png)

Ref: http://www.wildml.com/2015/11/understanding-convolutional-neural-networks-for-nlp/
