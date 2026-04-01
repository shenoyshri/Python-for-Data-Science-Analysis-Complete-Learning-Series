# 🐍 Python for Data Science & Analysis — Complete Learning Series

A structured, end-to-end collection of Jupyter Notebooks covering Python from fundamentals to data visualization. This project is designed as a **progressive learning series** — each notebook builds on the previous one, taking you from core Python programming all the way through NumPy, Pandas, and Matplotlib/Seaborn visualizations.

> Built by a practicing Data Analyst as a hands-on reference and portfolio project.

---

## 📁 Project Structure

```
📦 Python-Data-Science
 ┣ 📓 Python_4_Data_Science_and_Analysis.ipynb   ← Start here: Python Fundamentals
 ┣ 📓 NumPy_programs.ipynb                        ← Numerical Computing with NumPy
 ┣ 📓 Pandas_programs.ipynb                       ← Data Manipulation with Pandas
 ┣ 📓 Matplotlib_programs.ipynb                   ← Data Visualization (Matplotlib + Seaborn)
 ┣ 📓 python-advanced.ipynb                       ← Advanced NumPy + Real-world Analysis
 ┗ 📄 README.md
```

---

## 🗺️ Learning Path

```
[1] Python Fundamentals
        ↓
[2] NumPy — Arrays & Numerical Operations
        ↓
[3] Pandas — Data Manipulation & Cleaning
        ↓
[4] Matplotlib & Seaborn — Visualization
        ↓
[5] Advanced Python — Putting it all together
```

---

## 📋 Table of Contents

- [Notebooks Overview](#notebooks-overview)
- [Topics at a Glance](#topics-at-a-glance)
- [Prerequisites](#prerequisites)
- [Getting Started](#getting-started)
- [Key Concepts & Code Snippets](#key-concepts--code-snippets)
- [Datasets Used](#datasets-used)
- [Author](#author)

---

## Notebooks Overview

### 📓 1. Python Fundamentals (`Python_4_Data_Science_and_Analysis.ipynb`)
The foundation. Covers all core Python concepts required before moving to any data library.

| Topic | Description |
|-------|-------------|
| OOP – Classes & Objects | `__init__`, methods, object instantiation |
| Variables & Data Types | Strings, integers, floats, type casting, f-strings |
| User Input | Taking and processing input with `input()` |
| Variable Swapping | Temp variable swap vs. Pythonic tuple unpacking |
| Loops | `for`, `while`, nested loops, `break`, `continue` |
| Pattern Printing | Triangle and number patterns using nested loops |
| String Methods | `.split()`, `.casefold()`, `.find()`, `len()`, slicing |
| Lists & Iteration | Indexing, slicing, iteration with `range()` |
| Dictionaries | Nested dicts, sorting by keys/values |
| Sets | `pop()`, `add()`, `copy()`, union, intersection, difference |
| Functions | Parameters, return values, `*args` |
| Recursion | Recursive sum of list, Fibonacci series |
| Built-in Modules | `datetime`, `random`, `math` |
| Custom Modules | Creating and importing user-defined modules |
| Memory & Singletons | Python object caching, `id()`, singleton behavior |

---

### 📓 2. NumPy (`NumPy_programs.ipynb`)
Numerical computing foundation — essential for fast array operations and feeding data into Pandas and ML models.

| Topic | Description |
|-------|-------------|
| Array Creation | 1D and 2D arrays using `np.array()` |
| Array Slicing | Step slicing, reverse, 2D sub-array extraction |
| Array Properties | `shape`, `size`, `ndim`, `len()`, `dtype` |
| Data Type Conversion | `astype(float)`, `astype(str)` |
| Arithmetic Operations | Element-wise add, subtract, multiply, divide |
| Math Functions | `np.pow()`, `np.sqrt()` |
| Array Concatenation | `np.concatenate()` |

---

### 📓 3. Pandas (`Pandas_programs.ipynb`)
The workhorse of Data Analysis — load, clean, transform, and aggregate real-world datasets.

| Topic | Description |
|-------|-------------|
| Data Loading | `pd.read_csv()`, `pd.read_excel()`, dict to DataFrame |
| Data Exploration | `shape`, `info()`, `describe()`, `head()`, `tail()` |
| Null Value Handling | `isnull()`, `dropna()`, `fillna()`, `bfill()`, `ffill()` |
| Duplicate Detection | `duplicated().sum()` |
| Column Transformation | Conditional columns with `loc[]`, derived columns |
| String Operations | `.str.upper()`, `.map()` with custom functions |
| Value Counts | `value_counts()` on single and multiple columns |
| GroupBy & Aggregation | `groupby().agg()` — sum, mean, max, min, count |
| Merging DataFrames | Left join, right join with `pd.merge()` |
| Concatenation | `pd.concat()` for stacking DataFrames |
| Comparing DataFrames | `df.compare()` with `keep_shape`, `keep_equal` |
| Pivot & Melt | Wide-to-long and long-to-wide reshaping |

---

### 📓 4. Matplotlib & Seaborn (`Matplotlib_programs.ipynb`)
Turning raw data into visual stories — from simple scatter plots to heatmaps on real datasets.

| Chart Type | Library | Description |
|------------|---------|-------------|
| Scatter Plot | Matplotlib | Random data with color maps; Salary vs. Employee ID |
| Pie Chart | Matplotlib | Brand market share; Salary distribution by Country |
| Box Plot | Matplotlib | Single and multiple distributions; Salary outlier detection |
| Histogram | Matplotlib | Custom bins; Salary distribution by Department |
| Line Plot | Seaborn | Days vs. No. of Patients; Business Unit vs. Age by Ethnicity |
| Bar Plot | Seaborn | Country vs. Bonus % |
| Histogram + KDE | Seaborn | Business Unit by Gender; Titanic age by passenger type |
| Scatter Plot | Seaborn | Tips dataset — total bill vs. tip with day/size encoding |
| Heatmap | Seaborn | Average tip amount by day of the week |

---

### 📓 5. Advanced Python (`python-advanced.ipynb`)
Integrates NumPy, Pandas, Matplotlib, and Seaborn together — the way they are used in real Data Analysis projects.

| Topic | Description |
|-------|-------------|
| Library Integration | NumPy + Pandas + Matplotlib + Seaborn in a single workflow |
| Real Dataset | Seaborn's built-in `tips` dataset (244 rows, 7 columns) |
| NumPy Reshaping | `np.reshape()` — converting 1D range to 2D matrix |
| Array Filling | `np.full()` — create arrays filled with a constant value |
| Matrix Arithmetic | Element-wise operations on multi-dimensional arrays |

---

## Topics at a Glance

```
Python Fundamentals → OOP, Loops, Functions, Recursion, Modules
       ↓
NumPy              → Arrays, Slicing, Properties, Math Ops
       ↓
Pandas             → Load, Clean, Transform, Group, Merge, Pivot
       ↓
Matplotlib/Seaborn → Scatter, Pie, Box, Histogram, Line, Bar, Heatmap
       ↓
Advanced           → Multi-library workflow, Real datasets, Reshaping
```

---

## Prerequisites

- Python 3.x
- Jupyter Notebook or JupyterLab

Install all dependencies at once:

```bash
pip install numpy pandas matplotlib seaborn openpyxl jupyter
```

---

## Getting Started

1. **Clone the repository:**
   ```bash
   git clone https://github.com/shenoy-GitHub/<repo-name>.git
   cd <repo-name>
   ```

2. **Install dependencies:**
   ```bash
   pip install numpy pandas matplotlib seaborn openpyxl jupyter
   ```

3. **Launch Jupyter Notebook:**
   ```bash
   jupyter notebook
   ```

4. **Follow the learning path** — open notebooks in the order listed above for the best experience.

> ⚠️ **Note:** Some notebooks reference local Excel/CSV file paths (e.g., `D:/DataAnalytics/...`). Update these paths to match your local dataset location, or place the dataset files in the same folder as the notebook.

---

## Key Concepts & Code Snippets

### 🔹 Python — Fibonacci (Recursion)
```python
def fibs(num):
    if num == 1:
        return 0
    elif num == 2:
        return 1
    else:
        return fibs(num - 1) + fibs(num - 2)
```

### 🔹 NumPy — Array Properties & Slicing
```python
a = np.array([[10,20,30,40], [50,60,70,80], [20,40,60,80]])
print(a.shape)    # (3, 4) — 3 rows, 4 columns
print(a[::-1])    # Reversed array
print(a[0:2,0:2]) # 2D sub-array
```

### 🔹 Pandas — GroupBy Aggregation
```python
gp = df.groupby(["Department", "Gender"]).agg({
    "Annual Salary": "sum",
    "Age": "min"
})
```

### 🔹 Pandas — Null Value Handling
```python
data["Salary"] = data["Salary"].replace(np.nan, data["Salary"].mean())
print(data.ffill())   # Forward fill
print(data.bfill())   # Backward fill
```

### 🔹 Matplotlib — Scatter Plot with Color Map
```python
x = np.random.randint(0, 50, 50)
y = np.random.randint(0, 100, 50)
color = np.random.randint(10, 100, 50)
plt.scatter(x, y, marker="*", cmap="hot", c=color)
plt.colorbar()
plt.show()
```

### 🔹 Seaborn — Heatmap on Real Data
```python
data = sns.load_dataset("tips")
gp = data.groupby("day").agg({"tip": "mean"})
sns.heatmap(gp)
plt.show()
```

### 🔹 Advanced — NumPy Reshape + Full Library Workflow
```python
# Reshape 1D to 2D matrix
mat1 = np.reshape(range(16), (4, 4))

# Create constant-filled matrix
mat_x = np.full((4, 5), 2)

# Matrix arithmetic
a = np.array([[10,20,30,1],[1,4,10,8],[6,4,8,7]])
b = np.array([[5,4,6,4],[7,6,8,2],[5,8,1,3]])
print(a + b)
print(a * b)
print(a / b)
```

---

## Datasets Used

| Dataset | Format | Used In | Purpose |
|---------|--------|---------|---------|
| `ESD.xlsx` | Excel | Pandas, Matplotlib | Employee salary, age, department, bonus analysis |
| `company.csv` / `company1.xlsx` | CSV/Excel | Pandas | Duplicate detection, null handling |
| `loan_data_excel.xlsx` | Excel | Pandas | Data exploration and profiling |
| `Employees.csv` | CSV | Pandas | String operations, Full Name creation |
| `practice_1.xlsx` | Excel | Pandas | Bonus calculation |
| `tips` (Seaborn built-in) | — | Advanced, Matplotlib | Bill vs. tip analysis, scatter/heatmap |
| `titanic` (Seaborn built-in) | — | Matplotlib | Age distribution by passenger type |
| Inline dictionaries | — | All notebooks | Quick demonstrations |

---

## Author

**Srikanth Shenoy**
Data Analyst skilled in SQL, Python, Power BI, and Tableau

- 🔗 [GitHub](https://github.com/shenoy-GitHub)
- 🔗 [LinkedIn](https://www.linkedin.com/in/srikanth-shenoy)
- 🌐 [Portfolio](https://shenoyshri.github.io/index.html)

---

## 📌 Quick Reference — Where to Start

| If you are... | Start with... |
|---------------|---------------|
| New to Python | `Python_4_Data_Science_and_Analysis.ipynb` |
| Learning NumPy | `NumPy_programs.ipynb` |
| Learning data wrangling | `Pandas_programs.ipynb` |
| Learning visualization | `Matplotlib_programs.ipynb` |
| Reviewing everything together | `python-advanced.ipynb` |

---

> 💡 **Pro Tip:** Run each notebook cell-by-cell rather than all at once. Many cells use `input()` for interactive exercises, and understanding the output of each cell independently builds stronger intuition for Data Analysis workflows.
