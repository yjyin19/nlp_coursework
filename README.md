## author-profiling

In this course project, we aimed to determine if the author of a Twitter feed is a fake news spreader (the shared task [Profiling Fake News Spreaders on Twitter](https://pan.webis.de/clef20/pan20-web/author-profiling.html)). The tweet feeds are in English and Spanish. The training data contains only 300 cases for each language. We tried combining convolutional neural networks and long short-term memory (LSTM) neural networks for the best performance. The neural network models were implemented with Keras on Tensorflow. We also tried out extracting different features and various classifiers, such as logistic regression, random forests, and support vector machines. The implementation of these models was from scikit-learn.

---

## generalization-with-SCAN

In this course project, we first tried to re-implement the models from the paper
Generalization without systematicity: On the compositional skills of sequence-to-sequence recurrent networks ([Lake and Baroni (2018)](https://arxiv.org/abs/1711.00350)) and reproduce the results. The models are LSTM networks and gated recurrent unit (GRU) networks with or without attention mechanisms. We then tried to improve the performance of the models. My approach was to use a transformer sequence-to-sequence model instead of RNNs, as the transformer models have reached state-of-art performance in many machine translation tasks. The transformer model was implemented with PyTorch.
