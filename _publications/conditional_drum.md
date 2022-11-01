---
title: "Conditional Drums Generation using Compound Word Representations"
collection: publications
permalink: /publication/Conditional-Drum-Generation
excerpt: ''
date: 2022-02-05
venue: 'EvoMUSART'
paperurl: 'https://arxiv.org/pdf/2202.04464.pdf'
demo: ''
tutorial: ''
code: ''
---
The field of automatic music composition has seen great progress in recent years, specifically with the invention of transformer-based architectures. When using any deep learning model which considers music as a sequence of events with multiple complex dependencies, the selection of a proper data representation is crucial. In this paper, we tackle the task of conditional drums generation using a novel data encoding scheme inspired by the Compound Word representation, a tokenization process of sequential data. Therefore, we present a sequence-to-sequence architecture where a Bidirectional Long short-term memory (BiLSTM) Encoder receives information about the conditioning parameters (i.e., accompanying tracks and musical attributes), while a Transformer-based Decoder with relative global attention produces the generated drum sequences. We conducted experiments to thoroughly compare the effectiveness of our method to several baselines. Quantitative evaluation shows that our model is able to generate drums sequences that have similar statistical distributions and characteristics to the training corpus. These features include syncopation, compression ratio, and symmetry among others. We also verified, through a listening test, that generated drum sequences sound pleasant, natural and coherent while they "groove" with the given accompaniment.

[arxiv](https://arxiv.org/pdf/2202.04464.pdf)