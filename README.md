# 📊 COVID-19 Data Analysis with Python

This project is a Jupyter Notebook-based interactive report that allows users to explore COVID-19 data for any country of their choice. It includes total cases, deaths, vaccinations, and estimated recoveries. The graphs are automatically cleaned to remove misleading data from years when COVID-19 was no longer active.

---

## 🎯 Objectives

- To load and clean global COVID-19 data from [Our World in Data](https://ourworldindata.org/coronavirus-source-data)
- To enable user input to view COVID-19 trends for a specific country
- To visualize total cases, deaths, vaccinations, and death rate over time
- To remove inactive data after COVID-19 reporting stopped (making graphs more realistic)
- To calculate and display a summary of total infections, deaths, vaccinations, and recoveries

---

## 🛠️ Tools & Libraries Used

- **Python** 🐍
- **Pandas** – for data handling and cleaning
- **Matplotlib** – for plotting graphs
- **Seaborn** – for styling plots
- **Jupyter Notebook** – for interactive data analysis and presentation

---

## 🚀 How to Run This Project

1. Make sure you have **Python** and **Jupyter Notebook** installed.
2. Clone this repository or download the `.ipynb` file.
3. Open the notebook in Jupyter Lab or Jupyter Notebook.
4. Run all cells (Shift + Enter).
5. When prompted, enter the name of the country (e.g., `Rwanda`, `Kenya`, `India`).

---

## 📌 Features

- ✅ User can input any country name to analyze.
- ✅ Graphs only show active COVID years (drops to 0 when data stops).
- ✅ Calculates total cases, deaths, vaccinations, estimated recoveries, and death rate.
- ✅ Beautiful and clean visualizations.
- ✅ Clear narrative for anyone to understand.

---

## 💡 Insights & Reflections

- Most countries stopped reporting COVID-19 data by late 2022.
- Cumulative data like `total_cases` can be misleading if not trimmed — this project resets values to 0 after the last known active report.
- Death rates varied widely, especially in early phases of the pandemic.
- Vaccination rollout speed was significantly different across continents.

---

## 📂 Author

Made with ❤️ by Mahoro Belyse using Python and Jupyter.
