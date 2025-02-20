# 🍄 Streamlit Mushroom Classification App

## Overview

This is a **machine learning web app** that classifies mushrooms as **edible** or **poisonous** using multiple classifiers:

- **Support Vector Machine (SVM)**
- **Logistic Regression**
- **Random Forest**

The app is built using **Streamlit** and allows users to choose different models, adjust hyperparameters, and visualize metrics.

## 🛠️ Technologies Used

- Python 🐍
- Streamlit 🎨
- Pandas & NumPy 📊
- Scikit-learn 🤖
- Matplotlib 📈
- Docker 🐳 (for containerization)

## 📂 Dataset

- The model is trained on ``, which contains categorical features for classification.
- All features are label-encoded before training.

---

## 🚀 Installation & Setup

### 🔹 Running Locally (Virtual Environment)

```sh
git clone https://github.com/NandiniSrivastava/Docker.git
cd Docker
python -m venv .venv
source .venv/bin/activate  # Windows: .venv\Scripts\activate
pip install -r requirements.txt
streamlit run app.py
```

Now, open `` in your browser.

---

## 🐳 Running with Docker

### 🔹 Build and Run Docker Container

```sh
dockerwdhil ocker run -p 8501:8501 streamlit-mushroom-app
```

### 🔹 Using Docker Compose

```sh
docker-compose up --build
```

For **debug mode**, run:

```sh
docker-compose -f docker-compose.debug.yml up --build
```

---

## 📸 Screenshot (Optional)
![image](https://github.com/user-attachments/assets/34c9da3a-6ae3-4309-92b8-c3f2e52aa3a2)
![image](https://github.com/user-attachments/assets/c825efd1-7e19-42a8-a97d-6dec6781b553)
![image](https://github.com/user-attachments/assets/b89f768a-6ddd-4787-9e08-58afff1e645f)
![image](https://github.com/user-attachments/assets/53a2d13f-17a0-425f-882f-d0977bde9edb)




---

## 🔗 Links

- **Project Repository**: [GitHub Repo](https://github.com/NandiniSrivastava/Docker)

---

## 📜 License

This project is licensed under the **MIT License**.

---

