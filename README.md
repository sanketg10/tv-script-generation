# tv-script-generation
Using LSTMs in RNN to generate dialogue

This project first converts training data words into lookup dictionaries. Both word to integer and integer to words.
Then it takes training data and builds word embeddings for each one using RNN and LSTMs. Lot of the functionality is wrapped
in TensorFlow. 
The RNNs are then connected by a fully connected layer which then goes into a softmax function to give you word probabilities. 
Just take the word probabilities and choose the max one to predict the next word.


