# Base R Data Munging Project

This project was developed as part of our Data Munging course.  
Our main goal was to explore how far we could go using **Base R** functions to clean, reshape, and summarize data — without relying on tidyverse packages.

---

## 🧩 Overview

We worked with institutional and field-of-study datasets to practice the main concepts of data wrangling in R.  
Before switching to R, we initially performed several **data transformations in Python**, such as:
- Removing and imputing missing values
- Standardizing column names and data types
- Filtering out inconsistent or duplicate entries
- Merging institutional and earnings datasets
- Exporting the cleaned data into `.csv` files for use in R

After that, we moved to **Base R** for the main analysis, focusing on:
- Subsetting and filtering with `subset()`
- Summarizing using `apply()`, `tapply()`, and `aggregate()`
- Reshaping data with `reshape()` and `melt/cast` structures
- Joining tables using `merge()`
- Basic visualization with `plot()` and `barplot()`

---

## 📊 Findings

Across our analysis, we observed a consistent pattern:  
**public and non-profit institutions** tended to perform better both financially (in terms of return on investment) and in graduation outcomes.  

However, it’s important to note that **many private colleges had missing data**, which likely explains the low representation and skewed averages in some of the results.  
This limitation highlighted how critical data completeness and accuracy are when drawing broader conclusions.

---

## 📂 Files Included

| File | Description |
|------|--------------|
| `BaseR_Presentation.Rmd` | Main R Markdown document with the full analysis |
| `Will_Python_to_BaseR_Presentation.Rmd` | Collaborative version — translating Python logic into Base R |
| `BaseR_Presentation.html` | Rendered version of the presentation (output) |
| `BaseR_Presentation.pdf` | PDF version of the final presentation (static, ideal for sharing or printing) |


---

## 👥 Team
- **Will**
- **Leonardo Schneider**
- **James**

Date: *October 2025*

---

## ⚙️ How to Run

1. Open the `.Rmd` file in RStudio.  
2. Click **Knit** → choose **HTML** as output format.  
3. The presentation will be generated inside the `/output/` folder.

If you just want to view the project, open the `.html` file directly in your browser.

---

## 💡 Reflections

This project gave us a solid understanding of how much can be achieved using **Base R** alone.  
While it required more manual coding compared to Python or `dplyr`, it helped us fully understand the data transformation process from the ground up.  

Combining both tools — cleaning in Python and analyzing in R — provided a complete end-to-end data workflow.  
Overall, this experience showed how the fundamentals of data manipulation remain consistent across languages, even when syntax and libraries differ.

---

## 🌐 Project Preview (GitHub Pages)

Soon this section will include a direct link to the online HTML presentation.
