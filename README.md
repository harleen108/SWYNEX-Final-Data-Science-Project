# 🛡️ CyberShield AI
## End-to-End Network Traffic Analysis and Classification

**Final Data Science Project | SWYNEX Technologies**

CyberShield AI is an end-to-end data science project that analyzes network traffic and classifies it into **BENIGN** and **PortScan** categories using the CIC-IDS2017 dataset.

The project combines data preparation, exploratory data analysis, machine learning, and model evaluation into one documented workflow.

## 🎯 Project Objectives

- Prepare and inspect network traffic data.
- Explore traffic categories and relationships between numerical features.
- Train a Decision Tree classification model.
- Evaluate classification performance using standard metrics.
- Document findings, limitations, and future improvements.

## 🔄 End-to-End Workflow

1. **Data Preparation:** Inspect data quality, handle missing values and duplicates, and prepare numerical features.
2. **Exploratory Data Analysis:** Analyze traffic distribution and feature correlations using visualizations.
3. **Model Development:** Train a Decision Tree classifier using a stratified train-test split.
4. **Model Evaluation:** Assess accuracy, precision, recall, F1-score, and the confusion matrix.
5. **Conclusion:** Summarize findings, limitations, and potential future improvements.

## 📊 Dataset

- **Dataset:** CIC-IDS2017
- **Classification task:** BENIGN vs PortScan
- **Records in the final notebook dataset:** 140,439 labeled records
- **Original columns:** 79
- **Numeric features used for modeling:** 68

## 🧰 Technologies Used

- Python
- Pandas and NumPy
- Matplotlib and Seaborn
- Scikit-learn
- Google Colab

## 📈 Model Evaluation

The final notebook reports accuracy, weighted precision, weighted recall, and weighted F1-score. It also includes a confusion matrix to visualize correct and incorrect predictions.

The reported scores are specific to the current dataset and evaluation split. They should not be interpreted as proof of real-world cybersecurity effectiveness without independent validation and checks for potential data leakage.

## 🔍 Key Findings

- The dataset supports binary classification of BENIGN and PortScan traffic.
- Visualizations help communicate traffic composition and relationships between numeric features.
- A Decision Tree provides a baseline approach for network traffic classification.
- Independent testing is important to assess generalization to unseen traffic.

## ⚠️ Limitations

- The project focuses on two traffic categories.
- Results may vary on different datasets and network environments.
- Potential data leakage and redundant features should be investigated.
- The model is an educational experiment, not a production intrusion-prevention system.

## 🚀 Future Scope

- Validate performance on independent network traffic datasets.
- Investigate feature importance and potential data leakage.
- Compare additional classification algorithms.
- Explore more attack categories and a prototype monitoring dashboard.

## 📁 Repository Contents

- `SWYNEX-Final-Data-Science-Project.ipynb` — documented project notebook, visualizations, model evaluation, and conclusions.
- `README.md` — project overview, workflow, findings, and limitations.

## 👩‍💻 Project Information

**Project Name:** CyberShield AI  
**Internship Organization:** SWYNEX Technologies  
**Dataset Source:** CIC-IDS2017, Canadian Institute for Cybersecurity

---

*This project demonstrates an end-to-end data science workflow for network traffic classification and is intended for educational and experimental purposes.*
