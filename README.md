<h1 align="center"> Virtual Health Medical Journals Analysis </h1> <br>
<p align="center">
  <a href="http://clipart-library.com/clipart/kc8odg89i.htm">
    <img alt="Virtual Health Medical Journals Analysis" title="Virtual Health Medical Journals Analysis" src="http://clipart-library.com/images/kc8odg89i.jpg" width="350">
  </a>
</p>

This project utilizes Text Mining Techniques to recommend Articles Textually, Contextually & based on Topics similarity for the Medical Research using abstracts from the Virtual Health Library database.

## Introduction

The primary purpose is to build a web application platform for article recommendation that will easily help medical researchers to search for articles. The results of the search, either with a keyword or a journal will, allow user to choose from the Articles based on Categorization of Results.

### Models

Following are the three models utilized for this project:

* Latent Dirichlet Allocation (LDA) Multicore 
* Latent Semantic Indexing (LSI)
* BERT NLI Senence Transformer

### Latent Dirichlet Allocation (LDA) Multicore

This module allows both LDA model estimation from a training corpus and inference of topic distribution on new, unseen documents. LDA Multicore provides a faster implementation, especially for exceptionally large corpora as in this case. Following is the model representation.

<p align="left">
  <a href="https://www.analyticsvidhya.com/blog/2021/06/part-2-topic-modeling-and-latent-dirichlet-allocation-lda-using-gensim-and-sklearn">
    <img alt="LDA Multicore Topic Modeling" title="LDA Multicore Topic Modeling" src="https://www.researchgate.net/profile/Diego-Buenano-Fernandez/publication/339368709/figure/fig1/AS:860489982689280@1582168207260/Schematic-of-LDA-algorithm.jpg" width="350">
  </a>
</p>


### Latent Semantic Indexing (LSI) Model

LSI is based on the principle that words that are used in the same contexts tend to have similar meanings. A key feature of LSI is its ability to extract the conceptual content of a body of text by establishing associations between those terms that occur in similar contexts.

<p align="left">
  <a href="https://medium.com/analytics-vidhya/nlp-with-latent-semantic-analysis-b3de6e16ad7d">
    <img alt="LDA Multicore Topic Modelling" title="LDA Multicore Topic Modelling" src="https://miro.medium.com/max/1400/1*tctmPjlqV66mR9s-I5bzMg.jpeg" width="350">
  </a>
</p>
