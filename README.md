# Manufacturing Quality Analytics

Analyze manufacturing defects to support quality control: track defect rates, perform Pareto analysis, and monitor yield over time.

## 🔍 Problem
Quality teams need to identify the few defect types that cause most losses and spot where/when defects spike (machine, shift, product line).

## 🧠 What this project does
- Calculates KPIs: **defect rate**, **yield**, **Pareto distribution** (80/20).
- Visualizes trends over **time**, by **machine/line/shift** (as available in data).
- Highlights top contributors to defects to guide improvements.

## 📦 Data
- Source: Kaggle — *Manufacturing Defects / Data for Quality Control*.
- **Not included** in the repo. Place downloaded files in `/data`.

## 🛠️ Stack
- Python 3.10+
- pandas, numpy, matplotlib, jupyter

## 🚀 Quickstart
```bash
# 1) create & activate virtual env
python -m venv .venv
# Windows: .venv\Scripts\activate
# Mac/Linux:
source .venv/bin/activate

# 2) install deps
pip install -r requirements.txt

# 3) start Jupyter
jupyter notebook
