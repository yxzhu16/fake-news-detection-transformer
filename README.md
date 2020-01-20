# fake-news-detection-transformer
The encoder of the transformer network that produces a classification of each claim in PyTorch


## Transformer Network
Implemented a transformer encoder that produces a classification based on 
 - (i) the claim only, 
 - (ii) the claim and the claimant only (concatenated in one sequence)
 - (iii) the claim, the claimant and the 5 sentences from the related articles that are most similar to the claim (concatenated in one sequence). 

Used `nltk` and `TfidfVectorizer` to tokenize the sequence. 

Experimented with different number of layers in the architecture and to train for as many iterations as appropriate. 

## RNN
A RNN that produces the same classification job as the transformer network.

