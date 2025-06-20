Dataset had 10000 tweets with positive and negative sentiments 
1) Pre-processing like stemming was done
2) Vocabulary of unique words was built . It was a dictionary {'unique_words':len(vocab)}
3) OOV was handled by giving index of UNK token (Unknown token)
4) Padding of each sequence was done subtracting length of maximum length tweet in training
5) Dense class was created with constructor for random intialization of weights and forward propagation method
6) Model was created using Tensor Flow(keras) . It was embedding -> Average Max Pooling -> Dense Layer
7) Loss Function was 'Binary Cross Entropy' . Adam optimizer was used for speeding back propagation




** Accuracy of model was 99%**
