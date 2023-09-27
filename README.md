# Sequence-to-Sequence Machine Translation with PyTorch

This repository contains an implementation of a Sequence-to-Sequence (Seq2Seq) machine translation model using PyTorch. The model is trained to translate English sentences into German sentences. The Seq2Seq architecture consists of an encoder and a decoder, both implemented as recurrent neural networks (RNNs).

## Overview

- **Data**: The model is trained and tested on a dataset of English and German sentence pairs. The dataset is preprocessed to remove unwanted characters, normalize text, and encode words as integers.

- **Encoder-Decoder Architecture**: The Seq2Seq model consists of an encoder that encodes the source sentence (English) and a decoder that generates the target sentence (German). The model is trained using teacher forcing, where the decoder is provided with the ground truth target sentence during training.

- **Training and Evaluation**: The model is trained using stochastic gradient descent (SGD) and cross-entropy loss. Training progress, including loss per epoch, is visualized. The model's translations are evaluated on a test set.