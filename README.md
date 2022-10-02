# Sentiment--Classification

## 1. Deep Averaging Network
Papers Referenced:
<ul>
<li>Efficient Estimation of Word Representations in Vector Space 
<li>Distributed Representations of Words and Phrases and their Compositionality 
<li>GloVe: Global Vectors for Word Representation
<li>Enriching Word Vectors with Subword Information 
</ul>
The aim is to study the use of different pre-trained word embeddings
(word2vec/GloVe/fastText) for text representation and use them for text classification using pre-trained word embeddings. <br>

A simple way to represent a sentence is to tokenize, vectorize and average the word vector
representations of all the words in the sentence. This simple approach of
text representation is used for solving a text classification problem. <br>


Used t-SNE to plot the text representations obtained using the above-mentioned method.<br>

![plot](./images/1_tsne_before.png)<br>
![plot](./images/1_tsne_after.png)

 


