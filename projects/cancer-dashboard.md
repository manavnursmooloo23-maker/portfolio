# 📈 Cancer Prevalence Dashboard (Victorian Cancer Registry)

## 🔍 Project Overview
This project involved designing and developing the Cancer Prevalence tab from scratch for the Cancer Council Victoria Data Explorer, using real-world data from the Victorian Cancer Registry (VCR).

The objective was to build a public-facing, interactive Power BI dashboard that enables clinicians, researchers, policymakers, and the general public to explore cancer prevalence trends in a clear, intuitive, and accessible way.

---

## 🎯 Objectives

- Analyse cancer prevalence trends over time
- Build an interactive and user-friendly dashboard
- Ensure compliance with data privacy and governance requirements

---

## 🛠 Tools & Technologies

- Power BI
- R (data processing and validation)
- Excel (data preparation)

---
## 📊 Sample Data Description

The data used in this project is based on cancer prevalence data from the Victorian Cancer Registry (VCR). It represents the number of people living with a cancer diagnosis at a given point in time.

The dataset includes:

* **Timepoints** – Year-based snapshots of prevalence
* **Prevalence window (LastXYears)** – Represents people diagnosed within a selected period (e.g. 1, 5, 10, 20 years) who are still alive
* **Sex** – Male, Female, and Persons
* **Age groups** – (e.g. 0–24, 25–49, 50–69, 70–79, 80+)
* **Cancer types** – Grouped into main, sub, and detailed tumour categories
* **Geographical and socio-economic groupings** – Including remoteness, SEIFA, and Integrated Cancer Services regions

Each timepoint represents a complete snapshot for the selected prevalence window. Therefore, values should not be aggregated across multiple timepoints.

For visualisation purposes, the “Persons” category is excluded in certain calculations to avoid double counting, as it already represents the combined total of males and females.

---

## 📊 Key Dataset Labels

### 🟨 Core Time Variables

* **TimePoints** – Year of data snapshot
* **LastXYears** – Prevalence window (e.g. 1, 5, 10, 20 years)

### 🟩 Demographic Variables

* **Sex** – Male, Female, Persons
* **timepoint_ageg** – Age group classification

### 🟦 Cancer Classification

* **TUMOUR_GROUP_ID** – Unique cancer identifier
* **tumourgroup_main** – Main category (e.g. breast, lung)
* **tumourgroup_sub** – Sub-category
* **tumourgroup_detail** – Detailed classification

### 🟪 Prevalence Measures

* **Total_Prevalence** – Number of people living with cancer
* **Perc_of_Vic_pop_within_age_group** – Percentage within age group

### 🟫 Disparity Variables

* **SEIFA** – Socio-economic grouping
* **Remoteness / Region** – Geographic classification
* **Integrated Cancer Services (ICS)** – Health service regions

---

## ⚙️ Methodology

### Data Processing

- Cleaned and prepared raw datasets
- Computed prevalence counts and rates
- Validated outputs for consistency

### Data Governance

- Applied small-cell suppression rules
- Implemented rounding techniques to protect sensitive data

### Dashboard Development

- Designed interactive visuals and filters
- Created tooltips and hover features for better user understanding
- Focused on accessibility for non-technical users

---

## 📊 Key Insights

- Cancer prevalence shows a consistent upward trend over time
- Certain age groups exhibit significantly higher prevalence rates
- Visualisation improves understanding of complex healthcare data

---

## 📸 Dashboard Preview
(Add your images here later)

---

## 💡 Business Value

- Supports data-driven decision-making in healthcare
- Provides accessible insights for policymakers and researchers
- Enhances public understanding of cancer trends

---

## 🔗 Links

- GitHub Repository: (add your repo link here)
