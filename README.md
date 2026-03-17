## Contents

#### Pure NumPy implementation
No deep learning libraries. All operations (dot products, gradients, updates) are implemented manually.

#### Skip‑Gram with Negative Sampling
Implements the loss function from the original Word2Vec paper.
- Custom training pipeline
- Tokenization
- Vocabulary construction
- Subsampling of frequent words
- Skip‑gram pair generation
- Negative sampling distribution
- SGD training loop
  
#### Configurable hyperparameters
Embedding size, window size, learning rate, negative samples, epochs.

#### Similarity queries
Retrieve nearest neighbors using cosine similarity.


## Dataset
The model is trained on a subset of the NLTK Gutenberg corpus, which provides clean, public‑domain English text.
To keep training lightweight, only selected books are used (e.g., Alice in Wonderland, Macbeth, Emma).

## Requirments
- numpy
  
- nltk
  Gutenberg corpus
  Tokenization
  Downloading datasets
  
- matplotlib (optional)
 plotting the negative sampling distribution
 optional loss curves
