# Attention Mechanism Demo

## Overview
This project demonstrates the **scaled dot-product attention** mechanism, the core of Transformer architectures.  
It was created as part of real understanding on core concepts of Attention Mechanism.

## Steps Covered
1. Generate random Query (Q), Key (K), and Value (V) matrices.
2. Compute attention scores using dot products.
3. Apply scaling and softmax to get attention weights.
4. Multiply weights with Values to get the final output.

## Code
The implementation is in [`notebooks/attention_demo.ipynb`](./notebooks/attention_demo.ipynb).

## Concepts Learned
- Attention allows models to focus on relevant parts of the input sequence.
- Q, K, V represent different projections of the input embeddings.
- Softmax turns raw scores into probability weights.

## Next Steps
- Extend to multi-head attention.
- Visualize attention weights with heatmaps.
- Apply attention to a toy NLP example.