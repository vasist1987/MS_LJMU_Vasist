# CodeBase for MS thesis 
## Comparative study of different predictive models for the task of text similarity

In this comparative study various language techniques have been explored right from data cleaning- feature engineering - class imbalancing - choice embedding - modelling, an extensive comparative was conducted to determine optimal language model which is both accurate and fast.


![image](https://user-images.githubusercontent.com/35446640/110976679-2fc20480-8387-11eb-8571-32ccc7387b81.png)

Data Pre-Processing:
1. Spelling mistakes are corrected and stop words are removed.
2. Lemming and Stemming was tried in different combinations for different models.
3. POS and NER were also tried in different combinations with different models.
4. Class imbalancing techniques like SMOTE under balancing and over balancing were tried, Also was stratified approach.

Embedding:
1. GloVe 100,200, 300 and word2vec pre-trained embeddings were evalutaed on.
2. TFIDF and count vectorizer was also explored as part of this study.

Machine Learning approaches:
1. Logistic Regression with SAG optimizer was tried as the model converges faster.
2. Naive Bayes also was tried with different combiations.

Boosting Tree Models:
1. LightGBM and CatBoost models are used for evaluation.

Neural Network:
1. Simple GRU model with 2 layers was tried as aim of the study was to find optimal model.

Ensemble Approach:
1. Ensemble approach of stacking was tried on the best machine/ tree models and obtained better result than the base models.

Transfer Learning:
1. DistilBERT was explored as it is distilled model and one of the smallest yet powerful model in BERT family.
2. ALBERT was also explored as again this is one of the smaller models.

Below are the top results obtained after extensive exploratory research of more than 200 language models.

![image](https://user-images.githubusercontent.com/35446640/110979977-584bfd80-838b-11eb-89d2-6f8672d72bc4.png)


Code refractoring is pending will be done in due time.
