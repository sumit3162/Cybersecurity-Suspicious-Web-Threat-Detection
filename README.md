# 🔐 Cybersecurity – Suspicious Web Threat Detection

Detect and analyze suspicious web traffic using Machine Learning models on AWS CloudWatch data.

![Project Preview]([https://www.google.com/url?sa=i&url=https%3A%2F%2Fcyberpedia.reasonlabs.com%2FEN%2Fsuspicious%2520website%2520detection.html&psig=AOvVaw1DkITXR_mp0FXJPJ-Qdnj2&ust=1744800645226000&source=images&cd=vfe&opi=89978449&ved=0CBQQjRxqFwoTCND-4oTv2YwDFQAAAAAdAAAAABAE](https://github.com/sumit3162/Cybersecurity-Suspicious-Web-Threat-Detection/blob/main/visuals.png?raw=true))

---

## 📌 Project Overview

This project uses real-world AWS CloudWatch logs to identify web-based attacks and suspicious activities. With powerful ML models like Isolation Forest and Neural Networks, we detect anomalies and classify traffic efficiently.

---

## 🧠 Tech Stack

- **Languages**: Python
- **Tools**: Jupyter Notebook, AWS CloudWatch
- **Libraries**: pandas, seaborn, matplotlib, scikit-learn, tensorflow, networkx
- **Platform**: VS Code, Google Colab / Local Jupyter

---

## 📁 Project Structure

```bash
cybersecurity-web-threat-detection/
│
├── data/                  # Data or dataset links
│   └── README.md
├── images/                # Visuals and banner
│   └── preview.png
├── notebooks/             # Jupyter notebooks
│   └── analysis.ipynb
├── src/                   # (Optional) Python scripts
│
├── requirements.txt       # List of dependencies
├── README.md              # This file
└── .gitignore

📊 Features
✅ Exploratory Data Analysis (EDA) of suspicious traffic

✅ Feature engineering for session duration, average packet size

✅ Anomaly detection using Isolation Forest

✅ Classification with Random Forest and Neural Network

✅ Visual analytics: heatmaps, time trends, stacked bar plots

✅ Graph-based IP interaction using NetworkX

📦 How to Run

git clone https://github.com/sumit3162/cybersecurity-web-threat-detection.git
cd cybersecurity-web-threat-detection
pip install -r requirements.txt
Then open notebooks/analysis.ipynb and run all cells.

📂 Dataset
The dataset was collected from AWS CloudWatch logs simulating real production web traffic.
🔗 Download Dataset

📈 Results
📌 100% accuracy with Neural Network and Random Forest (on sample data)

📌 Country-wise attack detection

📌 Bytes_in/out vs anomaly visualization

📌 Network graph of IP communication

🧩 Future Work
Integrate real-time log stream from AWS

Build live dashboard for threat monitoring

Deploy model for alert system

🙋‍♂️ Author
Sumit Shingane
🔗 GitHub: sumit3162

