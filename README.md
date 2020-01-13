# Recommender System for Academic Literature
This is an experiment in using text mining on academic literature in a prospective manner. The eventual goal is to develop a tool for identifying novel interdisciplinary connections. I extract keyword-like features from research documents to pick up on latent terminological trends.

# Current focus
- Find a way to reliably assess the quality of the results, since doing so manually requires a high degree of domain specialization.

- Assess the generalizability to arbitrary research disciplines

- Identify synonymous and conflicting definitions between research disciplines

# Files

- plos_preprocess.py

  - Package to extract and clean text from PLOS .xml files.

- keyword_model.py

  - Package to extract bag of words from text data.

- autoencoder.py

  - Script to test the use of an autoencoder for improving feature extraction

  - Can be interpreted as "studying the material through core concepts and keywords"
  
  - Looking into: Can these be used to model different research "perspectives" given a set of keywords? 

- arxiv_tests.py

  - Model tests on arXiv ML abstracts

- ploss_tests.py

  - Model tests on PLOSS articles from the category of computational biology
  
- arxiv_feat_test.py

  - Script to test different feature extraction techniques
