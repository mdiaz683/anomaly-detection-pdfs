# Malicious PDF Detection Using Autoencoders Trained on Metadata

This project explores the use of deep autoencoders for detecting malicious PDF files through anomaly detection based on metadata. The goal is to build a lightweight and interpretable model capable of flagging suspicious documents without requiring labeled malicious data during training.

🔍 Project Overview
- Technique: Deep Autoencoder (TensorFlow/Keras)
- Approach: Trained exclusively on benign PDF metadata to learn normal patterns
- Goal: Detect anomalies via reconstruction error during testing
- Evaluation: Semi-supervised framework using CIC-Evasive-PDFMal2022 dataset

📁 Contents
- anomaly_detection.ipynb: Main notebook with data processing, model training, and evaluation.
- PDFMalware2022.parquet: Preprocessed metadata features from the CIC PDF malware dataset.
- DL_paper.pdf: Final research report describing the motivation, methodology, results, and future work.

📊 Dataset
Source: CIC-Evasive-PDFMal2022
https://www.unb.ca/cic/datasets/pdfmal-2022.html
https://www.kaggle.com/datasets/dhoogla/cic-evasive-pdfmal2022


🔐 Security Precautions
All analysis was conducted on structured metadata only. No raw PDF files were opened to ensure safety.
