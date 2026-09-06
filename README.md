# Student Performance - Data Analysis

## 📌 Description

This project explores the **Student Performance** dataset, which contains real academic, social, and demographic data of secondary school students from two courses — **Mathematics** and **Portuguese language**. The goal is to clean, analyze, and understand the factors (family background, study habits, lifestyle, etc.) that affect student grades.

## 📁 Main Files

| File / Folder | Description |
|----------------|--------------|
| `student-mat.csv` | Dataset — Math course student records |
| `student-por.csv` | Dataset — Portuguese course student records |
| `requirements.txt` | List of required Python packages |
| `student.txt` | Full attribute/column documentation for both datasets |
| `student-merge.R` | R script showing how the two datasets can be merged (382 common students) |
| `Math_Student.ipynb` | Jupyter Notebook — data cleaning & analysis for the **Math** dataset |
| `Portuguese_Student.ipynb` | Jupyter Notebook — data cleaning & analysis for the **Portuguese** dataset |
| `backup/` | Folder containing a backup copy of the original, unmodified dataset files |

## 📊 Dataset Source

The dataset is taken from the **UCI Machine Learning Repository**:
🔗 https://archive.ics.uci.edu/dataset/320/student+performance

## ✅ Work Done So Far

- **Dataset Cleaning** — Cleaned raw column values in both datasets (e.g., expanded short codes like `GT3`, `LE3`, `U`, `R`, `GP`, `MS` into readable full names, removed extra spaces, standardized text formatting).

## 🚀 Future Updates

- Build a **Machine Learning model** to **predict students' final grade (G3)** based on their academic, social, and family attributes.
- Add data visualizations to explore key patterns and correlations.

## ⚙️ Requirements

- **Python:** 3.14.6 (or a recent Python 3.x version)
- **Packages:** pandas, jupyter/notebook (see `requirements.txt`)

## 🛠️ Installation Guide

### 1. Check your Python version
```bash
python --version
```

### 2. (Recommended) Create a virtual environment
```bash
# Create
python -m venv venv

# Activate
venv\Scripts\activate      # Windows
source venv/bin/activate   # Mac/Linux
```

### 3. Install required packages
```bash
pip install -r requirements.txt
```

### Alternative: Using Anaconda
```bash
conda create -n student-analysis python=3.14
conda activate student-analysis
conda install pandas jupyter
```

## ▶️ How to Run

1. Open the project folder in **VS Code** or terminal.
2. Launch Jupyter Notebook:
   ```bash
   jupyter notebook
   ```
3. Open and run:
   - `Math_Student.ipynb` for the Math dataset
   - `Portuguese_Student.ipynb` for the Portuguese dataset

Or run directly in VS Code using the built-in Jupyter extension.