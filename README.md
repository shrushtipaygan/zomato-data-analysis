# 🍽️ Zomato Data Analysis

Exploratory Data Analysis (EDA) of Zomato restaurant data to uncover insights about restaurant ratings, online ordering trends, table booking patterns, pricing, and dining categories across Bengaluru.

---

## 📋 Table of Contents

- [Overview](#overview)
- [Dataset](#dataset)
- [Project Structure](#project-structure)
- [Installation](#installation)
- [Usage](#usage)
- [Key Insights](#key-insights)
- [Technologies Used](#technologies-used)

---

## Overview

This project performs an in-depth exploratory data analysis on a Zomato restaurant dataset from Bengaluru. The goal is to understand restaurant trends — such as which dining types are most popular, how online ordering affects ratings, the relationship between cost and votes, and how table booking availability varies across restaurant types — through clean data processing and meaningful visualizations.

---

## Dataset

**File:** `Zomato_data_.csv`

| Column | Description |
|---|---|
| `name` | Name of the restaurant |
| `online_order` | Whether the restaurant accepts online orders (Yes/No) |
| `book_table` | Whether the restaurant allows table booking (Yes/No) |
| `rate` | Customer rating (e.g., 4.1/5) |
| `votes` | Total number of customer votes |
| `approx_cost(for two people)` | Approximate cost for two people (in INR) |
| `listed_in(type)` | Type/category of the restaurant (e.g., Buffet, Cafes, Dining, etc.) |

---

## Project Structure

```
Zomato-Data-Analysis/
│
├── Zomato_data_.csv              # Dataset
├── Zomato_Data_Analysis.ipynb    # Main Jupyter Notebook with full EDA
├── requirements.txt              # Python dependencies
└── README.md                     # Project documentation
```

---

## Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/your-username/Zomato-Data-Analysis.git
   cd Zomato-Data-Analysis
   ```

2. **Create a virtual environment (optional but recommended)**
   ```bash
   python -m venv venv
   source venv/bin/activate        # On Windows: venv\Scripts\activate
   ```

3. **Install dependencies**
   ```bash
   pip install -r requirements.txt
   ```

---

## Usage

1. Launch Jupyter Notebook:
   ```bash
   jupyter notebook
   ```

2. Open `Zomato_Data_Analysis.ipynb` and run all cells sequentially.

> **Note:** If running on Google Colab, upload `Zomato_data_.csv` to `/content/` and update the file path in the notebook accordingly.

---

## Key Insights

- 🍴 **Dining** is the most common restaurant type listed on Zomato, followed by Cafes and Buffet.
- 📱 Restaurants that **accept online orders** tend to receive more votes, indicating higher customer engagement.
- 📅 **Table booking** is relatively rare and is mostly available in higher-rated, premium restaurants.
- 💸 Most restaurants fall in the **₹300–₹800** approximate cost range for two people.
- ⭐ The majority of restaurants are rated between **3.5 and 4.2**, showing a generally positive skew in ratings.
- 🏆 Restaurants with higher vote counts tend to have more consistent and reliable ratings.

---

## Technologies Used

- **Python 3.x**
- **Pandas** – Data loading, cleaning, and manipulation
- **NumPy** – Numerical operations
- **Matplotlib** – Static data visualizations
- **Seaborn** – Statistical data visualizations
- **Jupyter Notebook** – Development and presentation environment
