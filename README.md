# Language Translation with a Recurrent Neural Network
A Recurrent Neural Network (RNN) used to translate a given English text to French

This project was made by utilizing a dataset of TED talks translated from English to French for the purpose 
of creating a neural network that can generalize well enough to accurately predict the french translation given an 
english sentence above a 90% accuracy rate. The structure used to accomplish this was a Sequence to Sequence 
Recurrent neural network (RNN). Both Encoder and Decoder functions utilzed LSTM Cells for improved gradient flow 
through the cell state and Dropout functions with a keep prob rate of 70% to help the model better generalize.The 
network was created using Python 3, Tensorflow 1.0 and trained on a Floydhub GPU cloud instance.
