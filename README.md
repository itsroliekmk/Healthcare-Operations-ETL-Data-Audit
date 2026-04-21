# 🏥 Healthcare Operations & Clinical Data Audit

## 📌 Project Overview
This project focuses on the end-to-end cleaning and auditing of hospital operational data. Using Python, I transformed a high-entropy clinical dataset into a "Gold Standard" asset optimized for hospital resource planning and revenue modeling.

## 🛠️ Problems Solved
* **Clinical Normalization:** Unified misspelled diagnoses (e.g., `Hypertensoin` → `Hypertension`) to ensure reporting accuracy.
* **Logic-Based Auditing:** Identified records where Discharge occurred before Admission, flagging them for administrative review.
* **Financial ETL:** Standardized mixed-currency strings (₦, NGN, N) and text-based entries ("Free") into clean numeric floats.
* **KPI Engineering:** Automated the calculation of **Length of Stay (LOS)** for bed-occupancy analysis.

## 🧰 Tech Stack
* **Language:** Python 3.x
* **Libraries:** Pandas, NumPy, Unicodedata

## 📂 Deliverables
* `Healthcare-Operations-Clean.csv`: The finalized, audit-ready dataset.
