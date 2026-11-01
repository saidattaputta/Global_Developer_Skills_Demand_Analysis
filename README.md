# Global Developer Skills Demand Analysis

An analysis of the **2024 Stack Overflow Developer Survey** exploring developer technologies, programming-language preferences, databases, platforms, web frameworks, and respondent demographics. The project combines data collection, cleaning, analysis, and dashboard/report deliverables.

## Objective

Summarize technology adoption and developer preferences from survey responses, and translate the findings into accessible charts and dashboard views for developers, technical leaders, and workforce-planning discussions.

## Data Source

[Stack Overflow Developer Survey 2024](https://survey.stackoverflow.co/2024/)

The original project documentation describes a survey with 65,000+ responses from 185 countries. Check the survey's official methodology and filtered response counts before comparing the project's figures with other analyses.

## Analysis Components

- **Data collection:** API-based job/technology data collection exercises and source preparation.
- **Data wrangling:** cleaning and preparing survey responses for analysis.
- **Data visualization:** technology usage, desired technologies, platform/database preferences, and demographic views.
- **Dashboard/report:** PDF dashboard and written report deliverables.

## Deliverables

- [Project report](Project_Report.pdf)
- [Dashboard export](Dashboard.pdf)
- [Data collection notebook](Data_Collection.ipynb)
- [Data wrangling notebook](Data_Wrangling.ipynb)
- [Data visualization notebook](Data_Visualization.ipynb)

Dashboard and report images are also included in the repository.

## Tools

Python, pandas, NumPy, Matplotlib, Seaborn, Requests, Beautiful Soup, SQLite, Excel, and Google Looker Studio.

## Repository Contents

The repository contains notebooks, report/dashboard PDFs, exported images, and ZIP archives of selected outputs. The original lowercase `readme.md` has been preserved; GitHub uses this uppercase `README.md` as the repository landing-page documentation.

## Run Locally

```bash
git clone https://github.com/saidattaputta/Global_Developer_Skills_Demand_Analysis.git
cd Global_Developer_Skills_Demand_Analysis
python -m venv .venv
source .venv/bin/activate  # Windows: .venv\\Scripts\\activate
pip install pandas numpy matplotlib seaborn requests beautifulsoup4 openpyxl jupyter
jupyter notebook
```

Open the notebooks from the repository root. Some collection and wrangling steps refer to external URLs or Kaggle-style input paths and may require adapting to the available source files and credentials.

## Interpretation Notes

- Survey responses are self-reported and do not constitute a census of all developers.
- Usage, desire, and preference are different measures and should not be conflated.
- Figures depend on filters, missing-value handling, and the survey question's response options.
- Refresh the data and analysis before using the findings as current market guidance.

---

**Sai Datta Putta**

[LinkedIn](https://www.linkedin.com/in/sai-datta-putta/)