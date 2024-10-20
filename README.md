# Next-Word-Prediction-Using-LSTM

In this project where I delved deep into Natural Language Processing (NLP) to create a Next Word Prediction model using a Bidirectional Long Short-Term Memory (LSTM) network. This model showcases how neural networks can understand context, sequence, and structure in textual data to predict the next word with remarkable accuracy.

### Project Overview:
Using Arthur Conan Doyle's "The Adventure of the Dancing Men" book as the training corpus, I transformed the text into meaningful numerical sequences through tokenization, generating a vocabulary of unique words. I then applied Bidirectional LSTMs, which are particularly powerful as they capture dependencies in both forward and backward directions, enriching the model’s understanding of the language.

### Key steps included:
- Data Preprocessing: Tokenization and padding to ensure uniform input size for the network.
- Model Architecture: Built a robust sequential model with:
- Embedding Layer: Mapping each word to a dense vector space.
- Bidirectional LSTM Layer: Capturing context from both past and future tokens.
- Dense Output Layer: Predicting the next word based on the learned representations.
- Optimization and Training: Trained over 50 epochs, achieving an impressive accuracy of 94.4% by the final iteration.

### Key Technologies:
- TensorFlow & Keras: For building and training the neural network.
- Bidirectional LSTM: For enhanced sequence learning.
- NLP Techniques: Tokenization, padding, word embeddings to represent language structure effectively.
- 
### Model Capabilities: 
The model now generates contextually relevant text sequences, demonstrating its understanding of natural language and sequential dependencies. For instance, given the phrase "He took from his pocket the", the model predicts "various slips of the dancing men with which I cried."
