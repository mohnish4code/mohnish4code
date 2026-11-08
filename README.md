<!-- ===================== ANIMATED HEADER ===================== -->
<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f2027,50:203a43,100:00BFFF&height=220&section=header&text=Mohnish%20Kumar%20Shandilya&fontSize=48&fontColor=ffffff&animation=fadeIn&fontAlignY=38&desc=Machine%20Learning%20Engineer%20%E2%80%A2%20Computer%20Vision%20%E2%80%A2%20MLOps&descAlignY=58&descSize=18" alt="header"/>
</p>

<p align="center">
  <a href="https://github.com/mohnish4code">
    <img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&weight=600&size=24&duration=3000&pause=800&color=00BFFF&center=true&vCenter=true&multiline=false&width=700&lines=Hi+%F0%9F%91%8B%2C+I'm+Mohnish;I+build+end-to-end+AI+systems+%F0%9F%A4%96;Data+%E2%86%92+Model+%E2%86%92+Deployed+API+%F0%9F%9A%80;Computer+Vision+%7C+Time-Series+%7C+Anomaly+Detection;Open+to+ML+%2F+AI+Engineering+roles+%E2%9C%A8" alt="Typing SVG"/>
  </a>
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/mohnish2004" title="Connect on LinkedIn"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white"/></a>
  <a href="mailto:mohnishshandilya.3000@gmail.com" title="Send me an email"><img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white"/></a>
  <a href="https://www.kaggle.com/mohnishshandilya" title="My Kaggle profile"><img src="https://img.shields.io/badge/Kaggle-20BEFF?style=for-the-badge&logo=kaggle&logoColor=white"/></a>
  <a href="https://mohnish4code.github.io" title="My portfolio"><img src="https://img.shields.io/badge/Portfolio-3DDC97?style=for-the-badge&logo=googlechrome&logoColor=black"/></a>
  <a href="https://mohnish4code.github.io/resume.pdf" title="View my resume"><img src="https://img.shields.io/badge/Resume-000000?style=for-the-badge&logo=readthedocs&logoColor=white"/></a>
  <img src="https://komarev.com/ghpvc/?username=mohnish4code&label=Profile%20Views&color=00BFFF&style=for-the-badge" alt="profile views"/>
</p>

---

<!-- ===================== ABOUT ME ===================== -->
<img align="right" width="320" src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Smilies/Robot.png" alt="robot"/>

## 🧑‍💻 About Me

```python
class Mohnish:
    def __init__(self):
        self.role       = "Machine Learning Engineer"
        self.education  = "B.Tech ECE @ MIT ADT University, Pune (2023 - 2027)"
        self.portfolio  = "https://mohnish4code.github.io"
        self.learning   = ["MLOps", "FastAPI", "Docker", "GitHub Actions", "MLflow"]
        self.interests  = ["Computer Vision", "Anomaly Detection", "Time-Series"]
        self.email      = "mohnishshandilya.3000@gmail.com"

    def motto(self):
        return "Data -> Model -> Honest evaluation -> Deployed API"
```

<br clear="right"/>

---

<!-- ===================== PROJECTS ===================== -->
## 🚀 Featured Projects

<details open>
<summary><b>🚗 Vehicle Number Plate Detection System</b> &nbsp;(click to expand / collapse)</summary>
<br/>

> Detects Indian number plates with a custom-trained **YOLOv8n** model, reads them with **PaddleOCR (PP-OCRv4)** and a plate-aware decoder that only accepts valid Indian formats (including BH-series and two-row plates), and logs confirmed plates to **Google Sheets**. Served by **FastAPI** with a mobile-friendly **React** app.

| 🎯 Detector mAP@50 | ✅ Exact reads (held-out) | 🔤 Character error rate | 🚫 Wrong reads auto-accepted |
|:---:|:---:|:---:|:---:|
| **0.994** | **85.3%** (up from 54.4%) | **6.3%** | **0 / 68** |

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![YOLOv8](https://img.shields.io/badge/YOLOv8-111F68?style=flat-square)
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=flat-square&logo=opencv&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)

👉 [**View repository**](https://github.com/mohnish4code/Vehicle-Detection-System)
</details>

<details>
<summary><b>📈 Multi-Module Stock Prediction System</b> &nbsp;(click to expand)</summary>
<br/>

> **AlphaStream** combines a forecasting model, **technical rules** and live **FinBERT news sentiment** in a decision engine that outputs one **BUY / HOLD / SELL** call for each of **10 NSE large caps**.

- 📊 Compared **ARIMA, XGBoost, LSTM and Transformer** models (with and without news); **XGBoost + FinBERT** won and is served
- 🔒 Leakage-free walk-forward backtest: 6 one-year folds, **1,512 trading days** per stock, 5-row embargo, against 4 baselines
- 🧾 Honest result: no model had a reliable next-day edge, and buy-and-hold beat them all. The README explains why
- 🧪 FastAPI + React + TypeScript, MLflow, Optuna, Docker, GitHub Actions and **79 pytest tests**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![XGBoost](https://img.shields.io/badge/XGBoost-1A6E9A?style=flat-square)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![MLflow](https://img.shields.io/badge/MLflow-0194E2?style=flat-square&logo=mlflow&logoColor=white)

👉 [**View repository**](https://github.com/mohnish4code/Multi-Module-Stock-Prediction)
</details>

<details>
<summary><b>🛡️ System Log Anomaly Detection</b> &nbsp;(click to expand)</summary>
<br/>

> AIOps pipeline that turns **15.9M raw log lines** (HDFS and BGL) into event templates with **Drain**, then flags abnormal sessions and time windows. Every alert links back to the log lines behind it.

| 🧩 Parsing accuracy (HDFS) | 🤖 Models benchmarked | ⚡ Streaming F1 (HDFS) | 🧪 Tests |
|:---:|:---:|:---:|:---:|
| **0.998** | **7** (rule → PCA → LSTM / Transformer) | **0.982** | **45** |

- 🔒 Chronological 60/20/20 splits; the deep models did not beat simpler methods on the test period, and the README explains why

![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)

👉 [**View repository**](https://github.com/mohnish4code/System-Log-Anomaly-Detection)
</details>

<details>
<summary><b>📂 More projects</b></summary>
<br/>

| Project | What it does | Stack |
|---|---|---|
| 💸 [Expense Tracker](https://github.com/mohnish4code/Expense-Tracker-Project) | Budgets plus ML insights: unusual-expense alerts, overspend prediction, budget recommendations | FastAPI, SQLAlchemy, Scikit-learn, Docker |
| 🎯 [ATS Resume Scanner](https://github.com/mohnish4code/Resume-Analyser) | Scores a resume against a job description with an explainable 0–100 breakdown | FastAPI, Scikit-learn, TF-IDF |
| 📄 [Question Paper Generator](https://github.com/mohnish4code/Question-Paper-Generator-using-RAG-and-LLM) | Generates exam papers from course material with RAG | FAISS, Sentence Transformers, Google Gemini, Streamlit |
| 💳 [Credit Risk Prediction](https://github.com/mohnish4code/Credit-Risk-Prediction-Project) | Predicts loan default risk | Scikit-learn, XGBoost, Streamlit |
| 📉 [Customer Churn Prediction](https://github.com/mohnish4code/Customer-Churn-Prediction) | Predicts which bank customers will leave | TensorFlow / Keras |
| 🎓 [Student Performance Prediction](https://github.com/mohnish4code/Student-Performance-Prediction) | Predicts maths scores with a modular training pipeline | Scikit-learn, CatBoost, XGBoost, Flask |

</details>

---

<!-- ===================== TECH STACK ===================== -->
## 🛠️ Tech Stack

<p align="center">
  <a href="https://skillicons.dev">
    <img src="https://skillicons.dev/icons?i=python,java,mysql,tensorflow,pytorch,sklearn,opencv,fastapi,docker,githubactions,git,github,vscode&perline=7" alt="skills"/>
  </a>
</p>

<details>
<summary><b>🔍 See the full skill breakdown</b></summary>
<br/>

| Area | Skills |
|---|---|
| 🧠 **Machine Learning** | Scikit-learn, XGBoost, Isolation Forest, Feature Engineering, Cross-Validation, Time-Series Forecasting, Anomaly Detection |
| 🔥 **Deep Learning** | TensorFlow / Keras, PyTorch, LSTM, Autoencoders, Transformers, YOLOv8, OpenCV |
| ✨ **Generative AI** | LLM APIs, RAG, Sentence Transformers, FAISS, Prompt Engineering |
| ⚙️ **MLOps & Backend** | FastAPI, REST APIs, Docker, GitHub Actions, MLflow, Pytest, Git |
| 📊 **Data** | Pandas, NumPy, SQL, EDA, Data Pipelines, Streamlit |
| 💻 **Core CS** | DSA, OOP, System Design, DBMS, Operating Systems, Computer Networks |

</details>

---

<!-- ===================== CERTIFICATIONS ===================== -->
<details>
<summary><h2>🏅 Certifications</h2></summary>

- 🎓 **Kaggle:** Intro to Machine Learning, Intermediate Machine Learning, Feature Engineering
- 🤖 **Generative AI Value Added Course**, iBase Technologies

</details>

---

<!-- ===================== QUOTE + FOOTER ===================== -->
<p align="center">
  <img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&size=16&duration=4000&pause=1500&color=8B949E&center=true&vCenter=true&width=700&lines=%22AI+is+not+about+replacing+humans%2C+it's+about+augmenting+human+potential.%22" alt="quote"/>
</p>

<p align="center">
  <b>⭐ If you like my work, drop a star on a repo, and feel free to reach out!</b>
</p>

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:00BFFF,50:203a43,100:0f2027&height=120&section=footer" alt="footer"/>
</p>
