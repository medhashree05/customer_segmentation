#  Customer Segmentation using K-Means Clustering

##  Overview

This project performs **customer segmentation** using the K-Means clustering algorithm to group users based on their behavior. The goal is to identify distinct customer segments and derive actionable business insights.

---

##  Objective

* Segment customers into meaningful groups
* Understand user behavior patterns
* Enable targeted marketing and retention strategies

---

##  Dataset

* **Telco Customer Churn Dataset**
* Features used for clustering:

  * Tenure
  * Monthly Charges
  * Total Charges

---

## Tech Stack

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn

---

##  Methodology

### 1. Data Preprocessing

* Removed unnecessary columns (customerID)
* Converted `TotalCharges` to numeric
* Handled missing values
* Applied one-hot encoding for categorical variables

### 2. Feature Selection

Selected key features:

* Tenure
* Monthly Charges
* Total Charges

### 3. Feature Scaling

* Standardized data using `StandardScaler`

### 4. Clustering

* Applied **K-Means Clustering**
* Used **Elbow Method** to determine optimal number of clusters

### 5. Visualization

* Used **PCA** to reduce dimensions
* Visualized clusters in 2D space

---

##  Results

The model segmented customers into **3 clusters**:

###  Cluster 0: Loyal Customers

* High tenure
* High spending
* Highly engaged users

###  Cluster 1: Low Engagement Customers

* Low tenure
* Low spending
* New or inactive users

###  Cluster 2: At-Risk Customers

* High spending
* Low tenure
* Likely to churn

---

##  Business Insights

* Provide **loyalty rewards** to high-value customers
* Use **promotions and onboarding** for low-engagement users
* Target at-risk users with **retention strategies and offers**

---

##  Key Learnings

* Importance of feature scaling in clustering
* Using Elbow Method to select optimal clusters
* Translating data into business insights

---

## How to Run

1. Clone the repository

```bash
git clone https://github.com/medhashree05/customer_segmentation.git
```

2. Install dependencies

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

3. Run the notebook

* Open in Jupyter / Colab
* Execute all cells

---

##  Future Improvements

* Add more behavioral features
* Try other clustering techniques (DBSCAN, Hierarchical)
* Build a real-time dashboard using Streamlit

---

##  Author

**Medha Shree N**
