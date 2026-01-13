# MIMIC-III-Antibiotic-Usage-Analysis.
# Analysis of Critical Care Medication Usage (MIMIC-III)

---

## Project Overview
As a final-year **Doctor of Pharmacy (Pharm D)** student, I recognize that clinical decisions must be driven by data. While standard textbooks provide theoretical guidelines, I wanted to investigate how high-alert medications are utilized in a high-volume, real-world Intensive Care Unit (ICU).

This project utilizes **Python** to analyze the **MIMIC-III Clinical Database** (Beth Israel Deaconess Medical Center, MIT). The objective was to move beyond manual chart review and programmatically identify medication trends across thousands of patient records.

## Methodology
The analysis was conducted using a custom Python script that simulates a **Drug Utilization Review (DUR)** on a large scale.

1.  **Data Ingestion:** Processed raw clinical logs (`PRESCRIPTIONS.csv` and `ADMISSIONS.csv`) containing real-world medication orders.
2.  **Data Cleaning:** Implemented logic to standardize inconsistent drug nomenclatures (e.g., correcting capitalization errors) to ensure accurate statistical counting.
3.  **Utilization Analysis:** Developed an algorithm to rank medications by frequency, identifying the top administered agents in the ICU.
4.  **Outcome Linking:** Merged prescription datasets with patient discharge summaries (using `HADM_ID`) to create a unified cohort for analyzing the relationship between medication use and survival outcomes.

## Key Findings
The analysis identified **Potassium Chloride (KCL)** and **Insulin** as the highest-volume medication orders in the dataset.
* *Clinical Significance:* This finding validates the accuracy of the script. In critical care settings, precise electrolyte management and glycemic control are foundational to patient stability. The data accurately reflects standard ICU protocols.

## Technical Stack
 **Language:** Python 3.10
 **Libraries:** Pandas (Data Logic), Seaborn (Visualization)
 **Data Source:** MIMIC-III Clinical Database Demo

---

## Author
**Umar Taimur Tahir**
*Pharm D Candidate | Clinical Data Enthusiast*
Focused on leveraging data science to improve antimicrobial stewardship (AMR) and patient safety outcomes.
