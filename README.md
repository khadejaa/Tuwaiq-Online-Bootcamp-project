# Arabic Sentiment Analysis 

by: Khadejaa Saad Alshehri

--------
## Abstract
The goal of this project was to use classification models to predict the sentiment analysis of Arabic tweets in order to facilitate capturing public opinions on a topic, product, or service. We used [ASAD](https://www.kaggle.com/c/arabic-sentiment-analysis-2021-kaust/data) public dataset which is intended to accelerate research in Arabic NLP in general, and Arabic sentiment classification in specific. We applied different ML & DL models to achieve different results for this multiclass problem.

## Design
This project originates from the Arabic Sentiment Analysis competition. The data is provided by CAUST presents a three-class positive, negative or neutral for each tweet. Classifying sentiment accurately via ML & DL models would improve research and applications of Arabic NLP.

## Data
[ASAD](https://www.kaggle.com/c/arabic-sentiment-analysis-2021-kaust/data) consists of 95,000 annotated tweets, with three-class sentiments. ASAD has a total of 15,215 positive tweets, 15,267 negative tweets, and 64,518 neutral tweets.

## Algorithms
_word represention_
- CountVectorizer
- TfidfVectorizer
- word2vec

_Models_
- Logistic Regression
- Random Forest Classifier
- Support Vector Machine
- BiLSTM
- BERT

_Model Evaluation and Selection_
The entire training dataset of 95,000 records was split into 80/20 train/test sets. all scores reported below were calculated with the test set only.

Model | Accuracy | macro avg F1 | weighted avg F1
| ------------- |:-------------:| -----:|:-------------:|
Logistic Regression | 0.69 | 0.28 | 0.57
Random Forest Classifier | 0.66 | 0.30 | 0.57
Support Vector Machine |0.69 | 0.28 | 0.57
BiLSTM |0.69 | 0.27 |0.57
BERT |0.69 | 0.27 | 0.57



## Tools
* Numpy and Pandas for data manipulation
* Scikit-learn, Keras, tensorflow, simpletransformers for modeling
* Matplotlib for plotting
* spacy, nltk for NLP 
