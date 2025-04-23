# EOCRC and LOCRC Dashboard: Investigating Disparities in Early-Onset Colorectal Cancer

This repository contains the source code for an interactive dashboard that visualizes and explores disparities in **early-onset colorectal cancer (EOCRC)** and **late-onset colorectal cancer (LOCRC)**, based on SEER data collected between 2018 and 2021.

## 📊 Interactive Dashboard


Access the live dashboard here:
👉 https://ramya-rajendran-at-emory-edu.github.io/eocrc_and_locrc_dashboard/

🔗 Access the full GitHub repository here, which includes the project’s source code, README.md, rendered HTML dashboard, and all associated R Markdown (.Rmd) files:
👉 https://github.com/ramya-rajendran-at-emory-edu/eocrc_and_locrc_dashboard/


## 📁 Repository Structure

- `final_project_dashboard.Rmd` – Source code written in R Markdown  
- `final_project_dashboard.html` – Rendered dashboard (deployed via GitHub Pages)  
- `index.html` – Copied version of the HTML dashboard for GitHub Pages deployment (loads by default at project URL)
- `README.md` – Project overview and usage instructions
- `.gitignore` – Specifies files and folders to exclude from version control (e.g., .Rhistory, .RData, .Rproj.user/)

## 🔍 Project Overview

Developed as part of a Master of Public Health (MPH) Epidemiology final project, this dashboard analyzes disparities in colorectal cancer diagnoses based on clinical, demographic, and socioeconomic variables.

Key research objectives:
- Examine how **age, sex, race/ethnicity**, and **income** influence EOCRC vs. LOCRC diagnoses
- Assess disparities across **urban vs. rural residence** and **clinical staging**
- Highlight racial and socioeconomic differences in cancer incidence and diagnostic patterns

## 🌍 Importance & Real-World Impact
This dashboard highlights how socioeconomic status, demographic characteristics, and geographic location contribute to disparities in colorectal cancer outcomes, particularly in early detection and diagnosis. It also offers data-driven insights to support public health interventions and policy strategies aimed at reducing disparities and promoting early screening for improved population health.

## 🛠 Technologies Used

- **Programming:** R (v4.3+)
- **Libraries:** `plotly`, `DT`, `dplyr`, `readr`, `flexdashboard`
- **Reporting:** R Markdown
- **Deployment:** GitHub Pages

## 🧾 Rendering the Dashboard to Static HTML

To run the dashboard locally in RStudio:

```r
# Generate a static HTML version of the dashboard in the current working directory
rmarkdown::render(
  input = "final_project_4a_final_dashboard_and_github_pages_deployment.Rmd", 
  output_file = "final_project_4a_final_dashboard_and_github_pages_deployment.html", 
  output_dir = "."  # Output will be saved in the same folder as the Rmd
)
```

