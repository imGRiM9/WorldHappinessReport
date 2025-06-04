# World Happiness Report - Exploratory Data Analysis & Insights

This repository contains an exploratory data analysis (EDA) and insights derived from the World Happiness Report dataset. The project aims to uncover patterns, understand key factors influencing happiness scores across different countries and regions, and visualize these findings.

## 📊 Project Overview

The World Happiness Report is an annual survey by the United Nations Sustainable Development Solutions Network. It ranks countries by how happy their citizens perceive themselves to be. This analysis delves into the dataset to explore:

* The happiest countries and their scores.
* The relationship between economic indicators (like GDP per capita) and happiness.
* Regional differences in happiness metrics and contributing factors.
* The influence of factors such as social support, healthy life expectancy, freedom, generosity, and perceptions of corruption on national happiness levels.

## 💾 Dataset

The primary dataset used for this analysis is the World Happiness Report.
* **Source:** : Wlv.Canvas 
* **Key Metrics Explored:** Happiness Score, GDP per Capita, Social Support, Healthy Life Expectancy, Freedom to make life choices, Generosity, Perceptions of Corruption.

## 🛠️ Tools and Libraries

* **Python:** Primary programming language.
* **Pandas:** For data manipulation and analysis.
* **NumPy:** For numerical operations.
* **Matplotlib & Seaborn:** For data visualization.
* **Jupyter Notebook/Lab:** For interactive analysis and presentation.

## 📈 Key Analyses and Visualizations

This project includes several key analyses, visualized through various plots:

### 1. Top Happiest Countries
A bar chart showcasing the countries with the highest happiness scores, providing a quick view of global leaders in well-being.
![Screenshot 2025-06-04 224644](https://github.com/user-attachments/assets/07625c89-58a3-4182-bd78-dbfa7dd21428)

### 2. GDP per Capita vs. Happiness Score
A scatter plot illustrating the relationship between a country's economic output (GDP per Capita) and its national happiness score. Points are categorized by happiness levels (High, Medium, Low) to better understand the correlation.
![Screenshot 2025-06-04 224711](https://github.com/user-attachments/assets/cf34a624-4639-4408-a45f-06728a4c0617)


### 3. Regional Metric Comparisons
A grouped bar chart comparing key metrics such as Log GDP per capita, Social Support, and Healthy Life Expectancy between different regions (e.g., South Asia and the Middle East). This helps in understanding regional disparities and strengths.
![Screenshot 2025-06-04 224824](https://github.com/user-attachments/assets/e4e06006-fe7b-4d15-9c39-066f7ec4c47c)


## 🚀 How to Run

1.  **Clone the repository:**
    ```bash
    git clone https://github.com/imGRiM9/WorldHappinessReport.git![Screenshot 2025-06-04 224711](https://github.com/user-attachments/assets/69a76c36-c7bf-4865-9a42-4efb55bdbcd6)

    cd [repository-name]
    ```

2.  **Create a virtual environment (recommended):**
    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows: venv\Scripts\activate
    ```

3.  **Install dependencies:**
    ```bash
    pip install pandas numpy matplotlib seaborn jupyterlab
    ```
    *(Consider adding a `requirements.txt` file for easier dependency management: `pip freeze > requirements.txt`)*

4.  **Download the dataset:**
    Ensure you have the dataset file (e.g., `[dataset-filename.csv]`) in the `data/` directory (or update the path in the notebook).

5.  **Launch Jupyter Lab:**
    ```bash
    jupyter lab
    ```
    Then open the `[notebook-name.ipynb]` notebook and run the cells.

## 📋 Key Findings (Summary)

* Nordic countries consistently dominate the top ranks of happiness.
* There is a strong positive correlation between GDP per capita and happiness scores, although with diminishing returns at very high GDP levels.
* Significant regional variations exist in both overall happiness and the factors that contribute to it, with the Middle East, for example, showing higher average GDP per capita and Social Support compared to South Asia in this snapshot.

## 🌟 Future Work

* Time series analysis to observe trends in happiness scores for specific countries or regions over multiple years.
* Predictive modeling to estimate happiness scores based on various socio-economic factors.
* In-depth analysis of outliers or specific country case studies.

