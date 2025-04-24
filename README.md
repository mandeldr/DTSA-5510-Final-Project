# JobCluster: Unsupervised Clustering of Job Descriptions

**Description:**  
This project explores the use of unsupervised machine learning to uncover hidden structure in job descriptions. Using TF-IDF vectorization and dimensionality reduction with TruncatedSVD, we apply KMeans and Agglomerative Clustering to group job postings by textual similarity.

Through hyperparameter tuning and evaluation with silhouette scores, we found that Agglomerative Clustering with average linkage and SVD-reduced features achieved the best performance, revealing more meaningful job clusters. The goal is to assist in organizing and analyzing large sets of job data for workforce planning, job categorization, or exploratory analysis.

---

## 📋 Prerequisites

Before setting up the project:

1. **Python** (>= 3.9.6): Install from [python.org](https://www.python.org/).
2. Install Jupyter Notebook:
   ```bash
   pip install notebook
   ```
3. Optional for PDF exports: **LaTeX** (e.g., TeX Live or MiKTeX).

---

## ⚙️ Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/mandeldr/DTSA-5510-Final-Project.git
   cd DTSA-5510-Final-Project
   ```

2. **Set up Python virtual environment:**
   ```bash
   python -m venv venv
   source venv/bin/activate   # On Windows: .venv\Scripts\activate
   ```

3. **Install Python dependencies:**
   ```bash
   pip install -r requirements.txt
   ```

---

## 🚀 Usage

- **To start Jupyter Notebook:**
  ```bash
  jupyter notebook
  ```

---

## 🧰 Tools and Libraries

### Python Packages:
- `pip`: Package manager for Python.
- `Jupyter`: Interactive notebooks for development and data exploration.
