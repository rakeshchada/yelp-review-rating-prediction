# Yelp Review Rating Prediction

### Summary
The goal of this project was to predict reviews' star ratings on Yelp using the review text. We built the following models that perform text analysis on review data to predict the rating stars.

1. **Baseline Model**: The most common rating, 3 stars, is the rating predicted by this model for all the reviews.
2. **Term Frequency Model**: In this model we use frequency of word occurrence to predict the review rating.
3. **LDA + Sentiment Model**: This model predicts rating using Latent Dirichlet Allocation (LDA) with an added sentiment layer by extracting topics and sentiment associated with the review from review text.
4. **NMF + Sentiment Model**: In this model, we predict review rating using Non-negative Matrix Factorization (NMF) with an added sentiment layer by extracting topics and sentiment associated with the review from review text.

We achieved an accuracy of 61% in predicting review rating stars.

#### Code
Most files are IPython notebooks (`.ipynb` extension with JSON data).

The following modules are used in at least one example:

  * Python 2.7
  * NumPy
  * Pandas
  * Scipy
  * scikit-learn
  * nltk
  * seaborn
  * Matplotlib
  * Gensim
  * IPython 0.13+
  * cPickle

#### Team Members:
- Rakesh Chada
- Chetan Naik