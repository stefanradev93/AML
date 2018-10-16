# A Neural Conversational Agent
This repository contains the code for our final project for the lecture "Advanced Machine Learning" at Heidelberg University. 

## Prerequisites:
- Python 3.6.
- Tensorflow 1.10.1.
-  NLTK 3.3.
- IPythonNotebook

- download the [Cornell Movie Dialogs Corpus](https://www.cs.cornell.edu/~cristian/Cornell_Movie-Dialogs_Corpus.html)
- download [GloVe word embeddings](https://nlp.stanford.edu/projects/glove/)


## Setup:
- unzip the weights under `./weights/`
- put dialogue data under: `./chatbot/dialogs/cornell_movie-dialogs_corpus/`
- put embeddings under: `./embeddings/`
- for training: create two folders `./logs/` and `./checkpoints/`


## Contents:
- `seq2seq_attention_final-GPU-Basic.ipynb` : training the Basic model
- `seq2seq_attention_final-GPU.ipynb` : training the Attention model
- `seq2seq_conversations.ipynb` : samples of chatbot conversations (Basic, static Attention, dynamic Attention)
- `seq2seq-Attention.ipynb` : visualization of Attention weights
- `seq2seq_eval-BLEU.ipynb` : calculate BLEU score
- `seq2seq_eval-text-analysis.ipynb` : calculate text statistics
