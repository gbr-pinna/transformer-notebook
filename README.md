# Transformers From Scratch

A mathematical and implementation-focused introduction to the Transformer architecture introduced in *Attention Is All You Need* (Vaswani et al., 2017).

This repository contains:

* **transformer_tutorial.ipynb** — a Jupyter notebook that covers:
  * An intuitive explanation of self-attention and multi-head attention
  * Encoder-decoder Transformer architecture
  * Masking and positional encoding
  * Embeddings, loss functions, and regularisation
  * A PyTorch implementation of multi-head attention

  The goal of the notebook is to understand both the mathematical ideas and the tensor operations behind modern Transformer models.
  After studying the theory, we apply the Transformer to code a **small English–Italian translator** trained on a very small, synthetic corpus.
 

* **Transformer_notes.pdf** — handwritten notes summarising the key concepts from the original Transformer paper.

## Requirements

```bash
pip install torch jupyter
```

## Running the notebook

```bash
jupyter notebook
```

and open:

```text
transformer_tutorial.ipynb
```

## Reference

* Vaswani et al., *Attention Is All You Need* (2017)
* Géron, Aurélien. *Hands-On Machine Learning With Scikit-Learn and PyTorch: Concepts, Tools, and Techniques to Build Intelligent Systems*. O'Reilly Media, 2025.
