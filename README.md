# Natural-Language-Processing-TensorFlow

This repository contains the code for the labs in the Natural Language Processing course on Coursera.

Following are the contents of the notebooks:

Week 1: 
- Exploring the BBC news archive.
- Removing the Stopwords from the sentences.
- Converting the sentences to sequences and using tokenizer for fitting the words on index.

Week 2: 
- This week's notebook is focused on word embedding.
- In this notebook, you will find some code from the previous notebook
- By the end, some new functions like pad_sequences are introduced. Padding can be done at the start of the word vector or at the end.
- In TensorFlow, another layer at the start can be used to take embedding as input. This is called Embedding Layer. It will take the number of words as input, dimensions of the embedding, as well as the maxlength of the sequence.

Week 3:
- In this week's notebook, the focus will be on the overfitting encountered during the last week.
- Some common methods to avoid overfitting includes using Dropout layer and combination of various other layers as such LSTM, Conv1D, GlobalAveragePooling1D or MaxPooling1D.
- You can experiment with different hyper-parameters and layers to check the loss and accuracy using the graphs

Week 4:
- In this notebook, you will find the code on using the pre-existing training data during the training.
- The notebook is focused in predicting the next words and this happens by using the Bidirectional LSTM (in this particular notebook).
- The output is done by having a number of units for each word in the corpus.
- For encoding the words, one-hot encoding is used.

Apart from this, you will be able to find the basic functions that might be useful in building NLP networks. 
