# Implementation of 'DropEdge: Towards Deep Graph Convolutional Networks on Node Classification' Article

This repository contains the implementation of the "DropEdge: Towards Deep Graph Convolutional Networks on Node Classification" article.

## Overview

The article proposes a method called DropEdge, which aims to address over-smoothing in deep graph convolutional networks (GCNs) for node classification tasks.

### Part A)
- **General Idea**: The article introduces DropEdge, a method that randomly drops edges from the graph during training to prevent over-smoothing in deep GCNs.
- **Innovation**: DropEdge innovatively tackles the issue of over-smoothing by selectively removing edges during training, thereby forcing the model to focus on important graph connections.
- **Differences and Similarities with Dropout**: The idea of DropEdge is analogous to Dropout in deep learning, where connections between neurons are randomly dropped during training to prevent overfitting. However, in DropEdge, edges in the graph are dropped instead of neuron connections, and it specifically addresses over-smoothing in graph neural networks.

### Part B)
- **Implementation**: DropEdge method is implemented as described in the article, considering a two-layer GCN as the basic model.

### Part C)
- **Training and Evaluation**: Train and evaluate the implemented model on the CoraFull and CiteSeer datasets.

### Part D)
- **Effectiveness of DropEdge**: Seting the number of GCN layers along with DropEdge to eight layers and training the model on the CiteSeer dataset and evaluateing it to determine if DropEdge is still effective at preventing over-smoothing.

### Part E)
- **Skip-Connection Method**: Skip-Connection idea is applied to an eight-layer GCN to prevent over-smoothing.

## Related Paper

- "DropEdge: Towards Deep Graph Convolutional Networks on Node Classification" [Paper Link](https://arxiv.org/abs/1907.10903)

## Contributions

Contributions are welcome. Feel free to submit a pull request for any improvements or additional functionality.
