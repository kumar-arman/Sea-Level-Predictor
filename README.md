# Sea Level Predictor

This project analyzes historical global sea level data and predicts future sea level rise using **linear regression**.  
It is part of the **freeCodeCamp – Data Analysis with Python Certification**.

The dataset contains measurements of global average sea level change from **1880 onward**.

---

## 📌 Project Objective

The objective of this project is to:
- Analyze historical sea level trends
- Apply linear regression to model sea level rise
- Predict sea level changes up to the year **2050**
- Compare long-term trends with recent trends (post-2000)

---

## 📊 Dataset Information

- File name: `epa-sea-level.csv`
- Source:  
  US Environmental Protection Agency (EPA)  
  Data from CSIRO (2015) and NOAA (2015)
- Columns:
  - `Year` – Year of measurement
  - `CSIRO Adjusted Sea Level` – Sea level in inches

---

## 🛠️ Technologies Used

- Python 3.11
- Pandas
- Matplotlib
- SciPy
- VS Code
- Git & GitHub

---

## 📂 Project Structure

sea-level-predictor/
│
├── epa-sea-level.csv
├── sea_level_predictor.py
├── main.py
├── README.md
└── .gitignore

yaml
Copy code

---

## ⚙️ Features Implemented

### 1. Data Visualization
- Created a scatter plot of historical sea level data
- Visualized trends clearly over time

### 2. Linear Regression (All Data)
- Calculated a line of best fit using data from **1880 onwards**
- Extended the prediction to the year **2050**

### 3. Linear Regression (Recent Data)
- Calculated a second line of best fit using data from **year 2000 onwards**
- Used this to predict sea level rise assuming recent trends continue

---

## ▶️ How to Run the Project

Ensure **Python 3.11** is installed.

### Install dependencies:
```bash
py -3.11 -m pip install pandas matplotlib scipy
Run the project:
bash
Copy code
py -3.11 main.py
📈 Output
Running the project generates:

sea_level_plot.png

The plot includes:

Scatter plot of historical data

Red regression line (1880–2050)

Green regression line (2000–2050)

🎯 Key Learnings
Working with real-world climate datasets

Scatter plot visualization using Matplotlib

Linear regression using SciPy

Predictive analysis and trend comparison

Data analysis using Pandas



📜 License
This project is open-source and intended for educational purposes.

yaml
Copy code

---

## 💾 Save the File
Press:
Ctrl + S

yaml
Copy code

---

## 📤 Commit & Push README to GitHub

Run:

```bash
git add README.md
git commit -m "Added README for Sea Level Predictor"
git push origin main
