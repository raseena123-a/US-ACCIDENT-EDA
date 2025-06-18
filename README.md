# US-ACCIDENT-EDA
This project performs Exploratory Data Analysis (EDA) on a large dataset of US road accidents (2016–2023) sourced from Kaggle. It uncovers patterns in accident severity, time, weather, and location using visualizations and summary statistics.
## 📌 Objectives

- Understand accident patterns across different US states and cities
- Analyze accident severity distribution and its correlation with conditions
- Examine the impact of time of day, weather, and road features on accidents
- Identify trends over years and generate meaningful visual insights

## 📊 Dataset

- **Source**: [Kaggle – US Accidents (Sobhan Moosavi)](https://www.kaggle.com/datasets/sobhanmoosavi/us-accidents)
- **Size**: ~7.7 million records, 50+ features
- **Time Period**: 2016 to 2023

## 📈 Key Techniques

- Data Cleaning and Preprocessing
- Univariate, Bivariate & Multivariate Analysis
- Feature Engineering (e.g., datetime extraction, weather-visibility merge)
- Visualizations using `Matplotlib` and `Seaborn`

## 🔍 Sample Questions Explored

- Which states and cities report the highest number of accidents?
- What are the most common severity levels and weather conditions?
- Do more accidents happen during the day or at night?
- How has the number of accidents changed over the years?
- Is there any relationship between temperature, visibility, and severity?

## 📂 Project Structure

- `us_accident.ipynb` – Main analysis notebook
- `README.md` – Project overview
- `reduced_us_accidents.csv` – Optional: cleaned and reduced dataset (if applicable)

## 🛠️ Requirements

```bash
pandas
numpy
matplotlib
seaborn
