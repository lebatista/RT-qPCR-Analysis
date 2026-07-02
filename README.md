# RT-qPCR Data Analysis Pipeline

## Overview

This project presents a reproducible analysis workflow for RT-qPCR (quantitative real-time PCR) data. The notebook demonstrates data processing, normalization, statistical evaluation, and visualization of gene expression measurements.

The workflow is implemented in Python and focuses on ensuring transparent, structured, and reproducible analysis of experimental qPCR datasets.

---

## Objectives

- Process raw RT-qPCR Ct values
- Perform data normalization using reference genes
- Calculate relative gene expression (ΔCt / ΔΔCt methods)
- Evaluate experimental variability and data quality
- Generate publication-ready visualizations

---

## Methods

The analysis includes:

- Data preprocessing and structuring of Ct values
- Normalization against housekeeping genes
- Relative quantification using ΔΔCt method
- Basic statistical evaluation of expression differences
- Visualization of gene expression results using matplotlib / seaborn

---

## Tools & Libraries

- Python (pandas, numpy)
- matplotlib / seaborn
- Jupyter Notebook
- Statistical analysis in Python

---

## Key Features

- Reproducible workflow for RT-qPCR analysis
- Structured data handling and normalization pipeline
- Clear visualization of gene expression differences
- Transparent step-by-step analytical process

---

## Context & Relevance

RT-qPCR is widely used in molecular biology and diagnostic development for gene expression quantification and biomarker validation.

This analysis workflow reflects core tasks in:
- diagnostic assay evaluation (e.g. V&V studies)
- translational research environments
- molecular data quality assessment

---

## File Structure

- `qPCR_analysis_LB_20240328.ipynb` → main analysis notebook

---

## Notes

This project is intended as a reproducible demonstration of RT-qPCR data analysis workflows and does not rely on proprietary datasets.
