# Emotion Recognition project

this repository contains project files in the area of natural language processing. In particular, deep learning algorithms have been applied for emotion recognition tasks, which can create classification models that recognize human emotions in text.

### Dataset :bar_chart:

The dataset used is called TwIT and consists of Italian Twitter Dataset for Emotion Recognition with 3108 records and 3 columns. The variables are 'Id', 'Text' and 'Emotion'. Emotion is expressed in the following forms:


0 | Happiness :smile:
-|-
1 | Trust     :thumbsup:
2 | Sadness   :cry:
3 | Anger     :angry:
4 | Fear      :scream:
5 | Disgust   :dizzy_face:



### Word2Vec

word2vec is a two-layer neural network designed to process natural language and produce word embeddings.
Specifically, after importing the dataset, it was cleaned, lemmatized and tokenized. Finally, the text corpus was passed to the Word2Vec algorithm to produce Word Embeddings.

### GPT-3

GPT-3 is a language model created by OpenAI that can produce text similar to human language. The GPT-3 architecture is pre-trained and has 175 billion parameters and 96 hidden layers, trained on 500 billion pieces of data from Common Crawl, Wikipedia and textbooks.
The following project fine-tunes its classification model achieving amazing results, with 90% accuracy on the test set.

To do this, it is necessary to register at the OpenAI site from [this link](https://openai.com/)

### Google BERT

BERT is a deep learning model designed by Google to process natural language.
Just as in GPT-3, in BERT the model is first pre-trained using a very large neural network, whose computational cost is onerous, to produce word embeddings for use in NLP models.
The pre-trained model can also be invoked through special libraries and tuned with fewer computational resources on smaller datasets and optimizing performance for specific tasks.
The project has tuned a 24-level BERT model to create a classifier optimized to recognize emotions in text.
The results again are excellent, with a model accuracy of 89%.

In order to do this, it is necessary to download the pre-trained bert model from [Huggingface](https://huggingface.co/Davlan/bert-base-multilingual-cased-ner-hrl)


