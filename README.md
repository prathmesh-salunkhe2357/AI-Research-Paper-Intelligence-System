
# 🔍 AI Research Paper Search Engine

An AI-powered Research Paper Search Engine that performs **semantic search** over research papers using Sentence Transformers and FAISS. It also provides **automatic summarization**, **keyword extraction**, **Named Entity Recognition (NER)**, and **topic clustering** to help users quickly understand relevant research papers.

> Developed as part of the **CBSOT Internship Project**.

---

## 🚀 Features

- 🔎 Semantic Search using Sentence Transformers
- 📑 Automatic Research Paper Summarization
- 🔑 Keyword Extraction using KeyBERT
- 🏷️ Named Entity Recognition (NER)
- 📂 Topic Clustering
- ⚡ Fast Similarity Search using FAISS
- 🌐 Interactive Web Interface using Gradio

---

## 🛠️ Tech Stack

- Python
- Google Colab
- Sentence Transformers
- FAISS
- Transformers (BART)
- KeyBERT
- spaCy
- Scikit-learn
- Gradio
- Pandas
- NumPy

---

## 📁 Project Structure

```
AI-Research-Paper-Search-Engine/
│
├── AI_Research_Paper_Search_Engine.ipynb
├── paper_embeddings.npy
├── paper_faiss.index
├── sample_papers.csv
├── requirements.txt
├── README.md
├── LICENSE
├── .gitignore
│
└── images/
    ├── gradio.png
    ├── search_results.png
    ├── summary.png
    ├── keywords.png
    └── topic_cluster.png
```

---

## ⚙️ Workflow

1. Load research paper dataset
2. Generate sentence embeddings
3. Store embeddings using FAISS
4. Accept user search query
5. Perform semantic similarity search
6. Retrieve Top-K relevant papers
7. Generate summaries
8. Extract keywords
9. Perform Named Entity Recognition
10. Predict paper topic
11. Display results using Gradio

---

## 📷 Project Screenshots

### Home Interface

(Add Screenshot Here)

---

### Search Results

(Add Screenshot Here)

---

### Summary, Keywords & Entities

(Add Screenshot Here)

---

## 📊 Example Query

```
deep learning for medical image analysis
```

### Output

- Similarity Score
- Research Paper Title
- Generated Summary
- Extracted Keywords
- Named Entities
- Topic

---

## 📦 Installation

Clone the repository

```bash
git clone https://github.com/yourusername/AI-Research-Paper-Search-Engine.git
```

Move into the project folder

```bash
cd AI-Research-Paper-Search-Engine
```

Install dependencies

```bash
pip install -r requirements.txt
```

Run the notebook

```bash
jupyter notebook
```

or open in

- Google Colab

---

## 📚 Libraries Used

- sentence-transformers
- transformers
- faiss-cpu
- keybert
- spacy
- gradio
- pandas
- numpy
- scikit-learn

---

## 🎯 Future Improvements

- PDF Upload Support
- Research Paper Recommendation System
- Citation Graph Analysis
- Multi-language Support
- Advanced NER Models
- Research Trend Visualization

---

## 👨‍💻 Author

**Prathmesh Salunkhe**

CBSOT Internship Project

---

## 🙏 Acknowledgements

Special thanks to **CBSOT** and **Aryesh Rai Sir** for their guidance and mentorship throughout this internship project.

---

## ⭐ If you like this project

Please consider giving it a ⭐ on GitHub.
