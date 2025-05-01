# NLP-Project-2025
# Sentence Embeddings & Semantic Search with FAISS

This project demonstrates how to use sentence embeddings to compute similarity between sentences and perform fast semantic search using **FAISS**.

## 🔧 What This Project Does

1. **Embeds sentences** using a pre-trained transformer model (`all-MiniLM-L6-v2`).
2. **Visualizes** the embeddings in 2D using **PCA**.
3. **Computes similarity** between sentences using **cosine similarity**.
4. **Performs semantic search** using **FAISS**, a high-performance similarity search library.

---

## 🧠 Technologies Used

- [Sentence Transformers](https://www.sbert.net/)
- [FAISS (Facebook AI Similarity Search)](https://github.com/facebookresearch/faiss)
- `scikit-learn` for PCA and similarity metrics
- `matplotlib` for visualization
- `NumPy` for numerical operations

---

## 📝 Sample Texts Used

```python
texts = [
    "Paris is known for its art, fashion, and the Eiffel Tower.",
    "Python is widely used in data analysis and machine learning.",
    "I enjoy cooking traditional Indian dishes on weekends.",
    "The German Bundesliga features some of the best football clubs.",
    "Cats are playful and love to sleep in warm places.",
    "Many tourists visit Rome to explore its ancient architecture."
]
