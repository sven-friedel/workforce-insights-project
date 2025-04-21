# 📘 Data Dictionary: Automotive HR Software Talent Dataset

This data dictionary provides detailed descriptions for each column in the dataset used for analyzing the HR talent landscape in an automotive software development context.

---

| **Column Name**           | **Description**                                                                 | **Data Type**    | **Example**                |
|---------------------------|---------------------------------------------------------------------------------|------------------|----------------------------|
| `Employee ID`             | Unique identifier for each employee                                             | String           | EMP0342                    |
| `Region`                  | Geographical region where the employee is based                                 | Categorical      | Europe                     |
| `Department`              | Department within the automotive software organization                          | Categorical      | Cloud Engineering          |
| `Role`                    | Job role/title in the software development track                                | Categorical      | Software Engineer          |
| `Years of Experience`     | Approximate total years of professional experience                              | Float            | 5.2                        |
| `Salary`                  | Annual salary in USD (may contain 'N/A' to reflect data quality issues)         | Numeric / String | 102000 / 'N/A'             |
| `Hire Date`               | Date when the employee was hired                                                | Date             | 2019-07-23                 |
| `Left Company`            | Indicates whether the employee has left the company                             | Boolean          | TRUE / FALSE               |
| `Attrition Reason`        | If the employee left, the reason they provided (or "Unknown")                   | Categorical      | Better Offer               |
| `Education Level`         | Highest education level attained                                                | Categorical      | Master                     |
| `Training Status`         | Status of employee in a training/upskilling program                             | Categorical      | Completed                  |
| `Hiring Channel`          | Source through which the employee was hired                                     | Categorical      | LinkedIn                   |
| `Performance Rating`      | Performance evaluation score (1 = poor, 5 = excellent)                          | Integer (1–5)    | 3                          |
| `Tenure (Years)`          | Number of years the employee has been with the company                          | Float            | 3.7                        |
| `Work Arrangement`        | Type of work setup: remote, hybrid, or on-site                                  | Categorical      | Hybrid                     |
| `Upskilled`               | Indicates whether the employee has been upskilled (derived from training status)| Categorical      | Yes / No                   |
| `Gender`                  | Reported gender of the employee                                                 | Categorical      | Female                     |

---

## 🔍 Notes
- The dataset includes intentional imperfections (e.g. missing roles, non-numeric salaries) to simulate real-world data cleaning tasks.
- The `Upskilled` column is derived: `Yes` if `Training Status` is "Completed" or "Inprogress".
- Useful for portfolio analysis around attrition, training effectiveness, regional gaps, and performance correlations.

---
