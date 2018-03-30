# Multi-Lingual POS Tagger
POS Tagger is an implementation of Part-of-Speech tagging for an NLP task on the CoNLLU format datasets(English, Finnish) without depending on any language-specific knowledge.

# Initial Setup
To run the tagger model, you need Python 2.7

# Train a model
In this repo its been trained for English & Finnish CoNLLU on LEMMA & UPOS data, sample training data can be found from corpus folder.
Run train.py file and modify the --data_path value accordingly of your language choice. A single Feed-forward network achitecture with a single hidden layer is used here although Bidirectional LSTM and other architectures are more suitable for POS tagging.

# Tag the sentences
python testPOS.py and provide the sentence in a Finnish language. In order to use English model, *.pkl filenames needs to be modified 
