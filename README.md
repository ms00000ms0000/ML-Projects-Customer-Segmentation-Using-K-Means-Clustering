 # 🧩 ML Project - Customer Segmentation using K-Means Clustering  

## 🚀 Overview  
This **Machine Learning project** is based on **Customer Segmentation using K-Means Clustering**, an **unsupervised learning** technique. The dataset includes features such as **Customer ID, Gender, Age, Annual Income (k$), and Spending Score (1–100)** to group customers based on their purchasing behavior.  

The **WCSS (Within-Cluster Sum of Squares)** values were calculated for different cluster numbers, and the **Elbow Method** was applied to find the optimal number of clusters. The clusters were **visualized using scatter plots**, particularly **Annual Income vs. Spending Score**, revealing clear customer groups.  

This project demonstrates ML’s capability in **market segmentation and business strategy optimization** by identifying patterns in customer spending behavior.  

---

## 🔍 About the Project  
This project applies **unsupervised learning** to divide customers into distinct segments without predefined labels.  
Businesses can use these clusters to develop **targeted marketing strategies**, **personalized offers**, and **customer retention plans**.  
The analysis helps identify **high-value**, **medium-value**, and **low-value** customers based on their income and spending patterns.  

---

## 🧠 Model Architecture  
The project uses the **K-Means Clustering algorithm**, which groups data points into **k distinct clusters** based on feature similarity.  

* **Algorithm:** K-Means Clustering  
* **Problem Type:** Unsupervised Learning  
* **Evaluation Metric:** WCSS (Within-Cluster Sum of Squares)  
* **Optimization Technique:** Elbow Method  

---

## 🧾 Dataset Description  
The dataset contains demographic and behavioral attributes used for customer grouping:  

| Feature | Description |
|----------|-------------|
| **CustomerID** | Unique ID assigned to each customer |
| **Gender** | Gender of the customer (Male/Female) |
| **Age** | Age of the customer |
| **Annual Income (k$)** | Annual income of the customer in thousand dollars |
| **Spending Score (1–100)** | Score assigned based on customer spending behavior |

---

## ⚙️ Tech Stack & Libraries  

**Language:**  
* Python 🐍  

**Libraries:**  
* **NumPy** – Numerical computations  
* **Pandas** – Data preprocessing and manipulation  
* **Matplotlib / Seaborn** – Data visualization  
* **Scikit-learn** – K-Means clustering implementation and evaluation  

---

## 🚀 Features  
* Performs **Customer Segmentation** using K-Means Clustering  
* Applies **Elbow Method** to determine optimal number of clusters  
* Visualizes clusters using **2D scatter plots**  
* Helps in **market strategy optimization**  
* Assists businesses in **targeted marketing** and **customer profiling**  

---

## 📊 Results  
The **Elbow Method** indicated the optimal number of clusters (typically 5), resulting in distinct customer segments based on **Annual Income** and **Spending Score**.  
The **visual clusters** provide insights into high-spending customers and potential target groups for marketing.  


![customer_segmentation](https://github.com/user-attachments/assets/a2156e2b-4a2b-46b6-954e-cf942e626ab3)


---

## 📁 Repository Structure  

```

📦 ML-Projects-Customer-Segmentation-Using-K-Means-Clustering
│
├── Customer_Segmentation_KMeans.ipynb # Jupyter Notebook implementation
├── Mall_Customers.csv # Dataset used for training and analysis
└── README.md # Project documentation

```

---

## 🧪 How to Run  

1. **Clone the repository:**  
   ```bash
   git clone https://github.com/ms00000ms0000/ML-Projects-Customer-Segmentation-Using-K-Means-Clustering.git
   cd ML-Projects-Customer-Segmentation-Using-K-Means-Clustering

2. **Install dependencies:**
   ```bash
   pip install -r requirements.txt
   ```

3. **Run the Jupyter Notebook:**
   ```bash
   jupyter notebook Customer_Segmentation_KMeans.ipynb
   ```

4. **Execute all cells to perform clustering and visualize results.**

---

## 📈 Future Improvements

* Implement DBSCAN or Hierarchical Clustering for comparison

* Add an interactive Streamlit dashboard for real-time customer segmentation

* Include demographic insights for advanced business intelligence

---

## 👨‍💻 Developer

Developed by: Mayank Srivastava
