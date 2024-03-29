# Transformer
The dominant sequence transduction models are based on complex recurrent or convolutional neural networks that include an encoder and a decoder. The best performing models also connect the encoder and decoder through an attention mechanism. We propose a new simple network architecture, the Transformer, based solely on attention mechanisms, dispensing with recurrence and convolutions entirely. Experiments on two machine translation tasks show these models to be superior in quality while being more parallelizable and requiring significantly less time to train. The model achieves 28.4 BLEU on the WMT 2014 Englishto-German translation task, improving over the existing best results, including ensembles, by over 2 BLEU. On the WMT 2014 English-to-French translation task, our model establishes a new single-model state-of-the-art BLEU score of 41.8, a small fraction of the training costs of the best models from the literature. They show that the Transformer generalizes well to other tasks by applying it successfully to English constituency parsing both with large and limited training data.

[Attention Is All You Need (NIPS 2017)](https://papers.nips.cc/paper/7181-attention-is-all-you-need.pdf "Transformer")


![image](https://github.com/jyy0553/Transformer/blob/master/IMG/Multi_head.jpg)
![image](https://github.com/jyy0553/Transformer/blob/master/IMG/Transformer_architecture.jpg)
