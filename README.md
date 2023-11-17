# GRU-Movie-Sentiment-Analysis-using-GloVe-Embeddings

This repository includes code for sentiment analysis using Gated Recurrent Unit (GRU) networks with pre-trained GloVe word embeddings. The goal is to classify movie reviews into positive or negative sentiments using deep learning techniques, specifically GRU networks and GloVe word embeddings. The dataset used is movie data. Data preprocessing involves splitting reviews and sentiments and tokenizing text data for model input. GloVe word embeddings (100-dimensional) are employed to represent words in a numerical format. These embeddings are loaded and utilized to create the embedding matrix. The GRU-based neural network architecture includes an Embedding layer, GRU layer, and a Dense output layer with a sigmoid activation function. The model is trained with early stopping to prevent overfitting. After training, evaluation metrics such as accuracy, a classification report, and a confusion matrix are generated.

#### Requirements
Python 3.x   Libraries: pandas, matplotlib, seaborn, numpy, TensorFlow, scikit-learn
