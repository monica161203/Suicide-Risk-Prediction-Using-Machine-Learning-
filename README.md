#  Suicide Risk Prediction using Machine Learning & Explainable AI

##  Project Overview

Suicide is a pressing global mental health issue, claiming over **700,000 lives each year** and leaving a profound impact on families and communities. Predicting suicide risk is complex due to its multifaceted nature, encompassing behavioral, psychological, and social factors. Traditional diagnostic approaches, while helpful, are often subjective and inconsistent.

This project introduces a **transparent, data-driven framework** that leverages **machine learning (ML)** and **explainable artificial intelligence (XAI)** to assess suicide risk with improved **accuracy, consistency, and interpretability**.


##  Dataset Description

The study utilizes a **well-balanced dataset of 1,000 instances** with **22 features**, including:

- **Demographic Variables**: Age, Gender, Religion, Occupation  
- **Behavioral Indicators**: Sleep Problems, Anger, Humiliation  
- **Psychological Metrics**: Depression, Suicidal Ideation, Sadness  
- **Medical History**: Psychiatric Disorders, Previous Suicide Attempts


##  Preprocessing Steps

To prepare the data for modeling, the following preprocessing techniques were applied:

- Outlier treatment  
- Missing value imputation  
- Label encoding  
- Dimensionality reduction using **Principal Component Analysis (PCA)**


##  Models Implemented

Four supervised machine learning algorithms were used:

1. **Naive Bayes** – Lightweight and interpretable baseline  
2. **K-Nearest Neighbors (KNN)** – High-performing, proximity-based model  
3. **Artificial Neural Network (ANN)** – Deep learning model for complex relationships  
4. **Extreme Gradient Boosting (XGBoost)** – Ensemble method with highest accuracy  

 **Best Result:**  
- **XGBoost achieved 98% accuracy**, outperforming others on precision, recall, and F1-score  
- **ANN and KNN** also achieved strong performance (~97%)  
- **Naive Bayes** served as a benchmark with fast interpretability



##  Model Explainability (XAI)

To address the black-box nature of complex models, we used **SHAP (SHapley Additive exPlanations)** with XGBoost to interpret predictions.

 **Top Risk Factors Identified**:
- Social Isolation  
- Suicidal Thoughts  
- Sadness  
- Anger  
- Sleep Problems  

These insights enable **clinicians and decision-makers** to understand the model's reasoning and support ethical AI use.



##  Graphical User Interface (GUI)

A **user-friendly GUI** was developed to simulate real-time mental health screening:

- Users answer structured behavioral and psychological questions  
- Responses are encoded and passed to the trained XGBoost model  
- The model returns:
  - A classification result (At-Risk / Not At-Risk)  
  - Feature-level explanations using SHAP

This empowers mental health professionals to make **informed, transparent decisions** during assessments.



##  Key Contributions

- Developed a **high-accuracy suicide risk classifier** using ML  
- Applied **explainable AI (SHAP)** for transparent insights  
- Designed a **real-time GUI** for user interaction and screening  
- Demonstrated the value of ethical AI in **mental health diagnostics**



##  Tech Stack

- Python  
- Scikit-learn  
- XGBoost  
- Keras (for ANN)  
- SHAP  
- Tkinter (GUI)  
- Pandas, NumPy, Matplotlib



##  Future Work

- Incorporate real-world clinical data  
- Collaborate with mental health professionals for validation  
- Extend the system with multilingual support and voice-based input



##  Ethical Consideration

This tool is designed to **support**, not replace, clinical judgment. The use of such models should always include human oversight and comply with ethical standards.



##  License & Acknowledgments

This project is developed for academic and research purposes. Please consult a mental health professional for real-world concerns.

Grateful for the guidance, mentorship, and support provided during the development of this project.

---

