# 🧠 Machine Learning & AI Portfolio

### Ali Asghar
**Consulting ML Engineer | Full-Stack Developer**

I specialize in **Productionizing AI**. I don't just train models; I build the end-to-end infrastructure, APIs, and UIs that make them usable. My background allows me to bridge the gap between complex data science and scalable web engineering.

---

## 🏗️ End-to-End GenAI Systems (RAG & Agents)
*Full-stack applications demonstrating retrieval architectures and LLM integration.*

### 1. [Cognita - Hybrid RAG for Obsidian](https://github.com/iamAliAsgharKhan/Cognita)
A production-ready RAG system that syncs with local Obsidian vaults in real-time. It moves beyond simple vector search by implementing **Reciprocal Rank Fusion (RRF)** to combine semantic search with keyword (BM25) matching.

*   **Key Engineering:** implemented **Hybrid Search** (BM25 + ChromaDB), real-time file watching (Watchdog), and Recency Boost ranking.
*   **Stack:** ![FastAPI](https://img.shields.io/badge/-FastAPI-005571?logo=fastapi) ![Groq](https://img.shields.io/badge/-Groq_LLM-orange) ![ChromaDB](https://img.shields.io/badge/-ChromaDB-black) ![RRF](https://img.shields.io/badge/-RRF_Algorithm-blue)

### 2. [HyperQuery - NL2SQL Interface](https://github.com/iamAliAsgharKhan/HyperQuery)
An AI interface that allows non-technical users to query SQL databases using natural language. It uses Llama3-70B to generate SQL, but enforces **Pydantic validation** to ensure type safety and execution security.

*   **Key Engineering:** Dynamic schema awareness, safe read-only execution constraints, and responsive HTML table rendering.
*   **Stack:** ![Python](https://img.shields.io/badge/-Python-3776AB?logo=python&logoColor=white) ![SQLite](https://img.shields.io/badge/-SQLite-003B57?logo=sqlite) ![Llama3](https://img.shields.io/badge/-Llama3-blue)

---

## 🏥 Medical AI & Computer Vision
*Deep learning applications in healthcare and image analysis.*

### 3. [Medical VQA: Fine-Tuning BLIP](https://www.kaggle.com/code/ialiasghar/medical-vqa-fting-blip-for-radiology-pathology)
**Visual Question Answering (VQA)** for radiology and pathology. I fine-tuned the Salesforce **BLIP** transformer model to answer clinical questions based on medical imagery.

*   **Analysis:** Identified a critical "Generalization Gap" between Epoch 2 and 5, optimizing the training window to prevent memorization of patient-specific features.
*   **Result:** The model successfully identified specific pathologies (e.g., bone fractures) even when Ground Truth labels were generic.
*   **Stack:** ![PyTorch](https://img.shields.io/badge/-PyTorch-EE4C2C?logo=pytorch&logoColor=white) ![Transformers](https://img.shields.io/badge/-HuggingFace-yellow) ![BLIP](https://img.shields.io/badge/-BLIP_Model-black)

### 4. [Brain Tumor Detection](https://www.kaggle.com/code/ialiasghar/brain-tumor-detection-with-ml)
A classical ML approach to medical imaging. Instead of raw CNNs, I extracted statistical and textural features (Entropy, Skewness, Contrast) from MRI scans to train lightweight classifiers.

*   **Result:** Achieved **97% Accuracy** using Random Forest by removing redundant multicollinear features (like Energy/Homogeneity correlation).
*   **Stack:** ![Scikit-Learn](https://img.shields.io/badge/-Scikit_Learn-F7931E?logo=scikit-learn&logoColor=white) ![Pandas](https://img.shields.io/badge/-Pandas-150458?logo=pandas)

---

## 📊 Data Strategy & Critical Analysis
*Exploratory analysis and data auditing.*

### 5. [Smartphone Pricing: Trends & Clusters](https://www.kaggle.com/code/ialiasghar/smartphone-pricing-trends-clusters-insights)
A deep dive into the mobile market (2025 Dataset).
*   **Process:** Handled complex encoding issues (ISO-8859-1), cleaned mixed-type columns (RAM variants), and performed clustering analysis on price vs. specs.
*   **Insight:** Uncovered pricing tiers and spec-saturation points across different manufacturers.

### 6. [Plant Growth Optimization](https://www.kaggle.com/code/ialiasghar/plant-growth-milestone-prediction-using-environmen)
Analyzing environmental factors to predict growth milestones.
*   **Analysis:** Used **Cramer's V** to determine that `Fertilizer_Type` was the strongest predictor (0.34 correlation), refuting the assumption that Sunlight was the primary driver in this specific dataset.

### 7. [Heart Attack Risk - Dataset Audit](https://www.kaggle.com/code/ialiasghar/heart-attack-prediction-eda-modeling)
**Critical Negative Result:** Applied Random Forest, XGBoost, and Logistic Regression to a heart disease dataset.
*   **Outcome:** All models converged at ~52% accuracy (random chance).
*   **Conclusion:** Instead of forcing a result, I proved the dataset lacked genuine predictive signal and contained synthetic noise. *This project demonstrates the importance of data validation before modeling.*

---

## 📬 Contact
I am available for full-stack AI engineering roles and consulting.

- **Email**: aliasgharforwork@gmail.com
- **LinkedIn**: [linkedin.com/in/iamaliasgharkhan](https://www.linkedin.com/in/iamaliasgharkhan/)
- **GitHub**: [github.com/iamAliAsgharKhan](https://github.com/iamAliAsgharKhan)
