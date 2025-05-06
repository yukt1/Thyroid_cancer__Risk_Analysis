# Thyroid Cancer Risk Analysis

Explored clinical and demographic features to understand thyroid cancer risk and improve prediction accuracy.

---

## Project Summary

This project analyzes a large thyroid cancer dataset containing patient-level information such as age, gender, hormone levels, nodule size, ethnicity, radiation exposure, and diagnosis. Through EDA and statistical modeling, we evaluate the reliability of an existing risk scoring system and explore how machine learning can enhance early cancer detection.

---

##  Key Objectives

- Analyze distribution of malignancy across clinical features (e.g., TSH, T3, T4 levels, nodule size)
- Identify discrepancies in the existing Thyroid_Cancer_Risk scoring system
- Handle outliers and inconsistent values in clinical markers
- Build a logistic regression model to detect malignancy
- Address class imbalance to improve recall for malignant cases

---

##  Techniques Used

- **Data Cleaning & Validation**
- **Class Imbalance Handling** (class_weight=balanced)
- **Feature Engineering** (abnormal hormone levels, remodel flags)
- **Visualizations**:
  - Box plots, heatmaps, count plots, bar charts
  - Grouped aggregations by diagnosis and risk category
- **Statistical Modeling**:
  - Logistic Regression with Evaluation Metrics (Precision, Recall, F1-score)

---

##  Key Insights

- Over **27,000 malignant patients** were mislabeled as Low or Medium risk — indicating a **conservative bias** in the risk scoring system.
- **Radiation exposure** and **abnormal nodule size** are strong clinical predictors of malignancy.
- A logistic regression model using just 4 features achieved:
  - **Recall (Malignant class)**: 52%
  - **False negatives reduced by 50%**
- The model demonstrated better sensitivity than the original scoring system, making it a useful adjunct for patient triage.

---

##  Resources

- [![Kaggle Dataset](https://img.shields.io/badge/Kaggle-Thyroid%20Risk%20Data-blue?logo=kaggle)](https://www.kaggle.com/datasets/mzohaibzeeshan/thyroid-cancer-risk-dataset)
- **References**:
- American Cancer Society. (n.d.). *Thyroid cancer risk factors*. Retrieved April 24, 2025, from https://www.cancer.org/cancer/thyroid-cancer/causes-risks-prevention/risk-factors.html  
- SEER Program (NCI, 2022). *Cancer statistics*. Retrieved from https://seer.cancer.gov/statistics/  
- Zeeshan, M. Z. (2022). *Thyroid cancer risk dataset*. Retrieved from https://www.kaggle.com/datasets/mzohaibzeeshan/thyroid-cancer-risk-dataset  
- Tabiti, H., Gbadamassi, A. A., Bendahhou, K., & Oussafrar, Z. (2025). *Occurrence of metastases in differentiated thyroid carcinoma patients: A retrospective study in Morocco covering 10 years of follow-up*. Cureus. https://www.cureus.com/articles/333124-occurrence-of-metastases-in-differentiated-thyroid-carcinoma-patients-a-retrospective-study-in-morrocco-covering-10-years-of-follow-up.pdf  
- Zhang, X. Y., Zhang, D., Zhou, W., & Wang, Z. Y. (2025). *Predicting lymph node metastasis in papillary thyroid carcinoma: Radiomics using two types of ultrasound elastography*. Cancer Imaging. https://pmc.ncbi.nlm.nih.gov/articles/PMC11827213/  
- Shan, R., Li, X., Chen, J., Chen, Z., Cheng, Y. J., & Han, B. (2025). *Interpretable machine learning to predict the malignancy risk of follicular thyroid neoplasms in extremely unbalanced data*. JMIR Cancer. https://cancer.jmir.org/2025/1/e66269  
- Chowdhury, R., Turkdogan, S., Silver, J. A., & Hier, J. (2024). *Approach to hyperthyroidism and its effects on thyroid cancer risk*. MDPI. https://www.mdpi.com/2504-463X/5/2/20  
- Park, S. J., Lee, D. K., & Lee, H. J. (2025). *Excessive iodine intake during lactation is not related to the incidence of thyroid disease: A 3-year follow-up study*. Nutrients. https://www.mdpi.com/2072-6643/17/3/476  
- Hussein, M., Herrera, M., & Pinion, D. (2025). *The impact of radioactive iodine on outcomes among pediatric and adolescent thyroid cancer patients: A SEER database analysis*. Cancers. https://www.mdpi.com/2072-6694/17/1/107  
- Luo, L., Xia, J., Zhang, R., & Yao, X. (2025). *Efficacy and prognosis in patients with papillary thyroid cancer with postoperative preablative stimulated thyroglobulin measurement*. Acta Endocrinologica. https://pmc.ncbi.nlm.nih.gov/articles/PMC11750234/  
- Toraih, E., Hussein, M., & Elshazli, R. (2025). *Therapeutic outcomes and safety of radiofrequency ablation for primary papillary thyroid carcinoma: A meta-analysis*. Radiotherapy and Oncology. https://www.sciencedirect.com/science/article/pii/S0167814025000015  
- Chang, S. L. (2025). *Predictive factors for malignancy in cytologically diagnosed oncocytic cell neoplasm of the thyroid: A single-center analysis*. Authorea. https://www.authorea.com/doi/full/10.22541/au.173900674.46027215  


---

## Next Steps (Future Work)

- Compare performance with other models (Random Forest, XGBoost)
- Explore SHAP for interpretability of model predictions
- Validate model on external datasets
- Create a Streamlit app for clinical use-case demonstration

---

##  Contact

**Yuktha Sankaran Shreenivasan**  
 [LinkedIn](https://www.linkedin.com/in/yukthashreenivasan/)  
 Email: yukthasankaran@gmail.com  
 GitHub: [github.com/yukt1](https://github.com/yukt1)
