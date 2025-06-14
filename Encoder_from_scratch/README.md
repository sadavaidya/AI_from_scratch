# Transformer Encoder from Scratch using PyTorch

This project implements a basic Transformer Encoder architecture from scratch using PyTorch — without relying on high-level APIs like `nn.TransformerEncoder`.

### 🔍 What’s Implemented

- Token Embedding + Positional Encoding
- Multi-Head Self-Attention (no inbuilt modules)
- Position-wise Feedforward Network
- Layer Normalization and Residual Connections
- Classification Head on Top

### 🧪 Dataset

A small toy dataset (30+ samples) of fake news headlines across 4 classes:
- World
- Business
- Sports
- Technology

All preprocessing steps like tokenization, vocabulary creation, and padding are implemented manually.

### 🧠 Goal

To understand the inner workings of a Transformer Encoder by:
- Building each module from scratch
- Training on a small dataset
- Visualizing loss trends

> ⚠️ This repo is for educational purposes only — not intended for production or benchmark results.

### 📁 Structure

- `encoder_from_scratch.ipynb`: Jupyter Notebook with full implementation, training loop, and comments.
- `data_loader.py` *(optional)*: Manually tokenized and padded dataset loader.
- `README.md`: You're here.

### 🚀 Future Work

- Add attention heatmaps for interpretability
- Extend to full Transformer with decoder (or connect to existing GPT decoder)

---

## 🤝 Contributions

Pull requests are welcome for improvements, refactoring, or experiments with larger datasets.

