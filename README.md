# 🚀 AI-Powered FDA Approval Prediction 📊

Welcome to the repository for **AI-Powered FDA Approval Prediction**, a capstone project developed for the **Master of Liberal Arts in Extension Studies at Harvard University**. This project combines advanced **Machine Learning (ML)** and **Natural Language Processing (NLP)** to predict the likelihood of FDA drug approvals based on **Phase II clinical trial data**. 🧪💻

---

## 🔍 **About the Project**
This repository hosts the code, data, and resources used for our predictive modeling project aimed at assisting biotech investors and researchers in forecasting FDA drug approvals. The project leverages:

- **Heterogeneous data sources** like AACT and Cortellis.
- **Advanced ML models**, including tree-based and stacked ensemble models.
- **Language models (LLMs)** for feature extraction from unstructured text.

---

## 📂 **Repository Contents**

### 1. **Data**
   - Contains cleaned and preprocessed datasets derived from AACT and Cortellis databases.
   - Includes features engineered for clinical trial characteristics and drug-specific attributes.

### 2. **Saved Models**
   - Trained ML models ready for inference:
     - Non-sequential models for static predictions.
     - Sequential models for trial sequence analysis.

### 3. **Notebooks**
   - **`1_cortellis_aact_merge.ipynb`**: Data integration and preprocessing.
   - **`2a_Manually_matching_conditions_to_disease_types.ipynb`**: Manual mapping of conditions to disease types.
   - **`2b_conditions_diseasetype_therapyarea.ipynb`**: Further classification into therapy areas.
   - **`3_LM_FDA_Feature_Extraction_And_Data_Processing.ipynb`**: Feature extraction using advanced NLP models.
   - **`4_merged_df_1021_p2_p4filter_otherfeatures.ipynb`**: Dataset consolidation and filtering.
   - **`5_data_rollup_single_drug_disease_pair.ipynb`**: Creating data points for modeling.
   - **`6_time_sequence_final_data.ipynb`**: Trial sequence dataset preparation.
   - **`7_final_models_non_seq.ipynb`**: Non-sequential model training and evaluation.
   - **`8_final_models_seq.ipynb`**: Sequential model development and analysis.

---

## 🛠️ **Key Features**
- **Predictive modeling** with tree-based algorithms like Random Forest, XGBoost, and LightGBM.
- **Text mining with LLMs** (e.g., GPT-4, Llama3.2) for feature generation.
- **Trial sequence analysis** for dynamic predictions.

---

## 🧠 **Methodology**
### 📈 **Steps**
1. **Data Integration**: Combined data from AACT and Cortellis.
2. **Feature Engineering**: Extracted structured and unstructured features.
3. **Baseline Models**: Built Random Forest and XGBoost models for initial predictions.
4. **Enhanced Models**: Incorporated LLM-extracted features.
5. **Final Models**: Developed sequential models for real-time trial sequence analysis.

---

## 🎯 **Applications**
- **Investors**: Predict drug approval outcomes to guide investments.
- **Biotech firms**: Enhance decision-making in drug development.
- **Regulators**: Analyze trends and success factors in clinical trials.

---

## 📜 **Acknowledgments**
We are deeply grateful to:
- **Dr. Bruce Huang** for guidance on data processing.
- **Dr. Stephen F. Elston** for insights into ML methodologies.
- **Paulo Silva** for consistant help, espertise and mentorship.
- **Teaching Fellow Leonardo Neves** for assistance with NLP techniques.
- The **Harvard Extension School Data Science Capstone cohort** for their support.

---

## 💡 **Future Directions**
- Integrating real-time trial updates.
- Fine-tuning specialized language models for FDA prediction tasks.
- Expanding feature sets with sponsor data and trial methodologies.

---
For further inquiries, feel free to reach out at mofeiwang@hotmail.com.


