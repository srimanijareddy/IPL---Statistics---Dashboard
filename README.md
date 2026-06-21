# 🏏 IPL Statistics Analytics Dashboard

## Overview

The IPL Statistics Analytics Dashboard is a data analysis project built using Python and data visualization libraries. The project analyzes IPL match data stored in CSV format and presents meaningful insights through charts and visual reports.

This project helps users understand player performance, bowling statistics, team records, venue trends, and season-wise performance across multiple IPL seasons through a static dashboard interface.
---

## Features

* Top 10 Run Scorers Analysis
* Top 10 Wicket Takers Analysis
* Team Wins Analysis
* Venue Analysis
* Season-wise Analysis
* Static Dashboard Interface
* Data Visualization using Charts
* Processed Output Data Exported as JSON Files

---

## Technologies Used

### Programming Language

* Python

### Libraries

* NumPy
* Pandas
* Matplotlib
* Seaborn

### Frontend

* HTML
* CSS

### Data Format

* CSV Dataset
* JSON Output Files

---

## Dataset

The project uses IPL data stored in CSV files containing:

* Match Information
* Team Information
* Player Statistics
* Venue Details
* Season Details
* Bowling Statistics
* Batting Statistics

The analysis results can be exported as JSON files and stored in the `outputs/` folder. These files are currently not used by the static dashboard but are intended for future integration with JavaScript to build an interactive dashboard.

Dataset not included in this repository due to file size limitations.

---

## Project Structure

```text
IPL-Statistics-Dashboard/
│
├── data/
│   └── *.csv
│
├── outputs/
│   └── *.json
│
├── notebooks/
│   └── analysis.ipynb
│
├── charts/
│   ├── top_runs.png
│   ├── top_wickets.png
│   ├── team_wins.png
│   ├── venue_analysis.png
│   └── season_analysis.png
│
├── frontend/
│   ├── index.html
│   └── style.css
│
├── requirements.txt
│
└── README.md
```

### Folder Description

* **data/** → Contains the IPL CSV datasets used for analysis.
* **outputs/** → Contains JSON files generated from the analysis. These files are reserved for future use when adding JavaScript-based interactivity to the dashboard.
* **notebooks/** → Jupyter notebooks for data cleaning, processing, and analysis.
* **charts/** → Stores visualization images generated during analysis.
* **frontend/** → Contains the dashboard UI files (HTML and CSS).
* **requirements.txt** → Lists all Python dependencies required to run the project.
* **README.md** → Project documentation.

---

## Visualizations

The dashboard includes:

1. Top Run Scorers
2. Top Wicket Takers
3. Team Wins Analysis
4. Venue Analysis
5. Season-wise Performance Trends

---

## How to Run

1. Clone the repository.

2. Download the dataset from kaggle and place it inside the Data/ folder

3. Install the required libraries:

```bash
pip install pandas numpy matplotlib seaborn
```

3. Run the analysis notebook:

```text
notebooks/analysis.ipynb
```

This will process the CSV dataset, generate visualization charts, and optionally export JSON output files to the `outputs/` folder.

4. Open the dashboard:

```text
frontend/index.html
```

in your browser to view the dashboard.

---

## Future Improvements

* Interactive Dashboard using JavaScript
* Integration of JSON Output Files for Dynamic Data Loading
* Player Search Functionality
* Team-wise Detailed Analysis
* Season Filters
* Advanced Batting Statistics
* Advanced Bowling Statistics
* Additional Visualizations and Insights

---

## Author

**Sri Manija Mummadi**

B.Tech Information Technology

NIT Raipur
