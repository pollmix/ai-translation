## AI Translation

This model will predict the English translation of short German sentence.

```
INPUT: A German sentence
es tut mir sehr leid'

OUTPUT: English translation
i m sorry about that
```

### Tools Used

- Python
- PyTorch
- Matplotlib
- NumPy

### Concepts covered

- RNN (Recurrent Neural Network)
- Sequences and Vectors
- Encoding and Decoding

### Details

We started by exploring the different kinds of models that we can build using recurrent neural networks like vector-to-vector models, sequence-to-vector models, sequence-to-sequence, and vector-to-sequence models. We were most interested in was the sequence-to-sequence model for language translation. We noticed the basic components of a model, the encoder which generates a hidden state representation of the input sentence and the decoder that generates the sentence in the target language. We have seen the training process of this encoder-decoder model and how teacher forcing allows us to build models that converge faster.
