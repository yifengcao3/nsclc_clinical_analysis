# Clinical Trial Landscape Analysis in NSCLC
[![View Analysis Report](https://img.shields.io/badge/View-Analysis%20Report-blue?style=for-the-badge&logo=appveyor)](https://htmlpreview.github.io/?https://github.com/yifengcao3/nsclc_clinical_analysis/blob/main/docs/index.html)
> **A reproducible R-based project analyzing trends in innovative clinical trial designs for non-small cell lung cancer (NSCLC) from 2010 to 2026.**

This project investigates how modern clinical trial methodologies—including Bayesian adaptive designs and master protocols—have evolved in NSCLC clinical research. By integrating data from the ClinicalTrials.gov AACT database with public genomic resources (TCGA), the project explores both methodological trends and their biological rationale.
     
---

## Project Goals

* **Quantify** the adoption of Bayesian adaptive designs and master protocols over time.
* **Compare** innovative and conventional trial designs using clinical trial outcomes.
* **Integrate** TCGA biomarker data (e.g., *EGFR*, *KRAS*) to illustrate the biological rationale for precision-oriented clinical trial designs.
* **Maintain** a fully reproducible statistical analysis workflow using R and Quarto.

## Data Sources

* **ClinicalTrials.gov AACT**: Clinical trial registry data.
* **TCGA / GDC**: Public genomic and biomarker datasets.

## Repository Structure

```text
.
├── GDCdata/           # Raw and processed datasets
├── figures/           # Generated plots and visualizations
├── docs/              # Project proposal and documentation
├── analysis.qmd       # Main Quarto analysis file
├── _quarto.yml        # Quarto project configuration
└── README.md          # Project overview
