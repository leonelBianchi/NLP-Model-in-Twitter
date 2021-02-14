# NLP-Model-in-Twitter

Quick model to find patterns in tweets and classify them in positive or negative. We use simple and common natural language processing techniques to achieve a good performance of the model such as tokenization and word embedding. Then, the model is a neural network built with Tensorflow/Keras. To reach good results, we needed to low the learning rate and make the model less complex (two hidden layers of 4 neurons) to avoid overfitting.

The dataset used can be found in https://www.kaggle.com/crowdflower/twitter-airline-sentiment. It is a set of tweets made by travelers in February 2015 with its corresponding label. That is to say, each tweet has a label associated with it: positive, negative or neutral. To make the model simpler, we will only use the positive and negative tweets and use the sigmoid function to classify. If we wanted to use the three categories, the tanh for ouput layer could be a good choice (using 1,0,-1 as categorical values).
