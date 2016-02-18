This is the code used for the experiments in the paper ["A Theoretically Grounded Application of Dropout in Recurrent Neural Networks"](http://mlg.eng.cam.ac.uk/yarin/publications.html#Gal2015Theoretically). The [sentiment analysis experiment](Sentiment_analysis_code/) relies on a [fork of keras](https://github.com/yaringal/keras/tree/BayesianRNN) which implements Bayesian LSTM, Bayesian GRU, embedding dropout, and MC dropout. The [language model experiment](LM_code/) extends [wojzaremba's lua code](https://github.com/wojzaremba/lstm).