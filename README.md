🧠 Classification of Text Documents using Naive Bayes

📄 Project Overview
This project presents an automated **text classification** system using the **Naive Bayes algorithm**, one of the most efficient and interpretable probabilistic classifiers in Natural Language Processing (NLP).  
The model automatically categorizes textual documents (such as news articles, blogs, or reviews) into predefined categories with minimal human intervention.

---

🎯 Objectives
- Preprocess and clean raw text data  
- Extract features using **TF-IDF (Term Frequency–Inverse Document Frequency)**  
- Train and validate a **Naive Bayes** model  
- Evaluate model performance using standard classification metrics

---

🧩 Methodology

The workflow includes the following major steps:

1. Data Collection**  
   Dataset of 10,000 labeled text documents across 5 categories: *Sports, Technology, Business, Politics, and Health.*

2. Data Preprocessing**  
   - Tokenization  
   - Stopword Removal  
   - Lemmatization  
   - Lowercasing and punctuation removal  
   - TF-IDF Vectorization  

3. Model Training**  
   - Implemented both **Multinomial Naive Bayes** and **Bernoulli Naive Bayes** using `scikit-learn`.

4. Model Evaluation**  
   - Accuracy, Precision, Recall, F1-Score, and ROC-AUC metrics.



⚙️ Tools and Technologies

| Category | Tools / Libraries |
|-----------|------------------|
| Language | Python 3.10 |
| ML Framework | scikit-learn |
| NLP Toolkit | nltk |
| Data Handling | pandas, numpy |
| Visualization | matplotlib, seaborn |
| Platform | Google Colab |



 📊 Results

| Metric | Score |
|:--------|:------:|
| Accuracy | **88%** |
| Precision | 86% |
| Recall | 84% |
| F1-Score | 85% |
| ROC-AUC | 0.91 |

Key Takeaways:
- **Multinomial Naive Bayes** achieved the best performance.  
- Performs efficiently even on large, high-dimensional text data.  
- Ideal for applications like **spam detection**, **sentiment analysis**, and **topic categorization**.

 💡 Discussion

✅ Advantages
- Simple, fast, and computationally efficient.  
- Works well for high-dimensional text data.  
- Requires minimal training data.  
- Easy to implement and interpret.

⚠️ Limitations
- Assumes feature independence (not ideal for context-dependent text).  
- Struggles with phrases like *“not good”* where meaning depends on word combinations.  



🚀 Future Work
- Integrate **Word Embeddings** like *Word2Vec*, *GloVe*, or *BERT* to enhance contextual understanding.  
- Experiment with **hybrid models** combining Naive Bayes and **deep learning architectures (CNN/RNN)**.  
- Expand dataset and add multilingual text classification support.



## 📁 Repository Structure

