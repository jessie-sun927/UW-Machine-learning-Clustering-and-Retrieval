## Week2 Topics:
* Implement nearest neighbor search for retrieval tasks
* Contrast document representations
  - Bag of words
  - TF-IDF
  * In BOW, common words count could dominate rare words count, while TF-IDF penalize common words
  * Since TF-IDF penalize frequent words, less need to deal with stop words explicitly
* Contrast methods for measuring similarity between two documents
  - Euclidean vs. weighted Euclidean
  - Cosine similarity vs. similarity(unnormalized inner product)
  * Euclidean distance are often used when features are numeric, cosine similarity is used when features are texts
  * Using Euclidean distance might favor short text in measuring similarity
  * Cosine similarity would ignore the text length, which is not always desired since it could make dissimilar objects appear more similar


## Algorithms: 
* Bag of words model, TF-IDF, Nearest Neighbor Search, KNN


## Implementation Details of Programming Assignment 1:

Goal: 
  * Gain intuition for different notions of similarity and practice finding similar documents. 
  * Explore the tradeoffs with representing documents using raw word counts and TF-IDF
  * Explore the behavior of different distance metrics by looking at the Wikipedia pages most similar to President Obama’s page.

* Find nearest neighbor of the Barack Obama page using raw word count and Euclidean distance measure
* Explore the problem of BOW model by finding common words between neighbors and how many articles contain these common words
* Find nearest neighbor of the Barack Obama page using TF-IDF and Euclidean distance measure
* Explore the benefits of TF-IDF by finding common words between neighbors and how many articles contain these common words
* Explore the problem of Euclidean distance measure by comparing the 100NN's document length
* Find nearest neighbor of the Barack Obama page using TF-IDF and Cosine similarity(distance)
* EXplore the problem of cosine similarity by calcuating the distance between a short tweet and a long article
