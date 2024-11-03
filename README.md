# Literary GPT

## Overview
This repository contains a custom pre-trained language model built from scratch, leveraging the Tiny Shakespeare dataset. With approximately 200,000 parameters, this model demonstrates key principles of NLP and attention-based architectures, inspired by the "Attention Is All You Need" paper.

## Features
- **Byte Pair Encoding (BPE)** for tokenization
- **Layer Normalization** to stabilize training
- **Multi-Head Attention** for contextual representation
- **Feed-Forward Layers** to refine output representations

## Architecture
The model is built upon foundational principles from the transformer architecture. Key layers include:
- **Embedding Layer** for token encoding
- **Multi-Head Self-Attention** for parallel attention mechanisms
- **Feed-Forward Networks** for nonlinear transformations
- **Positional Encoding** to add sequence order information

## Dataset
The Tiny Shakespeare dataset was used to train this model, providing a text corpus of classic literature with a focus on consistent and varied language patterns.

## Installation
To run this project, clone the repository and ensure you have Python 3.8+ and the following dependencies:
- **PyTorch** for deep learning framework
- **NumPy** for array operations

Install dependencies:
```bash
pip install torch numpy
