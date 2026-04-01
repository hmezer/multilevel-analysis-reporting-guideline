# Correct and Comprehensive Reporting of Results of a Multilevel Analysis

This repository provides comprehensive guidelines, theoretical background, and a practical R tutorial for correctly reporting the results of Multilevel Models (MLM). 

Multilevel models involve many analytic decisions (centering, random-effects specification, estimation methods) that significantly affect results and interpretation. Incomplete reporting hides these choices, hindering reproducibility and trust. This project aims to bridge that gap.

**Authors:** Sila Aydin & Huseyin Mert Ezer (TU Dortmund)

## 📂 Repository Contents

This repository contains two primary resources:

### 1. The Presentation (`reporting-guidelines-presentation.pdf`)
A slide deck outlining the theoretical framework and common pitfalls in MLM reporting. 
**Key topics covered:**
* **Motivation:** Why correct reporting of multilevel models matters.
* **Diagnosing Clustering:** Understanding Intraclass Correlation Coefficient (ICC), Variance Partitioning Coefficient (VPC), and design effects. 
* **Model Specification:** Step-by-step breakdown of Null, Intermediate, and Final models.
* **Model Estimation:** Maximum Likelihood (ML) vs. Restricted Maximum Likelihood (REML).
* **Common Pitfalls:** Guidelines to avoid missing justifications, incomplete variance measures, and poor data hierarchy descriptions.

### 2. The R Tutorial (`Tutorial-in-R.html`)
A practical, step-by-step coding tutorial demonstrating how to execute and report multilevel analyses in R.
* **Format:** HTML Document (compiled from RMarkdown/Quarto).
* **How to view:** Simply download the `Tutorial-in-R.html` file and open it in any web browser (Chrome, Firefox, Safari, etc.) to view the formatted code, outputs, and narrative explanations.

## 🚀 How to Use This Repository

If you are a student or researcher looking to improve your methodological reporting:
1. Start with the **Presentation** to understand *what* needs to be reported and *why*.
2. Move on to the **R Tutorial** to see exactly *how* to extract those required metrics (like ICC, random slope variances, and fixed effects) using R.

## 📚 References
This material draws on key methodological literature, including recommendations from the LEVEL (Logical Explanations & Visualizations of Estimates in Linear mixed models) guidelines, Bates et al., and Huang (2023). Full references are available within the respective documents.
