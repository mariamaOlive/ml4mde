# Recommendation System for Stack Overflow Questions  
### Author: Mariama Oliveira
#### Project part of the Course: Machine Learning for Model-Driven Engineering at UNIVAQ

## 📌 Project Overview  
This project explores **recommendation systems** to suggest users who are likely to answer new questions posted on **Stack Overflow**. The study focuses on **classical recommendation techniques**, such as **collaborative filtering** and **content-based filtering**, along with **transformer-based embeddings** for enhanced recommendations.

## 🔹 Motivation  
Stack Overflow hosts **millions of questions** and answers. However, **many questions remain unanswered** due to the difficulty in reaching the right experts. This project aims to **recommend potential answerers** for new questions based on historical interactions and text-based features.

## 🔹 Contributions  
1️⃣ **Dataset Extraction:** Collected real data from **Stack Exchange Data Explorer** (2019 dataset).  
2️⃣ **Implementation of Recommendation Approaches:** Tested **collaborative filtering**, **content-based filtering**, and **transformer-based embeddings**.  
3️⃣ **Use of Transformer Models:** Applied **sentence embeddings** for semantic-based recommendations.  
4️⃣ **Comparison of Different Approaches:** Analyzed performance differences across methods.  


## 📌 Dataset  
The dataset was extracted from **Stack Exchange Data Explorer** and includes:  
- **878,718 questions** from Stack Overflow.  
- **1,105,677 answers** linked to these questions.  
- **Features extracted:** Question ID, User ID, Title, Tags, Creation Date, and Vote Counts.  
  
📂 **Dataset:** [Google Drive Link](https://tinyurl.com/datasetSO)  


## 📌 Tools & Technologies  
✅ **Python (Pandas, NumPy, Scikit-Learn, PyTorch, Transformers)**  
✅ **Sentence-Transformers (all-MiniLM-L6-v2 for embeddings)**  
✅ **Matplotlib & Seaborn for data visualization**  
✅ **SQL (Stack Exchange Data Explorer for dataset extraction)**  

