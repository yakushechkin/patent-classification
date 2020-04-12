# patent-classification

WIPO-alpha patent classification (GloVe, domain-specific word embeddings, BERT)

**Project Objective:** Use the pre-trained language model BERT to fine-tune a classification model on a domain specific dataset.

**Domain:** ‘Patent application analysis’

**Classification task:** Multi-class classification: WIPO-alpha patent applications are divided into 8 sections, the task is to determine to which section an application belongs.

This project involved all steps from A to Z, from looking for dataset, parsing, deciding which classification task to choose and the implementation of three different approaches (GloVe, domain-specific, BERT) going from simple to complex and getting correspondingly different results.

The models were trained on Cloud TPUs on [Google Colab](http://colab.research.google.com).

FILES:
* **Patent_Classification_BERT.ipynb** - the project itself (Jupyter Notebook)
* **Patent_Classification_BERT.html** - static HTML version
