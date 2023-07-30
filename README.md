# PyTorch Seq2Seq

## Note: This repo only works with torchtext 0.9 or above which requires PyTorch 1.8 or above. 

This repo contains tutorials covering understanding and implementing sequence-to-sequence (seq2seq) models using [PyTorch](https://github.com/pytorch/pytorch) 1.8, [torchtext](https://github.com/pytorch/text) 0.9 and [spaCy](https://spacy.io/) 3.0, using Python 3.8.

## Getting Started

To install PyTorch, see installation instructions on the [PyTorch website](pytorch.org).

To install torchtext:

``` bash
pip install torchtext
```

We'll also make use of spaCy to tokenize our data. To install spaCy, follow the instructions [here](https://spacy.io/usage/) making sure to install both the English and German models with:

``` bash
python -m spacy download en_core_web_sm
python -m spacy download de_core_news_sm
```

## Tutorials

* 1 - [Sequence to Sequence Learning with Neural Networks
This project covers the workflow of a PyTorch with torchtext seq2seq project. It cover the basics of seq2seq networks using encoder-decoder models, how to implement these models in PyTorch, and how to use torchtext to do all of the heavy lifting with regards to text processing. The model itself will be based off an implementation of [Sequence to Sequence Learning with Neural Networks](https://arxiv.org/abs/1409.3215), which uses multi-layer LSTMs which was replace by GRU.
