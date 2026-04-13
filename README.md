# ACE Inhibitor QSAR Modeling

## 🧠 Objective

Develop predictive QSAR models to estimate ACE inhibitor activity (pIC50) using molecular descriptors and machine learning.

---

## 📊 Dataset

* Source: ChEMBL
* ~2000 compounds
* Target: IC50 → converted to pIC50

---

## ⚙️ Workflow

* Data cleaning and SMILES standardization
* Descriptor calculation using RDKit
* Drug-likeness filtering (Lipinski, QED, PAINS)
* Feature scaling and preprocessing
* Model training:

  * Random Forest
  * Gradient Boosting
  * SVR
  * XGBoost
* Cross-validation and evaluation


---

## 📊 Outputs

* Feature importance → `/results/feature_importance.png`
* Model comparison → `/results/model_metrics_comparison.png`
* Cross-validation → `/results/cv_fold_performance.png`

---

## 🚀 How to Run

pip install -r requirements.txt
Open notebook from `/notebooks`

---

## 🛠 Tech Stack

Python, RDKit, Scikit-learn, XGBoost, Pandas, NumPy

---

## 👤 Author

Sahil Khan
