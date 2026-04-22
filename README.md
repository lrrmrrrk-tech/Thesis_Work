# 🧬 Intelligent Deep Learning Framework for Liver Cirrhosis Detection & Prognosis

## 🚀 Overview

This project presents an advanced machine learning and deep learning framework for the **early detection and prognostic assessment of liver cirrhosis** in high-risk patients.

Using longitudinal clinical data from the **Mayo Clinic Primary Biliary Cirrhosis (PBC) dataset**, the study combines interpretable deep learning with powerful ensemble techniques to deliver robust and clinically meaningful predictions.

---

## 🎯 Objectives

* Detect liver cirrhosis at early stages using clinical biomarkers
* Predict patient prognosis based on structured medical data
* Balance predictive performance with model interpretability
* Address class imbalance and clinical data challenges
* Provide a scalable framework for healthcare AI applications

---

## 🗂️ Dataset

**Mayo Clinic Primary Biliary Cirrhosis (PBC) Dataset**

* Source: Fleming & Harrington (1991)
* ~418 patients
* 7,905 longitudinal observations (~19 records per patient)


---

## 🧠 Methodology

### 🔹 1. Data Processing

* Cleaning and standardization of clinical variables
* Handling missing values and inconsistencies
* Feature preparation for modelling

### 🔹 2. Handling Class Imbalance

* Advanced resampling techniques applied to improve minority class prediction
* Ensures fair and reliable model performance across outcomes

### 🔹 3. Model Architecture

#### 🧩 Deep Learning Model

* **TabNet-Inspired Attention MLP**

  * Learns feature importance dynamically
  * Enhances interpretability in clinical decision-making

#### 🌳 Machine Learning Models

* **Histogram Gradient Boosting Trees (HGBT)**
* **DART Gradient Boosting (Dropouts meet Multiple Additive Regression Trees)**

#### 🔗 Ensemble Learning

* **Deep Stacking Ensemble**

  * Combines predictions from multiple base learners
* **Calibrated Soft Voting Ensemble**

  * Improves probability estimation and reliability

---

## 📊 Evaluation Metrics

Model performance is assessed using:

* F1 Score
* Precision
* Recall
* Calibration performance (for probabilistic outputs)

---

## 📈 Key Contributions

* Hybrid framework combining deep learning and ensemble methods
* Improved predictive performance on imbalanced clinical data
* Incorporation of **attention mechanisms for interpretability**
* Clinically relevant approach to prognosis modelling

---

## ⚙️ Tech Stack

* Python 🐍
* Scikit-learn
* PyTorch / Deep Learning Frameworks
* Imbalanced-learn
* Pandas & NumPy

---

---

## ▶️ How to Run

1. Clone the repository:

```bash
git clone https://github.com/your-username/your-repo.git
```

2. Install dependencies:

```bash
pip install -r requirements.txt
```

3. Launch the notebook:

```bash
jupyter notebook
```

---

## 🔮 Future Work

* Temporal modelling using LSTM or Transformer architectures
* Integration of survival analysis techniques
* Deployment as a clinical decision support tool
* External validation on independent healthcare datasets

---

## ⚠️ Disclaimer

This project is for research and educational purposes only and is **not intended for direct clinical use** without proper validation.

---

## 👤 Author

**Oluwasegun Joseph Olanrewaju-Ajiboye**
Data Scientist  | Machine Learning | Healthcare AI

---

## 🌟 Acknowledgements

* Mayo Clinic for dataset access
* Research community in medical AI and predictive modelling

---

⭐ If you find this work valuable, consider starring the repository!
