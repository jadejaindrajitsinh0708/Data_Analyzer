# 📊 Python — Data Analysis & Visualization Program

A simple Data Analysis and Visualization project built with Python to analyze CSV datasets, perform data operations, handle missing values, and generate different types of graphs.

## 📌 Project Description

This is a menu-driven Data Analysis and Visualization Program created using Python.

The project demonstrates important Python data analysis concepts such as:

* Loading CSV Datasets
* Exploring Data
* DataFrame Operations
* Handling Missing Values
* Descriptive Statistics
* Data Visualization
* Generating Different Types of Charts
* Saving Visualizations

## 🛠️ Technologies Used

* Python 3 – Main programming language
* Pandas – Data manipulation and analysis
* Matplotlib – Data visualization
* Seaborn – Statistical data visualization
* Git – Version control system
* GitHub – Repository and code hosting platform

## 📂 Project Structure

```text

│
├── README.md
├── main.py
├── sales_data.csv
│
└── plot/
```



## 📌 Features

### 1. Load Dataset

* Load CSV files using Pandas.
* Display a success message after loading.
* Handle invalid file paths.

### 2. Explore Data

* Display the first 5 rows.
* Display the last 5 rows.
* Display column names.
* Display data types.
* Display basic dataset information.

### 3. DataFrame Operations

* Calculate the total sales.
* Display the top 5 products with highest sales.
* Display the top 5 products with lowest sales.
* Find the region with highest sales.
* Calculate total quantity sold by each product.

### 4. Handle Missing Data

* Display missing values.
* Fill missing values with the mean.
* Drop rows with missing values.
* Replace missing values with a specific value.

### 5. Generate Descriptive Statistics

* Calculate minimum value.
* Calculate maximum value.
* Calculate average (mean).
* Calculate median.
* Calculate standard deviation.

### 6. Data Visualization

The program supports different types of charts:

* Bar Plot
* Line Plot
* Scatter Plot
* Pie Chart
* Histogram
* Area Plot

### 7. Save Visualization

* Save generated graphs as PNG images.
* Save images with 300 DPI resolution.
* Store visualizations inside the plot directory.

## 🧠 Python Concepts Used

### Pandas

Pandas is used to load, explore, manipulate, and analyze CSV datasets.

Example:

```python
self.data = pd.read_csv(path)
```

### Data Exploration

Pandas functions are used to explore dataset information.

```python
self.data.head()
self.data.tail()
self.data.columns
self.data.dtypes
self.data.info()
```

### DataFrame Operations

GroupBy and aggregation functions are used to perform data analysis.

```python
self.data.groupby("Region")["Sales"].sum()
```

### Missing Value Handling

Pandas functions are used to identify and handle missing values.

```python
self.data.isnull().sum()
self.data.dropna(inplace=True)
```

### Descriptive Statistics

Statistical functions are used to calculate numerical summaries.

```python
self.data.describe()
self.data.mean(numeric_only=True)
self.data.median(numeric_only=True)
```

### Data Visualization

Matplotlib and Seaborn are used to create different types of charts.

```python
sns.barplot(data=self.data, x=x, y=y)
```

```python
sns.scatterplot(data=self.data, x=x, y=y)
```

## 📋 Menu Options

When the program starts, the following menu is displayed:

```text
=============== Data Analysis & Visualization Program ===============

1. Load Dataset
2. Explore Data
3. Perform DataFrame Operations
4. Handle Missing Data
5. Generate Descriptive Statistics
6. Data Visualization
7. Save Visualization
8. Exit

======================================================================
```

### 1. Load Dataset

Loads a CSV dataset from the specified file path.

### 2. Explore Data

Displays the first 5 rows, last 5 rows, column names, data types, and basic information.

### 3. Perform DataFrame Operations

Performs sales analysis, product analysis, and region-wise sales analysis.

### 4. Handle Missing Data

Displays, fills, drops, and replaces missing values.

### 5. Generate Descriptive Statistics

Calculates minimum, maximum, average, median, and standard deviation.

### 6. Data Visualization

Creates Bar, Line, Scatter, Pie, Histogram, and Area-style plots.

### 7. Save Visualization

Saves the generated graph as a PNG image.

### 8. Exit

Exits the program.

## 📊 Dataset Requirements

For sales analysis operations, the CSV dataset should contain the following columns:

* Sales
* Product
* Region
* Quantity

Example Dataset:

```csv
Product,Region,Sales,Quantity
Laptop,North,50000,5
Mobile,South,30000,10
Tablet,East,20000,8
Laptop,West,60000,6
Mobile,North,40000,12
```

## ▶️ How to Run

Make sure Python 3 is installed on your computer.

### Install Required Libraries

```bash
pip install pandas matplotlib seaborn
```

### Clone the Repository

```bash
git clone https://github.com/your-username/Data-Analysis-Visualization.git
```

### Go to the Project Folder

```bash
cd Data-Analysis-Visualization
```

### Run the Python Program

```bash
python main.py
```

## 💻 Example Output

```text
=============== Data Analysis & Visualization Program ===============

1. Load Dataset
2. Explore Data
3. Perform DataFrame Operations
4. Handle Missing Data
5. Generate Descriptive Statistics
6. Data Visualization
7. Save Visualization
8. Exit

Enter Your Choice: 1

Enter Dataset Path: data/sales_data.csv

Dataset Loaded Successfully!
```

### Example Data Analysis Output

```text
Total Sales: 200000

Region with Highest Sales: West

Top 5 Products with Highest Sales:
0    50000
1    30000
2    20000
3    60000
4    40000
```


## 👨‍💻 Author

**INDRAJIT SINH**