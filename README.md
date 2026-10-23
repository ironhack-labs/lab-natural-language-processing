![logo_ironhack_blue 7](https://user-images.githubusercontent.com/23629340/40541063-a07a0a8a-601a-11e8-91b5-2f13e4e6b441.png)

# Lab | Natural Language Processing


## Introduction

Advance-fee fraud emails, the "I am a bank manager and need your help to transfer 25 million dollars" kind, are still sent by the million, and every email provider filters them with a text classifier. In this lab you build one. You clean almost 6,000 emails, remove stop words and lemmatise them, look at the words that tell the two classes apart, turn the text into TF-IDF features, add a few features of your own, and train a Naive Bayes classifier. At the end you use it on emails it has never seen, and find out what it really learned.

The lab follows the **NLP Fundamentals** lesson step by step.


## Getting Started

Open the `main.ipynb` file in the `your-code` directory. Follow the instructions, add your code, and answer the questions in the markdown cells. The data is in the `data` folder: `kg_train.csv` has the labelled emails, and `kg_test.csv` has emails without labels for the last challenge.

The first run of the notebook downloads a few NLTK resources, so you need an internet connection.

## Deliverables

- `main.ipynb` with your code and your answers.

## Submission

Upon completion, add your deliverables to git. Then commit git and push your branch to the remote.

## Resources

- [scikit-learn user guide: Working with text data](https://scikit-learn.org/stable/modules/feature_extraction.html#text-feature-extraction)
- [Python documentation: Regular expression HOWTO](https://docs.python.org/3/howto/regex.html)
- [NLTK book, chapter 3: Processing raw text](https://www.nltk.org/book/ch03.html)
