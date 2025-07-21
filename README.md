# ML-Algorithms-Tutorial

Welcome to the **ML-Algorithms-Tutorial** repository!  
This project contains a comprehensive collection of Jupyter notebooks demonstrating various machine learning algorithms, including supervised, unsupervised, semi-supervised, and reinforcement learning, along with rich visualizations and interactive dashboards.

---

## 📂 Project Structure

```
ML-Algorithms-Tutorial/
│
├── datasets/                      # Raw datasets organized by task
│   ├── anomaly_detection/
│   │   └── creditcard.csv
│   ├── association/
│   │   └── groceries.csv
│   ├── classification/
│   │   ├── diabetes.csv
│   │   ├── iris.csv
│   │   └── titanic.csv
│   ├── clustering/
│   │   ├── Mall_Customers.csv
│   │   └── wholesale_customers.csv
│   └── regression/
│       ├── auto_mpg.data
│       └── boston_housing.csv
│
├── notebooks/                    # Organized notebooks by ML type and topic
│   ├── 01_supervised/
│   │   ├── classification/
│   │   │   ├── Diabetes_Predictor.ipynb
│   │   │   ├── iris_classification.ipynb
│   │   │   └── Titanic_Classifier.ipynb
│   │   └── regression/
│   │       ├── AutoMPG_Regression.ipynb
│   │       └── BostonHousing_Regression.ipynb
│   ├── 02_unsupervised/
│   │   ├── anomaly_detection/
│   │   │   └── creditcard_anomaly.ipynb
│   │   ├── association/
│   │   │   ├── Groceries_AssociationRules.ipynb
│   │   │   └── market_basket.ipynb
│   │   └── clustering/
│   │       ├── mall_clustering.ipynb
│   │       ├── Mall_Customers_Segmentation.ipynb
│   │       └── Wholesale_Customers_Segmentation.ipynb
│   ├── 03_semi_supervised/
│   │   └── semi_supervised_intro.ipynb
│   └── 04_reinforcement/
│       └── reinforcement_intro.ipynb
│
├── README.md                     # This file
└── requirements.txt              # Python dependencies
```

---

## 📊 Dataset Summary

- **anomaly_detection/creditcard.csv** — Credit card transaction data for fraud detection  
- **association/groceries.csv** — Market basket transactional data for association rule mining  
- **classification/** — Multiple datasets for classification tasks: diabetes, iris flower, titanic survival  
- **clustering/** — Customer segmentation datasets for clustering examples  
- **regression/** — Classic regression datasets like Auto MPG and Boston Housing

---

## 📓 Notebook Summaries

### 01_supervised
- **Diabetes_Predictor.ipynb** — Predict diabetes presence using classification algorithms with data preprocessing and evaluation  
- **iris_classification.ipynb** — Multi-class classification on iris dataset with model building and metrics  
- **Titanic_Classifier.ipynb** — Titanic survival prediction with feature engineering and multiple classifiers  
- **AutoMPG_Regression.ipynb** — Predicting car mileage using linear regression models  
- **BostonHousing_Regression.ipynb** — Regression on Boston housing prices with exploratory data analysis and model comparison  

### 02_unsupervised
- **creditcard_anomaly.ipynb** — Anomaly detection in credit card transactions using unsupervised methods  
- **Groceries_AssociationRules.ipynb** — Frequent itemset mining and association rules using Apriori algorithm  
- **market_basket.ipynb** — Market basket analysis with visualization of frequent itemsets  
- **mall_clustering.ipynb** — Customer segmentation using KMeans, hierarchical clustering, and DBSCAN  
- **Mall_Customers_Segmentation.ipynb** — Interactive clustering dashboard and EDA on mall customer data  
- **Wholesale_Customers_Segmentation.ipynb** — Clustering and segmentation of wholesale customer data  

### 03_semi_supervised
- **semi_supervised_intro.ipynb** — Introduction to semi-supervised learning concepts and algorithms with illustrative examples  

### 04_reinforcement
- **reinforcement_intro.ipynb** — Basics of reinforcement learning, including Q-learning, DQN, and policy gradient methods, with example environments and visualizations  

---

## ⚙️ Setup Instructions

1. Clone this repository:
   ```bash
   git clone <repo_url>
   cd ML-Algorithms-Tutorial
   ```

2. Create and activate a Python environment (recommended):
   ```bash
   python -m venv venv
   source venv/bin/activate   # On Windows: venv\Scripts\activate
   ```

3. Install required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

4. Launch Jupyter Notebook or JupyterLab:
   ```bash
   jupyter notebook
   # or
   jupyter lab
   ```

5. Open notebooks from the `notebooks/` directory and run the cells interactively.

---

## 🛠️ Features

- Data preprocessing and cleaning examples  
- Exploratory data analysis with rich visualizations  
- Implementation of various ML algorithms: supervised, unsupervised, semi-supervised, and reinforcement learning  
- Interactive dashboards for clustering and association rules  
- Use of Plotly for dynamic 2D/3D visualizations  
- Modular code with clear markdown explanations  

---

## 📈 How to Use

- Select a notebook based on your learning goal  
- Explore step-by-step guided code with explanations and plots  
- Modify parameters and interact with widgets in clustering notebooks  
- Experiment with datasets and algorithms to understand behavior  

---

## 🙋‍♂️ Contribution

Feel free to open issues or submit pull requests to enhance notebooks or add new algorithms.

---

## 📜 License

Specify your license here, e.g., MIT License.

---

Thank you for exploring **ML-Algorithms-Tutorial**!  
Happy learning and coding! 🚀
