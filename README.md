# PANDAS
A comprehensive collection of pandas tutorials, core concepts, and extensive practice problems covering everything from basics to advanced data manipulation techniques. This repository serves as a complete learning resource for mastering pandas - Python's most powerful data analysis library.
pandas/
# 🐼 Pandas - Complete Learning Repository

![Python](https://img.shields.io/badge/Python-3.8+-blue.svg)
![Pandas](https://img.shields.io/badge/Pandas-2.0+-green.svg)
![License](https://img.shields.io/badge/License-MIT-yellow.svg)
![Contributions](https://img.shields.io/badge/Contributions-Welcome-orange.svg)

## 📌 Table of Contents
- [About](#about)
- [Installation](#installation)
- [Repository Structure](#repository-structure)
- [Topics Covered](#topics-covered)
- [Getting Started](#getting-started)
- [Practice Problems](#practice-problems)
- [Usage Examples](#usage-examples)
- [Resources](#resources)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## 📖 About

Welcome to my **Pandas Complete Learning Repository**! This is a comprehensive collection of tutorials, examples, and practice problems covering everything you need to master pandas - Python's most powerful data analysis library.

This repository is part of my **Data Science Journey** and serves as:
- 📚 A complete learning resource for pandas
- 💻 A hands-on practice platform
- 🔍 A quick reference guide
- 🎯 A portfolio showcase of data manipulation skills

Whether you're a complete beginner or looking to advance your pandas skills, this repository has something for everyone!

## 🚀 Installation

### Prerequisites
```bash
Python 3.8 or higher
```

### Required Libraries
```bash
pip install pandas numpy matplotlib seaborn jupyter
```

### Clone This Repository
```bash
git clone https://github.com/parul1806-byte/PANDAS
cd pandas
```

### Install Dependencies
```bash
pip install -r requirements.txt
```

## 📂 Repository Structure
```
pandas/
│
├── 01_Basics/
│   ├── 01_series_operations.ipynb
│   ├── 02_dataframe_fundamentals.ipynb
│   ├── 03_data_types_indexing.ipynb
│   └── README.md
│
├── 02_Data_Selection/
│   ├── 01_loc_iloc_indexing.ipynb
│   ├── 02_conditional_selection.ipynb
│   ├── 03_boolean_masking.ipynb
│   └── README.md
│
├── 03_Data_Manipulation/
│   ├── 01_arithmetic_operations.ipynb
│   ├── 02_column_operations.ipynb
│   ├── 03_row_operations.ipynb
│   └── README.md
│
├── 04_Data_Cleaning/
│   ├── 01_handling_missing_values.ipynb
│   ├── 02_duplicate_removal.ipynb
│   ├── 03_data_type_conversion.ipynb
│   └── README.md
│
├── 05_Data_Aggregation/
│   ├── 01_groupby_operations.ipynb
│   ├── 02_pivot_tables.ipynb
│   ├── 03_statistical_functions.ipynb
│   └── README.md
│
├── 06_Merging_Joining/
│   ├── 01_concat_operations.ipynb
│   ├── 02_merge_operations.ipynb
│   ├── 03_join_techniques.ipynb
│   └── README.md
│
├── 07_Advanced_Topics/
│   ├── 01_time_series_analysis.ipynb
│   ├── 02_multi_indexing.ipynb
│   ├── 03_apply_lambda_functions.ipynb
│   ├── 04_string_operations.ipynb
│   └── README.md
│
├── 08_Practice_Problems/
│   ├── Beginner/
│   │   ├── problems_01_20.ipynb
│   │   ├── problems_21_50.ipynb
│   │   └── solutions.ipynb
│   ├── Intermediate/
│   │   ├── problems_01_30.ipynb
│   │   ├── problems_31_60.ipynb
│   │   └── solutions.ipynb
│   └── Advanced/
│       ├── problems_01_25.ipynb
│       └── solutions.ipynb
│
├── 09_Real_World_Projects/
│   ├── sales_analysis/
│   ├── student_performance/
│   ├── financial_analysis/
│   └── ecommerce_analytics/
│
├── 10_Datasets/
│   ├── sample_data/
│   ├── practice_datasets/
│   └── README.md
│
├── Cheat_Sheets/
│   ├── pandas_quick_reference.pdf
│   ├── common_operations.md
│   └── interview_questions.md
│
├── requirements.txt
├── .gitignore
├── LICENSE
└── README.md
```

## 📚 Topics Covered

### 1️⃣ Basics
- Creating Series and DataFrames
- Understanding data structures
- Basic indexing and selection
- Data types and type conversion
- Inspecting DataFrames (head, tail, info, describe)

### 2️⃣ Data Selection & Filtering
- Label-based indexing (`.loc[]`)
- Position-based indexing (`.iloc[]`)
- Boolean indexing and masking
- Query method
- Conditional selection with multiple conditions

### 3️⃣ Data Manipulation
- Arithmetic operations
- Column creation and deletion
- Row operations
- Applying functions
- Data transformation techniques

### 4️⃣ Data Cleaning
- Handling missing values (dropna, fillna)
- Removing duplicates
- Data type conversions
- Replacing values
- Detecting and handling outliers

### 5️⃣ Data Aggregation
- GroupBy operations
- Aggregation functions (sum, mean, count, etc.)
- Pivot tables and crosstabs
- Multi-level aggregation
- Custom aggregation functions

### 6️⃣ Combining DataFrames
- Concatenation (concat)
- Merging (merge, join)
- Different join types (inner, outer, left, right)
- Handling duplicate columns

### 7️⃣ Advanced Operations
- Time series analysis
- Multi-indexing (hierarchical indexing)
- Apply, map, and applymap
- Lambda functions
- String operations
- Window functions (rolling, expanding)

### 8️⃣ Performance Optimization
- Efficient data types
- Vectorization
- Avoiding loops
- Memory management
- Best practices

## 🎯 Getting Started

### For Beginners
Start with the basics:
1. Navigate to `01_Basics/`
2. Open `01_series_operations.ipynb`
3. Follow along with the examples
4. Complete the exercises at the end

### For Intermediate Learners
Jump to specific topics:
1. Review the topics you want to learn
2. Navigate to the relevant folder
3. Practice with provided examples
4. Solve practice problems

### For Advanced Users
Challenge yourself:
1. Go to `08_Practice_Problems/Advanced/`
2. Try solving without looking at solutions
3. Explore `09_Real_World_Projects/`
4. Contribute new problems or optimizations

## 🧩 Practice Problems

### Beginner Level (50+ Problems)
- Basic DataFrame operations
- Simple filtering and selection
- Basic arithmetic operations
- Creating new columns

### Intermediate Level (100+ Problems)
- Complex conditional selection
- GroupBy and aggregations
- Merging multiple DataFrames
- Data cleaning challenges

### Advanced Level (75+ Problems)
- Multi-step data analysis
- Performance optimization
- Complex transformations
- Real-world scenarios

## 💡 Usage Examples

### Example 1: Creating and Manipulating a DataFrame
```python
import pandas as pd

# Create a DataFrame
df = pd.DataFrame({
    'Name': ['Alice', 'Bob', 'Charlie', 'David'],
    'Age': [25, 30, 35, 28],
    'Score': [85, 92, 78, 95]
})

# Filter rows where Score > 80
high_scorers = df[df['Score'] > 80]

# Add a new column
df['Grade'] = df['Score'].apply(lambda x: 'A' if x >= 90 else 'B' if x >= 80 else 'C')

print(df)
```

### Example 2: GroupBy Operations
```python
# Group by category and calculate statistics
df.groupby('Category').agg({
    'Sales': ['sum', 'mean', 'count'],
    'Profit': 'sum'
})
```

### Example 3: Handling Missing Data
```python
# Fill missing values with mean
df['Column'].fillna(df['Column'].mean(), inplace=True)

# Drop rows with any missing values
df_clean = df.dropna()
```

## 📊 Current Progress

- [x] Series Operations ✅
- [x] DataFrame Fundamentals ✅
- [x] Arithmetic Operations ✅
- [ ] Data Cleaning (In Progress) 🔄
- [ ] GroupBy Operations
- [ ] Merging & Joining
- [ ] Time Series Analysis
- [ ] Advanced Topics

**Problems Solved:** 75+ / 300+ Target

## 🛠️ Tools & Technologies

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white)

## 📖 Resources

### Official Documentation
- [Pandas Official Docs](https://pandas.pydata.org/docs/)
- [NumPy Documentation](https://numpy.org/doc/)

### Recommended Learning
- [10 Minutes to Pandas](https://pandas.pydata.org/docs/user_guide/10min.html)
- [Pandas Cheat Sheet](https://pandas.pydata.org/Pandas_Cheat_Sheet.pdf)

### Additional Practice
- [Kaggle Datasets](https://www.kaggle.com/datasets)
- [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/index.php)

## 🤝 Contributing

Contributions are always welcome! Here's how you can help:

1. **Fork the repository**
2. **Create a new branch** (`git checkout -b feature/new-topic`)
3. **Make your changes**
4. **Commit your changes** (`git commit -m 'Add new topic: XYZ'`)
5. **Push to the branch** (`git push origin feature/new-topic`)
6. **Open a Pull Request**

### What You Can Contribute
- ➕ New practice problems
- 🐛 Bug fixes
- 📝 Documentation improvements
- 💡 New examples and use cases
- 🎨 Better explanations
- 🔧 Code optimizations

## 🌟 Show Your Support

If you find this repository helpful:
- ⭐ **Star** this repository
- 🍴 **Fork** it for your own learning
- 📢 **Share** it with others
- 💬 **Provide feedback** via issues

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 📧 Contact

**Your Name**
- 📧 Email: parulpal7088@gmail.com.com
- 💼 LinkedIn:https://www.linkedin.com/in/parul-pal-145ba1306/
- 🐱 GitHub:https://github.com/parul1806-byte


## 🙏 Acknowledgments

- Thanks to the pandas development team for this amazing library
- Inspired by various data science communities
- Special thanks to all contributors

## 📈 Learning Journey

This repository is part of my ongoing Data Science journey. Follow my progress:
- **Started:** November 2025
- **Current Focus:** Data Manipulation & Cleaning
- **Next Milestone:** Complete 100 practice problems
- **Goal:** Master pandas for real-world data analysis

---

## 📊 Repository Stats

![GitHub stars](https://img.shields.io/github/stars/yourusername/pandas?style=social)
![GitHub forks](https://img.shields.io/github/forks/yourusername/pandas?style=social)
![GitHub watchers](https://img.shields.io/github/watchers/yourusername/pandas?style=social)

---

<div align="center">

### 🚀 Happy Learning! Keep Coding! 🐼

**Made with ❤️ and lots of ☕**

</div>
