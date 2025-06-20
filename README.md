# 💰 Salary Prediction Model
### _Revolutionizing Fair Compensation with AI-Powered Insights_ 🚀
[![Python](https://img.shields.io/badge/python-3670A0?logo=python&logoColor=ffdd54&style=for-the-badge)](https://www.python.org/)  [![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-1.x-yellow?style=for-the-badge&logo=scikit-learn)](https://scikit-learn.org/)  [![XGBoost](https://img.shields.io/badge/XGBoost-1.x-orange?style=for-the-badge&logo=xgboost)](https://xgboost.ai/)  [![RandomForest](https://img.shields.io/badge/RandomForest-Regressor-brightgreen?style=for-the-badge)](https://scikit-learn.org/stable/modules/ensemble.html#forest)  [![R2 Score](https://img.shields.io/badge/R%C2%B2-0.66-success?style=for-the-badge)]() [![Gradio](https://img.shields.io/badge/-Gradio-3E8EFB?logo=gradio&logoColor=white&style=flat)](https://gradio.app/) 
---

## 🧠 Project Overview

This project predicts software engineer salaries using a thoughtfully engineered dataset composed of:

- **College Tier** (Tier 1–4)  
- **City:** Metro vs Non-Metro  
- **Experience (Years)**  
- **Role** and **Previous CTC**  
- **Academic Records**, etc.

Multiple regression models were trained and evaluated, with **Random Forest Regressor** emerging as the top performer.

---

## ⚙️ Data Preprocessing

- Converted *College* text to numerical tiers  
- Categorized *City* into Metro (1) & Non-Metro (0)  
- One-hot encoding for *Tier* & *Role*  
- Outlier detection using percentile limits  
- Capped extreme values by replacing them with mean statistics

---

## 🚀 Model Training & Evaluation

Models trained:

- Linear Regression  
- Ridge & Lasso  
- Decision Tree  
- **Random Forest Regressor**  
- Bagging Regressor  
- XGBoost Regressor

Standard scaling applied where necessary. GridSearchCV optimized hyperparameters and validated performance.

**Performance Summary:**

| Model                    | Train R² | Test R² | Test MSE (₹) |
|-------------------------|---------:|--------:|-------------:|
| **Random Forest**       | 0.9493   | **0.6590** | ~50 Lakh     |
| XGBoost                 | 0.7758   | 0.6261  | ~55 Lakh     |
| Bagging                 | 0.9474   | 0.6537  | ~51 Lakh     |
| Decision Tree (CV-tuned)| 0.6398   | 0.6032  | ~58 Lakh     |

✅ *Final model:* **Random Forest Regressor** with `max_depth=30` and `n_estimators=300`.

---

## 🧰 Tech Stack

- **Python 3.x**  
- **Pandas**, **NumPy**  
- **Scikit-Learn**, **XGBoost**, **GridSearchCV**  
- **Matplotlib**, **Seaborn**  
- **Gradio** for interactive UI  
- Developed using **Google Colab**

---

## 🗂 Repository Structure
```
├── ML Case Study.csv # Main dataset
├── Colleges.csv & Cities.csv
├── Salary_Prediction_Model_.ipynb # Colab notebook
├── app.py # Gradio UI launcher
├── saved_model.pkl # Serialized preprocessing + model
├── requirements.txt
└── README.md
```

---


## 📊 Project Output 
#### Google Colab Project Link : https://colab.research.google.com/github/vaishnxvii/Salary-Prediction-Model/blob/main/Salary_Prediction_Model_.ipynb
Preview
![Salary prediction model ss](https://github.com/user-attachments/assets/f9f45ee5-b54e-4f42-891b-3a38ff53d046)

---

## Install Necessary Modules:

Open your ![Anaconda](https://img.shields.io/badge/Anaconda-brightgreen?logo=anaconda) prompt and type and run the following command (individually): 
- ```
  pip install numpy
- ```
  pip install pandas
- ```
  pip install seaborn
- ```
  pip install matplotlib
- ```
  pip install statsmodels
- ```
  pip install scikit-learn
- ```
  pip install pydotplus
- ```
  pip install xgboost
- ```
  pip install tabulate
- ```
  pip install colorama
- ```
  pip install gradio

---

## 🎛 How to Run

```bash
git clone https://github.com/vaishnxvii/Salary-Prediction-Model.git
cd Salary-Prediction-Model
pip install -r requirements.txt
python app.py
```

This launches a Gradio interface where you can input employee details and instantly get salary estimates.

---

<p align="center">. . .</p>

<p align="center">Almost done, Hang in there ;)</p>
  
<p align="center">
  <img src="https://github.com/user-attachments/assets/b829824d-f908-4414-84ba-50f73517f16a" alt="Sticker Image">

</p>
<p align="center">. . .</p>

<p align="center">Once Installed now we can import it inside our python code.</p>

---

## 🔭 Next Steps
- Incorporate extra features (certifications, domain expertise, etc.)
- Develop deep-learning regression models
- Deploy online via Flask, FastAPI, or Streamlit
- Expand dataset to include broader regions and experience levels

---


<p align="center">. . .</p>

<p align="center">Good Work and Thank youu!</p>
  
<p align="center">
  <img src="https://github.com/user-attachments/assets/31aba53d-b9e4-4169-8634-257e681c3b8b" alt="Sticker 2">
</p>

<p align="center">. . .</p>


## 📄 License
Released under the MIT License — open for modification and contributions.

## ❤️ Want to Contribute?
Issues and pull requests are welcome!
Explore, fork, and enhance this project to suit your consulting needs.


<p align="center">. . .</p>
  
<p align="center">Have a Break, Have a coffee!.</p>
<p align="center">
  <img src="https://github.com/user-attachments/assets/c8993402-a353-4530-8121-43c441617270" alt="Sticker 2">
</p>



