# AttWNN: A Binary Code Similarity Detection Method Based on Attention Walk Graph Neural Network

This repository is the official implementation of [AttWNN: A Binary Code Similarity Detection Method Based on Attention Walk Graph Neural Network]. 

## Requirements

Code is written in Python 3.6 and requires:
* PyTorch 1.5
* scikit-learn 0.21

## Installation
Describe how to install the project and all dependencies.
```bash
git clone https://github.com/tarofriendzy/AttWNN.git
cd AttWNN
```

## Quick Start
Step 1: Static analysis of binary code using ANGR

```
python binary_code/preprocessing.py
```

Step 2: Generate feature vector representation of nodes

```
python block_embedding/node_embedding_generation.py
```

Step 3: AttWNN training

```
python attwnn/main.py --dataset <dataset_name> 
```
