# Solar Farm Investment Analysis – Moonlight Solar Solutions

This project is part of a case study aiming to support **Moonlight Solar Solutions** in improving operational efficiency and sustainability through data-driven decisions. The goal is to identify strategic, high-potential regions for solar farm investment by conducting a thorough Exploratory Data Analysis (EDA) across datasets from three countries.

---

## 📊 Project Objectives

- Understand and clean datasets from three different regions.
- Perform in-depth EDA using Python libraries.
- Compare key metrics and conduct statistical testing.
- Visualize findings to support strategic business decisions.
- Recommend regions with strong potential for solar farm development.

---



## 📁 Project Structure

```plaintext

solar-challenge-week1/
├── .github/workflows/ci.yml       # ✅ GitHub Actions pipeline to install dependencies 
├── .gitignore                     # ✅ Ignores data files, venv, and cache 
├── .vscode/settings.json          # ✅ Ensures consistent IDE behavior 

├── notebooks/                     # 📓 Exploratory profiling notebooks
│   ├── _init_.py                   
│   ├── benin_eda.ipynb            # EDA & validation for Benin
│   ├── sierraleone_eda.ipynb      # EDA & validation for Sierra Leone
│   └── togo_eda.ipynb             # EDA & validation for Togo

├── scripts/                           
│   ├── __init__.py
 
├── tests/                         
│   ├── __init__.py
 
├── requirements.txt               # 📦 Python dependencies  
└── README.md                      # 📘 Project overview, setup steps, and task progress

```

## 🛠️ Tools and Libraries

- **Python**: Programming language used for analysis.
- **Pandas**: Data manipulation and analysis.
- **Matplotlib & Seaborn**: Data visualization.
- **NumPy**: Numerical computations.
- **Jupyter Notebook**: Interactive coding environment.
- **scipy**: Statistical Computation.
---

## 📈 Methodology

1. **Data Understanding**: Reviewed the project description and data columns to grasp the dataset's structure and content.
2. **Environment Setup**: Initialized a GitHub repository and set up a virtual environment.
3. **Data Analysis**:
   - Loaded and cleaned datasets from three countries.
   - Conducted EDA to identify trends and anomalies.
   - Compared metrics across datasets.
   - Performed statistical testing based on Key Performance Indicators (KPIs).
4. **Visualization**: Created visual summaries to illustrate findings.
5. **Code Modularization**: Refactored code for clarity and reusability.
6. **Reporting**: Documented insights and recommendations.

---

## 🚀 How to Run This Project

Follow the steps below to set up and run the project on your local machine:

### 1. Clone the Repository

```bash
git clone https://github.com/mesay-tadesse/solar-challenge-week1.git
cd solar-challenge-week1
# Create a virtual environment
python -m venv venv

# Activate the virtual environment
# On Windows:
venv\Scripts\activate

# On macOS/Linux:
source venv/bin/activate
# Create a virtual environment
python -m venv venv

# Activate the virtual environment
# On Windows:
venv\Scripts\activate

# On macOS/Linux:
source venv/bin/activate

pip install -r requirements.txt

jupyter notebook
```

## 👤 Author

- **Name**: Metasebiya Akililu
- **GitHub**: [@mesay-tadesse](https://github.com/mesay-tadesse)

---

## 📄 License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

## 📬 Contact

For questions or feedback, please reach out via [GitHub Issues](https://github.com/mesay-tadesse/solar-challenge-week1/issues).