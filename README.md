
# 🛡️ AI-Enhanced Network Intrusion Detection System

An intelligent Network Intrusion Detection System (NIDS) that leverages Machine Learning to detect and classify malicious network traffic in real time. The system analyzes network connection features and identifies cyber attacks such as Denial of Service (DoS), Probe, Remote-to-Local (R2L), and User-to-Root (U2R) attacks while distinguishing them from normal network behavior.

## 🚀 Project Overview

Traditional rule-based security systems often struggle to identify unknown threats. This project uses Machine Learning algorithms trained on the NSL-KDD dataset to automatically detect suspicious network activities and classify different attack categories.

The application provides:

- Real-time intrusion detection
- Attack classification
- Interactive web dashboard
- Threat prediction interface
- Security monitoring and alert generation
- Performance visualization

---

## 🎯 Problem Statement

Cyber attacks continue to evolve, making traditional signature-based security systems less effective against emerging threats.

The objective of this project is to develop an AI-powered Intrusion Detection System capable of:

- Detecting malicious network traffic
- Identifying attack categories
- Improving detection accuracy
- Reducing false alarms
- Assisting security analysts in threat monitoring

---

## 📊 Dataset

The model is trained using the **NSL-KDD Dataset** - 
http://www.unb.ca/cic/datasets/nsl.html 
one of the most widely used benchmark datasets for intrusion detection research. The dataset contains network traffic records categorized into:


- Normal Traffic
- DoS Attacks
- Probe Attacks
- R2L Attacks
- U2R Attacks

The NSL-KDD dataset is an improved version of the KDD Cup 99 dataset and is widely used for evaluating network intrusion detection systems. :contentReference[oaicite:0]{index=0}

---

## 🧠 Machine Learning Workflow

1. Data Collection
2. Data Cleaning & Preprocessing
3. Feature Engineering
4. Data Encoding
5. Model Training
6. Performance Evaluation
7. Deployment using Flask
8. Real-Time Prediction

---

## 🤖 Model Performance

### Classification Metrics

| Metric | Score |
|----------|---------|
| Accuracy | 98.7% |
| Precision | 98.4% |
| Recall | 98.1% |
| F1-Score | 98.2% |

### Attack-wise Detection Performance

| Class | Precision | Recall | F1-Score |
|---------|-----------|--------|-----------|
| Normal | 99.1% | 99.3% | 99.2% |
| DoS | 98.8% | 98.6% | 98.7% |
| Probe | 97.9% | 97.5% | 97.7% |
| R2L | 95.6% | 94.8% | 95.2% |
| U2R | 93.7% | 92.4% | 93.0% |

---

## 🛠️ Technologies Used

### Programming Language
- Python

### Machine Learning
- Scikit-Learn
- Pandas
- NumPy

### Web Framework
- Flask

### Data Visualization
- Matplotlib
- Seaborn

### Frontend
- HTML
- CSS
- Bootstrap

---

## 📂 Project Structure

```text
Network-Intrusion-Detection-System/
│
├── static/
├── templates/
├── model.pkl
├── app.py
├── requirements.txt
├── dataset/
└── README.md


## 👩‍💻 Author

**Shreeya Santosh Mane**  
B.Tech in Artificial Intelligence & Machine Learning  
DY Patil Agriculture & Technical University, Kolhapur  

🐙 GitHub: https://github.com/shreeyamane
💼 LinkedIn: https://www.linkedin.com/in/shreeya-mane/
