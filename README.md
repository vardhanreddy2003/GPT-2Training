
---

## 🧠 Model Architecture

GPT-2 architecture consists of the following core components:

1. **Token Embeddings**
2. **Positional Encodings**
3. **N Transformer Blocks**, each with:
   - Masked Multi-Head Self-Attention  
   - Feedforward MLP  
   - Layer Normalization & Residual Connections  
4. **Linear Output Layer** – Predicts next token probabilities

---

## ⚙️ Training Details

- **Framework:** PyTorch  
- **Optimizer:** AdamW  
- **Loss Function:** CrossEntropyLoss  
- **Goal:** Next-word prediction (autoregressive training)

Due to **limited GPU resources**, full-scale model training wasn’t performed,  
but the training loop (`model_train`) is implemented and ready to run on suitable hardware.

---

## 📚 What I Learned

Through this project, I gained a strong understanding of:

- How **attention mechanisms** and **masking** work in transformers  
- The role of **positional encodings** in sequence modeling  
- How **transformer blocks** interact through residual connections  
- The process of **language modeling and token prediction**  
- The core structure that powers large language models like GPT-2  

This experience significantly strengthened my intuition about **deep learning architectures** and **sequence modeling**.

---

## 💡 Future Plans

- Train the model on a larger text corpus once resources are available  
- Implement sampling strategies like temperature and top-k sampling  
- Integrate checkpoint saving/loading  
- Add performance metrics and text generation examples  

---

## 🤝 Acknowledgment

Special thanks to **[Vizuraa YouTube Channel](https://www.youtube.com/@vizuarachannel)** for providing clear and insightful explanations of GPT-2 architecture and attention mechanisms.  
Their educational series helped me visualize and understand the theory while implementing it all from scratch.

---

## 📬 Connect with Me

👤 **Vardhan Reddy**  
🔗 [LinkedIn](https://www.linkedin.com/in/vardhanreddy2003)  
💻 [GitHub](https://github.com/vardhanreddy2003)

---

## 📝 License

This project is licensed under the **MIT License**.  
You’re free to use and modify the code with proper credit.

---

### 🌟 “I built GPT-2 from the ground up — one transformer block at a time, powered by curiosity.”
