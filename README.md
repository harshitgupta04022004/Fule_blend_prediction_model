

# Fuel Blend Properties Prediction

This repository contains our solution for the **Shell.ai Hackathon**, focused on predicting the fuel blend properties using machine learning models. Our top-performing model utilized **TabPFN**, which gave us the highest leaderboard score.

## 🧠 Problem Statement

Given a set of features corresponding to fuel blend compositions, the task is to accurately predict the physical and chemical properties of the final fuel blend. This is critical in optimizing fuel for performance, safety, and environmental compliance.

## 📁 Project Structure

```
├── Notebook
│   ├── fuel-blend-properties-predictio (3).ipynb
│   ├── fuel-blend-properties-predictio (4).ipynb
│   └── tabpfn_and_output_correction_method_y-y....ipynb   # Best performing model
│
├── 133e814757ed11f0
│   ├── fuel-blend-properties-predictio (1).ipynb
│   └── dataset
│
├── high_score
├── final_working.ipynb
└── README.md
```

## 🚀 Our Best Approach: TabPFN

* **Model:** TabPFN (Transformer-based Probabilistic Neural Network)
* **Strength:** No manual tuning needed
* **Result:** Achieved highest public leaderboard score in our submissions

## 🏗️ Setup Instructions

1. Clone the repo

```bash
git clone https://github.com/<your_repo_url>
cd fuel-blend-prediction
```

2. Install required dependencies:

```bash
pip install -r requirements.txt
```

3. Run the best model notebook:

```bash
jupyter notebook Notebook/tabpfn_and_output_correction_method_y-y....ipynb
```

## 👨‍💻 Team Members

* **Harshit Gupta** (Lead Developer)
* **Vedant** (Assistant Developer)
* **Harsh Vaishnav** (Contributor)
* **Chetan Luna** (Contributor)

## 📊 Results

* Public Leaderboard Rank: **Top Spot** (screenshot attached)
* Evaluation Metric: RMSE / MAE (as per competition)

## 📎 Files of Interest

* `Notebook/tabpfn_and_output_correction_method...ipynb` → Final solution
* `final_working.ipynb` → earlier model version
* `high_score/` → Stores predictions of best model
* `dataset/` → Input data (not included in repo)

## 📌 Future Scope

* Automate ensemble of multiple models
* Use AutoML tools for further boosting
* Dockerize the solution for reproducibility

## 📝 License

IIITN License. See `LICENSE` file for more info.

---

Feel free to open issues or pull requests. Contributions are welcome!
