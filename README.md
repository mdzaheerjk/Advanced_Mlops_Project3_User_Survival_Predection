# 🚢 User Survival Prediction (Titanic) – Advanced MLOps Project

![MLOps](https://img.shields.io/badge/MLOps-CI%2FCD-blue)
![Python](https://img.shields.io/badge/Python-3.10%2B-brightgreen)
![License](https://img.shields.io/badge/License-GPL--3.0-orange)
![Docker](https://img.shields.io/badge/Docker-Ready-blue)
![Airflow](https://img.shields.io/badge/Airflow-DAGs-informational)
![Prometheus](https://img.shields.io/badge/Prometheus-Monitoring-yellow)

An end-to-end MLOps project for predicting user survival on the Titanic dataset. This project demonstrates robust data pipelines, automated model training, CI/CD deployment with Docker and Airflow, monitoring with Prometheus, and a live web application for predictions. Built for reproducibility, scalability, and production-grade deployment.

> 📁 **Repository**: `Advanced_Mlops_Project3_User_Survival_Predection`

---

## 🚀 Project Highlights

- 🚂 **Data Pipeline**: Automated ingestion and processing of Titanic dataset
- 🤖 **Model Training**: Feature engineering and model pipeline for survival prediction
- ☁️ **MLOps Orchestration**: Airflow DAGs for workflow automation (ETL, training, serving)
- 📦 **Dockerized Microservices**: Complete stack with Docker & Docker Compose
- 📊 **Monitoring**: Prometheus integration for model and app monitoring
- 🌐 **Web App**: Interactive UI for survival predictions

---

## 🧠 Technical Stack

### 🛠️ Core Technologies
![Python](https://img.shields.io/badge/Python-3.10%2B-brightgreen)
![Docker](https://img.shields.io/badge/Docker-Ready-blue)
![Airflow](https://img.shields.io/badge/Airflow-DAGs-informational)
![Prometheus](https://img.shields.io/badge/Prometheus-Monitoring-yellow)
![Flask](https://img.shields.io/badge/Flask-WebApp-lightgrey)

### 📦 Libraries & Utilities
- Pandas, NumPy, Scikit-learn (ML, Data)
- Airflow (Workflow orchestration)
- Prometheus (Monitoring)
- YAML (Config management)
- HTML/CSS (Web UI)

---

## 🏗️ Project Structure

```bash
Advanced_Mlops_Project3_User_Survival_Predection/
├── Dataset/
│   └── TITANIC/
│       └── Titanic-Dataset.csv     # Raw Titanic dataset
├── Code/
│   ├── config/
│   │   ├── __init__.py
│   │   ├── database_config.py
│   │   └── paths_config.py
│   ├── dags/
│   │   ├── exampledag.py
│   │   └── extract_data_from_gcp.py
│   ├── notebook/
│   │   └── titanic.ipynb           # EDA & prototyping
│   ├── pipeline/
│   │   └── training_pipeline.py    # End-to-end ML pipeline
│   ├── src/
│   │   ├── __init__.py
│   │   ├── custom_exception.py
│   │   ├── data_ingestion.py
│   │   ├── data_processing.py
│   │   ├── feature_store.py
│   │   ├── logger.py
│   │   └── model_training.py
│   ├── static/
│   │   └── style.css               # Web app styling
│   ├── templates/
│   │   └── index.html              # Web app template
│   ├── Dockerfile                  # Docker image build
│   ├── docker-compose.yml          # Multi-service orchestration
│   ├── prometheus.yml              # Monitoring config
│   ├── application.py              # Flask app entry
│   ├── requirements.txt
│   ├── setup.py
│   ├── LICENSE
│   ├── PDF and NOTES.pdf
│   └── README.md
├── STEPS NOTEPAD FILE              # Deployment & workflow notes
├── .gitignore
```

---

## ⚡ Installation & Usage

### 1. Clone the repository
```bash
git clone https://github.com/mdzaheerjk/Advanced_Mlops_Project3_User_Survival_Predection.git
cd Advanced_Mlops_Project3_User_Survival_Predection/Code
```

### 2. Set up a virtual environment
```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

### 3. Install dependencies
```bash
pip install -r requirements.txt
```

### 4. Run the ML pipeline
```bash
python pipeline/training_pipeline.py
```

### 5. Run the web application
```bash
python application.py
```
Access the app at [http://127.0.0.1:5000](http://127.0.0.1:5000)

---

## 🐳 Docker, Airflow & Monitoring

- **Docker:**  
  Use the provided `Dockerfile` and `docker-compose.yml` for local or cloud containerized deployment.

- **Airflow:**  
  DAG scripts in `dags/` automate data ingestion, preprocessing, and model training pipelines.

- **Prometheus:**  
  Monitoring is enabled by the `prometheus.yml` configuration.

---

## 📊 Example Use Cases

- **Survival Prediction**: Predict whether a Titanic passenger would survive based on input features
- **Web App Demo**: Interactive UI for submitting passenger details and viewing predictions
- **MLOps Pipeline Demo**: End-to-end automation from data to deployment

---

## ✍️ Author

**Mohammed Zaheeruddin**  
🎓 First-Year B.Tech Student | AI/ML & GenAI Enthusiast  
🏫 Shetty Institute of Technology, Gulbarga  
📧 info.zaheerjk@gmail.com

---

## 📜 License

This project is licensed under the **GPL-3.0 License** – see the LICENSE file for details.

---

#### Key Features:
1. Fully automated, modular MLOps pipeline for survival prediction
2. Dockerized microservices and orchestration with Docker Compose
3. Airflow DAGs for workflow automation
4. Real-time monitoring with Prometheus
5. User-friendly web interface for live model inference
6. Ready for education, research, or production adaptation
