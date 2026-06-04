# SalesInsight PY

## Overview

SalesInsight PY is a Python-based sales analytics solution designed to transform raw sales records into actionable business insights. The project simulates a real-world data analysis workflow by generating, cleaning, transforming, analyzing, and visualizing sales information through an automated pipeline.

The application was developed as part of the *Artificial Intelligence for Predictive Analytics* program and demonstrates the practical application of data processing, exploratory analysis, object-oriented programming, and software development best practices.

---

## Project Goals

The main objective of this project is to build an end-to-end sales analysis pipeline capable of:

* Generating and processing sales datasets;
* Detecting and handling data quality issues;
* Producing aggregated business metrics;
* Identifying customer spending patterns;
* Visualizing trends through charts and reports;
* Exporting analytical results to external files;
* Creating a simple revenue forecast based on historical performance.

---

## Business Questions Answered

The pipeline was designed to answer common business intelligence questions such as:

### Sales Performance

* How does revenue evolve throughout the year?
* Which months generate the highest sales volume?
* What are the quarterly revenue trends?

### Product Analysis

* Which products generate the highest revenue?
* Which categories contribute most to total sales?

### Regional Performance

* Which regions have the strongest sales performance?
* How does revenue distribution vary across regions?

### Customer Analysis

* Who are the most valuable customers?
* How can customers be segmented according to spending behavior?

### Revenue Forecasting

* What is the expected revenue trend for the next few months based on historical data?

---

## Main Features

### Data Generation

* Synthetic sales dataset generation
* Controlled randomness using seeds
* Intentional insertion of dirty data for cleaning exercises

### Data Cleaning

* Missing value handling
* Invalid date detection
* String normalization
* Data type correction
* Regular expression-based validation

### Data Transformation

* Revenue calculation
* Date decomposition (month, quarter, year)
* Revenue range classification
* Conditional transformations using NumPy

### Business Analytics

* Monthly revenue analysis
* Quarterly revenue analysis
* Product ranking
* Category performance
* Regional performance
* Customer segmentation

### Statistical Analysis

* Mean
* Median
* Standard deviation
* Percentiles
* Min-Max normalization
* Vectorized calculations

### Visualization

* Revenue evolution over time
* Top-performing products
* Regional revenue distribution

### Forecasting

* Moving-average-based revenue projection
* Multi-month forecasting
* Forecast reporting

### Exporting Results

* CSV reports
* JSON statistics
* PNG charts

---

## Concepts Demonstrated

This project applies several concepts covered throughout the course:

### Python Fundamentals

* Variables and data types
* Arithmetic and logical operators
* Conditional statements
* Loops
* Functions and modularization
* Lambda functions
* Higher-order functions

### Data Processing

* CSV reading and writing
* JSON serialization and deserialization
* Date and time manipulation
* Regular expressions

### Pandas

* DataFrames and Series
* Filtering and selection
* GroupBy aggregations
* Data transformations
* Vectorized operations

### NumPy

* Arrays
* Statistical functions
* Broadcasting
* Conditional vectorization with `np.select`

### Data Visualization

* Matplotlib
* Seaborn
* Chart customization
* Image export

### Object-Oriented Programming

* Classes
* Constructors
* Instance attributes
* Methods
* Inheritance
* super()

### Software Engineering Practices

* Git and GitHub
* Branching strategy
* Commit history
* Kanban workflow
* Project organization

---

## Project Structure

```text
salesinsight-py/
│
├── README.md
├── salesinsight.py
├── sales.csv
│
├── outputs/
│   ├── summary_report.csv
│   ├── metrics_by_month.csv
│   ├── customer_segmentation.csv
│   ├── general_statistics.json
│   └── charts/
│       ├── sales_by_month.png
│       ├── top_products.png
│       └── regional_distribution.png
│
└── planning/
    └── kanban_tasks.md
```

---

## Installation

### Requirements

* Python 3.10 or newer
* Pandas
* NumPy
* Matplotlib
* Seaborn

Install dependencies:

```bash
pip install pandas numpy matplotlib seaborn
```

---

## Running the Application

The project can be executed using one of the following environments.

### Visual Studio Code (Recommended)

1. Open the project folder in VS Code.
2. Install the following extensions:
   * Python
   * Jupyter
3. Open the `salesinsight.ipynb` notebook.
4. Execute the notebook cells sequentially from top to bottom.
5. The generated files (reports, charts, and JSON outputs) will be saved automatically in the `outputs/` directory.

### Jupyter Notebook

1. Launch Jupyter Notebook:
```bash
jupyter notebook
```

2. Open the file:
```text
salesinsight.ipynb
```

3. Run all cells sequentially.

### Google Colab

1. Upload the notebook file `salesinsight.ipynb`.
2. Execute the cells from top to bottom.
3. Download the generated outputs if needed.

### Running as a Python Script

If using the `.py` version of the project:

```bash
python salesinsight.py
```

Make sure all required dependencies are installed before execution.

### Installing Dependencies

```bash
pip install pandas numpy matplotlib seaborn
```

---

## Internet and Client-Server Context

In this project, data is loaded from a local CSV file. However, in a production environment, the same information could be obtained from web services through APIs.

In a client-server architecture, the Python application acts as the client, sending requests to a remote server. The server processes the request and returns structured data, often in JSON format, which can then be analyzed by the application.

This architecture is widely used in modern analytics platforms, dashboards, ERP systems, CRM systems, and cloud-based business applications.

---

## Development Workflow

The project was organized using a Kanban approach, allowing the development process to be divided into manageable tasks and tracked through completion.

Version control was managed using Git and GitHub with a simplified branching strategy, ensuring that features, documentation, and improvements were developed independently before integration.

---

## Future Improvements

Potential enhancements include:

* Integration with real-world datasets;
* Database connectivity;
* Dashboard development using Streamlit or Power BI;
* Machine Learning forecasting models;
* REST API integration;
* Automated reporting;
* Cloud deployment.

---

## Demonstration Video

Video link:

---

## Author

Developed as part of the *Artificial Intelligence for Predictive Analytics* coursework, demonstrating data analysis, software engineering, and Python programming skills through a complete sales analytics pipeline.

---

## About SCTEC and SENAI SC
https://sctec.scti.sc.gov.br/#sobre
https://sc.senai.br/sobre-senai
