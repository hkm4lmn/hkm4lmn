# Hi, I'm Hakim 👋

**Hakim Al-Amin** · Computer Science undergraduate at **Universiti Teknologi MARA (UiTM)** · Selangor, Malaysia

I build data-driven web apps: machine learning models with clean APIs and usable frontends on top. Right now I'm finishing my final year project, a clinical prediction tool for spinal cord injury rehabilitation.

- 🎓 Bachelor of Computer Science (Hons.), UiTM · Diploma in Computer Science (2025), CGPA 3.50, Dean's List
- 🔬 Interested in applied ML, explainable AI and backend engineering
- 🛍️ Part-time retail work, which is where some of my side-project ideas come from
- 🇫🇷 Learning French alongside my CS degree

---

## ⭐ Featured project

### [SCI Return-to-Work Prediction](https://github.com/hkm4lmn/SCI-RTW-public) (Final Year Project)

A clinical decision-support web app that estimates whether a person with a spinal cord injury will return to work within ten years, and roughly when, and shows the factors behind each estimate.

- **Data:** U.S. NSCISC public dataset; trained on 16,841 patients and tested on a held-out 20%
- **Model:** two layers. Layer 1 predicts return to work (yes / no), Layer 2 the timing (Year 1, 5 or 10). Compares XGBoost, Random Forest and Logistic Regression
- **Results:** XGBoost reaches 0.744 ROC-AUC and 67.6% accuracy against a 53.9% majority baseline, and 88% accuracy on its high-confidence predictions. The README reports where it falls short, including uneven errors across education groups
- **Explainability:** per-patient factors from XGBoost's SHAP-style contributions, mapped from NSCISC codes to readable labels
- **App:** FastAPI backend with login and roles (doctor, therapist, patient, admin), saved patient history and printable reports; React frontend; tests in GitHub Actions
- **Stack:** Python · scikit-learn · XGBoost · FastAPI · React · Docker

[View the repository →](https://github.com/hkm4lmn/SCI-RTW-public)

---

## 🛠️ Side projects

| Project | What it does | Stack |
|---|---|---|
| **[Retail Stock & Sales Tracker](https://github.com/hkm4lmn/retail-stock-tracker)** | Inventory and sales API for a small store: audited stock movements, sales that can't oversell even under concurrent load, and daily reports | FastAPI · PostgreSQL · SQLAlchemy · pytest · Docker |
| **[MY Price Tracker](https://github.com/hkm4lmn/my-price-tracker)** | Public Telegram bot that tracks prices on Malaysian online shops and alerts on drops, target prices and restocks, with a price-history page per product. Postgres doubles as the job queue, alerts use a transactional outbox, and every fetch is protected against SSRF | FastAPI · PostgreSQL · Telegram Bot API · Docker · Caddy |

---

## 🧰 Tools I use

**Languages:** Python · JavaScript (Node.js) · SQL
**Backend:** FastAPI · Node.js · PostgreSQL
**ML & data:** scikit-learn · XGBoost · SHAP · pandas · WEKA
**Tools:** Git · GitHub · Docker

---

## 📫 Get in touch

Open to internships and graduate roles in software engineering, backend or ML.
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Hakim%20Al--Amin-0A66C2?logo=linkedin&logoColor=white)](https://www.linkedin.com/in/hakim-al-amin-262181320/)
