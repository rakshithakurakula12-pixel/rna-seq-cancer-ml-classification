# RNA-Seq Cancer vs Normal Classification (Machine Learning)

This project builds a **machine learning model** that classifies samples as **cancer** or **normal** using **RNA-seq gene expression data**.

It is designed to show my skills in:
- Bioinformatics (RNA-seq data handling)
- Machine Learning (classification models)
- Data analysis & visualization
- Reproducible research with notebooks and GitHub

---

## 🧬 Project Overview

### Goal
Use RNA-seq gene expression data to:
- Preprocess and normalize counts  
- Select important genes/features  
- Train ML models to predict **cancer vs normal**  
- Evaluate performance with accuracy, ROC curve, confusion matrix  
- Identify **top genes** contributing to the prediction

### Planned Steps
1. **Data Preparation**
   - Load RNA-seq expression matrix
   - Load labels (cancer/normal)
   - Split into train/test sets

2. **Feature Engineering**
   - Filter low-variance genes
   - Optionally select top genes using statistics or feature importance

3. **Model Training**
   - Train baseline models:
     - Logistic Regression
     - Random Forest
     - Support Vector Machine (SVM)
   - Compare performance

4. **Evaluation**
   - Accuracy, precision, recall, F1-score
   - ROC curve and AUC
   - Confusion matrix

5. **Biological Insight**
   - Look at top genes used by the model
   - Discuss possible biological relevance

---

## 📂 Repository Structure (Planned)

```text
data/                 # RNA-seq matrices and labels (cancer vs normal)
notebooks/            # Jupyter notebooks for each step
results/              # Plots, metrics, and reports
models/               # Saved trained models (optional)
README.md             # Project documentation
# RNA-Seq Cancer vs Normal Classification (Machine Learning)
