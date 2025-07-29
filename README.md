# 🎬 Netflix Data Analysis Dashboard | 2025

Combining my passion for **cinema** with my growing interest in **data analytics**, this project explores and visualizes insights from a Netflix movies dataset using **Python** and **Power BI**.

---

## 📌 Table of Contents

* [📈 Objective](#-objective)
* [🧠 Key Questions Explored](#-key-questions-explored)
* [🧰 Tools & Technologies](#-tools--technologies)
* [🔍 Exploratory Data Analysis](#-exploratory-data-analysis)
* [📊 Power BI Dashboard Highlights](#-power-bi-dashboard-highlights)
* [🗂️ Folder Structure](#-folder-structure)
* [🚀 How to Run This Project](#-how-to-run-this-project)
* [📎 Learnings](#-learnings)
* [🧭 Future Improvements](#-future-improvements)
* [🧑‍💼 About Me](#-about-me)

---

## 📈 Objective

To perform **exploratory data analysis (EDA)** and create a compelling **interactive dashboard** to uncover meaningful insights about movies available on Netflix — including genre trends, popularity patterns, and annual production data — and build a recruiter-facing portfolio project.

---

## 🧠 Key Questions Explored

Here are the extracted questions from your conclusion section:
What are the Top 10 Most Popular Movies on Netflix?
What genre has the highest total vote count?
Is there any correlation between Vote Average and Popularity?
Which are the Top 5 Genres by Total Popularity?
What genre has the highest average popularity?
What does the relationship between Vote Average and Popularity look like?
What is the most frequent genre in the dataset?
What genre has the highest votes?
What movie got the highest popularity? What’s its genre?
What movie got the lowest popularity? What’s its genre?
Which year has the most filmed movies?


---

## 🧰 Tools & Technologies

| Category                           | Tools                 |
| ---------------------------------- | --------------------- |
| **Data Preprocessing**             | Python, Pandas, NumPy |
| **Data Visualization**             | Seaborn, Matplotlib   |
| **Dashboard Creation**             | Power BI              |
| **Development Environment**        | Jupyter Notebook      |
| **Data Cleaning & Transformation** | Power Query, Pandas   |
| **Version Control**                | Git & GitHub          |

---

## 🔍 Exploratory Data Analysis

The `.ipynb` Jupyter Notebook includes:

* Importing and reading raw dataset
* Checking for nulls, duplicates, and outliers
* Handling missing values
* Creating new features (e.g., release decade, title length)
* Grouping, filtering & sorting using Pandas
* Visualizations using Matplotlib & Seaborn:

  * Genre distribution
  * Popularity heatmaps
  * Time series charts by release year

📌 *Bonus struggle*: Handling inconsistent data in genres (multiple genres per movie), managing non-numeric popularity values, converting runtime formats.

---

## 📊 Power BI Dashboard Highlights

* 🎥 **Top 10 Movies by Popularity**: Bar chart sorted descending
* 🎭 **Top 5 Genres**: Donut chart with dynamic slicers
* 📅 **Year-wise Film Count**: Line chart to show trends over decades
* 🕹️ **Interactive Filters**: Year, Genre, Country
* 📋 **KPI Cards**: Total Movies, Avg Rating, Max Runtime

> 🔧 Built using **Power BI Desktop**

---

## 🗂️ Folder Structure

```
Netflix-Data-Analysis/
├── data/
│   └── netflix_movies.csv
├── notebooks/
│   └── Netflix_Data_Analysis.ipynb
├── dashboard/
│   └── Netflix_Dashboard.pbix
├── images/
│   └── dashboard_screenshot.png
├── README.md
├── LICENSE
└── requirements.txt
```

---

## 🚀 How to Run This Project

### 1. Clone this repo

```bash
git clone https://github.com/yourusername/netflix-data-analysis.git
cd netflix-data-analysis
```

### 2. Set up Python environment

```bash
pip install -r requirements.txt
```

### 3. Run the Jupyter Notebook

```bash
jupyter notebook notebooks/Netflix_Data_Analysis.ipynb
```

### 4. Open Power BI Dashboard

Open the `.pbix` file in Power BI Desktop to explore the dashboard.

---

## 📎 Learnings

* Hands-on experience with **real-world data cleaning**
* Practiced **EDA using Pandas** and **Seaborn** visualizations
* Mastered **Power BI fundamentals**: filters, slicers, visuals
* Understood the value of **data storytelling** for non-technical audiences

---

## 🧭 Future Improvements

* Integrate IMDb or TMDB API for real-time data updates
* Add sentiment analysis using movie reviews
* Deploy the dashboard online using Power BI service
* Build a Streamlit or Flask app for frontend interaction

---

## 🧑‍💼 About Me

👋 Hi, I'm **Gagan Jha** — a BCA student and aspiring **Data Scientist**.
I love combining technical skills with creative storytelling, and this project reflects my journey of exploring data using tools like **Python and Power BI**.

📫 Reach out to connect or collaborate:
[LinkedIn](https://linkedin.com/in/gagan-jha) | [Email](gkjha1495@gmail.com)

---

> ⭐ If you found this helpful or interesting, please consider giving it a star!
> 📌 Contributions, suggestions, and feedback are welcome!

