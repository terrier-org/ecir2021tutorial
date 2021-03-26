# IR From Bag-of-words to BERT and Beyond through Practical Experiments

This is the official repository of "*IR From Bag-of-words to BERT and Beyond through Practical Experiments*", an [ECIR 2021](https://www.ecir2021.eu) full-day tutorial with [PyTerrier](https://github.com/terrier-org/pyterrier) and [OpenNIR](https://opennir.net) search toolkits.

# About the tutorial

Advances from the natural language processing community have recently sparked a renaissance in the task of adhoc search. Particularly, large contextualized language modeling techniques, such as [BERT](https://en.wikipedia.org/wiki/BERT_(language_model)), have equipped ranking models with a far deeper understanding of language than the capabilities of previous bag-of-words ([BoW](https://en.wikipedia.org/wiki/Bag-of-words_model)) models. Applying these techniques to a new task is tricky, requiring knowledge of deep learning frameworks, and significant scripting and data munging. In this full-day tutorial, we build up from foundational retrieval principles to the latest neural ranking techniques. We provide background on classical (e.g., [BoW](https://en.wikipedia.org/wiki/Bag-of-words_model)), modern (e.g., [Learning to Rank](https://en.wikipedia.org/wiki/Learning_to_rank)) and contemporary (e.g., [BERT](https://en.wikipedia.org/wiki/BERT_(language_model)) search ranking and re-ranking techniques. Going further, we detail and demonstrate how these can be easily experimentally applied to new search tasks in a new declarative style of conducting experiments exemplified by the [PyTerrier](https://github.com/terrier-org/pyterrier) and [OpenNIR](https://opennir.net) search toolkits.

This tutorial is interactive in nature for participants; it is broken into sessions, each of which mixes explanatory presentation with hands-on activities using prepared Jupyter notebooks running on the [Google Colab](https://colab.research.google.com/) platform.

At the end of the tutorial, participants will be comfortable accessing classical inverted index data structures, building declarative retrieval pipelines, and conducting experiments using state-of-the-art neural ranking models.

# Authors

* [Sean MacAvaney](https://macavaney.us), University of Glasgow, UK
* [Craig Macdonald](http://www.dcs.gla.ac.uk/~craigm/), University of Glasgow, UK
* [Nicola Tonellotto](http://tonellotto.github.io), University of Pisa, IT

# Contents

* Part 1: Classical IR: indexing, retrieval and evaluation 
  - [Slides](slides/part1.pdf)
  - [Jupyter Notebook](notebooks/notebook1.ipynb) [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/terrier-org/ecir2021tutorial/blob/main/notebooks/notebook1.ipynb)
* Part 2: Modern Retrieval Architectures: PyTerrier data model and operators, towards re-rankers and learning-to-rank
  - [Slides](slides/part2.pdf)
  - [Jupyter Notebook](notebooks/xxxx.ipynb)
* Part 3: Contemporary Retrieval Architectures: Neural re-rankers such as BERT, EPIC, ColBERT
  - [Slides](slides/part3.pdf)
  - [Jupyter Notebook](notebooks/xxxx.ipynb)
* Part 4: Recent Advances beyond the classical inverted index: neural inverted index augmentation, nearest neighbor search, dense retrieval
  - [Slides](slides/part4.pdf)
  - [doc2query and DeepCT notebook](notebooks/notebook4.0.ipynb) [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/terrier-org/ecir2021tutorial/blob/main/notebooks/notebook4.0.ipynb)
  - [ANCE notebook](notebooks/notebook4.1.ipynb) [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/terrier-org/ecir2021tutorial/blob/main/notebooks/notebook4.1.ipynb)
  - [ColBERT notebook](notebooks/notebook4.2.ipynb) [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/terrier-org/ecir2021tutorial/blob/main/notebooks/notebook4.2.ipynb)

# Feedback

If you attended our ECIR 2021 tutorial, please could you complete this anonymous feedback quiz https://forms.office.com/r/2WbpLiQmWV
