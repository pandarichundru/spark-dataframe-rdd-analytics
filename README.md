# Big Data Log Analysis Using Apache Spark

This project demonstrates unstructured web server log data processing using Apache Spark's DataFrame and RDD APIs. It was developed as part of the Big Data Analytics coursework.

## 📌 Project Overview

The notebook performs end-to-end analysis on raw server logs, extracting key fields and conducting both statistical and exploratory analyses. It visualizes the results using PySpark and Matplotlib.

## 🧰 Technologies Used

- Apache Spark (DataFrame & RDD APIs)
- PySpark SQL
- Python (pandas, matplotlib)
- Jupyter Notebook


## 🚀 How to Run

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/big-data-log-analysis-spark.git
   cd big-data-log-analysis-spark
   ```

2. **Install dependencies**
   Make sure Spark and PySpark are installed:
   ```bash
   pip install pyspark pandas matplotlib
   ```

3. **Run the notebook**
   Open `76_CN7031.ipynb` in Jupyter and run the cells step-by-step.

## 🔍 Key Features

- Converts raw log text to structured DataFrame using regex.
- Uses SQL queries for aggregation and filtering.
- Visualizes insights (top hosts, traffic stats, status code distribution).
- RDD transformations for low-level log byte analysis.

## 📊 Sample Analyses

- Top 3 hosts with highest average response size.
- Distribution of bytes in replies over time.
- Most frequently accessed URLs with status 200.
- HTTP version-wise total byte usage using RDDs.

## 📘 Author

**Pandari Naga Veera Sainath Chundru**  


## 📜 License

This project is for academic purposes only. Contact the author for reuse permissions.
