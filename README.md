# Projects

## 1. Project 1 : Sentiment Analysis

### Introduction
This project was about developing deep learning models for classification and interpretation of emotions(positive and negative) from raw text datasets to help our client **The NDP Group Inc** in sentiment analysis platform service. Based on the datasets about costomers' opinions, provided by the client, performed EDA and developed LSTM, GRU and Bert models. Since LSTM added more than an hour per epoch to the trianing time and accuracy was not so good(91%), I designed GRU model. I expect that it might take much less time to train since GRU model has less number of parameter to train. However the GRU model also took about an hour per epoch and accuracy was 91%. I also tried to put a fully connected additional hidden layer to LSTM model to improve accuracy and it was not improved. Therefore, I developed Bidirectional Encoder Representations from Transformers(BERT) model. It took about 30 minutes to be fine-tuned since the BERT is a pre-trained model and had 96% accuracy.

### Citation
You can find source codes 'https://colab.research.google.com/github/google-research/bert/blob/master/predicting_movie_reviews_with_bert_on_tf_hub.ipynb'


## 2. Project 2 : Apple & Samsung airing cost prediction

### Introduction
This project was about designing models to predict how much Apple and Samsung need to assign their capital for commercial. To handle the highly skewed response variable(airing cost), I used log-transformation and since most of independent variables are catagorical variables, I gave dummy variables. Since dummy variables leads to sparse matrix, I figured out that there might be great chance that dimension reduction could improve the accuracy. Therefore, I developed prediciton models based on original dataset and dimensionally-reduced data. I designed regression models, XGboost model, random forest regression model, and stack model to predict cost and the random forest regression model has the best performance. Also to design classification models, I used binning technique to the response variable(airing cost) and developed random forest classification model and logistic regresiion model.


## 3. Project 3 : Classification of new cases of cancer

### Introduction
A goal of this project was developing a clustering model for new cases of cancer. The dataset showed how new cases of cancer could be classified by gene expression monitoring (via DNA microarray) and thereby provided a general approach for identifying new cancer classes and assigning tumors to known classes. The model classified patients with acute myeloid leukemia (AML) and acute lymphoblastic leukemia (ALL).


## 4. Project 4 : Robust asset portfolio

### Introduction
Many financial optimization problems involve future values of security prices, interest rates and exchange rates which are not known in advance but can only be forecast or estimated. This project is focusing on developing a robust optimization model for asset portfolio management via Python and CPLEX. You can find plots of efficient frontiers with different number of investment and different robust optimization models from this project.


