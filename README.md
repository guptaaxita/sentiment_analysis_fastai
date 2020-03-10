# Sentiment Analysis using FastAI
ULMFiT classification model on US Airlines Sentiment twitter data

## High Level Summary
1) ULMFiT gradual unfreezing technique and FastAI library is used to fine tune pretrained-language model and build a classifier model to predict sentiments into three classes positive, negative and neutral.

2) WikiText 103 is the pretrained language model and AWD_LSTM model were used to train and fine-tune model with pretrained weights.

3) A language classifier model was developed on top of a pretrained model to predict a sentiment of a given tweet as positve, negative or neutral.
