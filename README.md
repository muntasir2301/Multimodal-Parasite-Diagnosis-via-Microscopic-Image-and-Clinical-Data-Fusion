## 📝 Project Overview

This repository contains the official implementation of an end-to-end **Multimodal AI Diagnostic System** for accurate and robust parasitic disease diagnosis[cite: 1]. By moving beyond traditional unimodal pipelines, this system systematically fuses biological visual context with patient clinical physiological indicators[cite: 1].

🔑 Key Features
* **Dual-Branch Architecture:** Employs a pre-trained **ResNet34** backbone for visual feature extraction from Giemsa-stained blood smear images, alongside a **Multi-Layer Perceptron (MLP)** branch to encode patient clinical metadata (body temperature, hemoglobin level, WBC count, and chills status)[cite: 1].
* **Late-Fusion Concatenation:** Merges visual and clinical representations into a unified 544-dimensional joint feature space to resolve morphologically ambiguous boundary cases[cite: 1].
* **Comprehensive 8-Class Diagnosis:** Performs multi-disease classification across *Babesia, Leishmania, Leukocyte, Plasmodium (Malaria), RBCs, Toxoplasma, Trichomonad,* and *Trypanosome*[cite: 1].
* **High Diagnostic Accuracy:** Trained on 34,298 clinically-annotated samples, achieving an impressive **macro-averaged F1-score of 0.97**[cite: 1].
* **Interactive Deployment:** Features a production-grade, real-time **Streamlit web application** designed for point-of-care clinician-in-the-loop diagnostic deployment[cite: 1].

🛠️ Tech Stack
* **Deep Learning:** PyTorch[cite: 1]
* **Computer Vision:** ResNet34 (Transfer Learning)[cite: 1]
* **Data Processing:** Scikit-Learn[cite: 1]
* **Deployment:** Streamlit, Ngrok[cite: 1]

📊 Dataset
You can download the full microscopic image dataset from [https://drive.google.com/drive/folders/1g7dHf08SUOp_TvNA0nCjsfzwKJBefKCD?usp=drive_link].
