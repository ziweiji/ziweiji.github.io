---
title: "Modality-Transferable Emotion Embeddings for Low-Resource Multimodal Emotion Recognition"
collection: publications
permalink: /publication/2020-9-21-modality
excerpt: ''
date: 2020-9-21
venue: 'AACL 2020'
paperurl: 'https://arxiv.org/pdf/2009.09629.pdf'
authors: 'Wenliang Dai, Zihan Liu, Tiezheng Yu, Pascale Fung'
citation: 'Dai W, Liu Z, Yu T, et al. Modality-Transferable Emotion Embeddings for Low-Resource Multimodal Emotion Recognition[J]. arXiv preprint arXiv:2009.09629, 2020.'
paper: 'https://arxiv.org/pdf/2009.09629.pdf'
slide:
award:
code: https://github.com/wenliangdai/Modality-Transferable-MER
show_year: false
---
Despite the recent achievements made in the multi-modal emotion recognition task, two problems still exist and have not been well investigated: 1) the relationship between different emotion categories are not utilized, which leads to sub-optimal performance; and 2) current models fail to cope well with low-resource emotions, especially for unseen emotions. In this paper, we propose a modality-transferable model with emotion embeddings to tackle the aforementioned issues. We use pre-trained word embeddings to represent emotion categories for textual data. Then, two mapping functions are learned to transfer these embeddings into visual and acoustic spaces. For each modality, the model calculates the representation distance between the input sequence and target emotions and makes predictions based on the distances. By doing so, our model can directly adapt to the unseen emotions in any modality since we have their pre-trained embeddings and modality mapping functions. Experiments show that our model achieves state-of-the-art performance on most of the emotion categories. In addition, our model also outperforms existing baselines in the zero-shot and few-shot scenarios for unseen emotions.

[Paper](https://arxiv.org/pdf/2009.09629.pdf)
[code](https://github.com/wenliangdai/Modality-Transferable-MER)

Recommended citation: Dai W, Liu Z, Yu T, et al. Modality-Transferable Emotion Embeddings for Low-Resource Multimodal Emotion Recognition[J]. arXiv preprint arXiv:2009.09629, 2020.