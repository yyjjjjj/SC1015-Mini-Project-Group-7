# Welcome to Obesity Analysis Repository
**About**
---

This Mini Project for SC1015 (Introduction to Data Science and Artificial Intelligence) focuses on factors that influence risk of obesity.  
This is project done by ECDS Group 7 (Ying Jie, Nadya, Deleah).

1. Data Preparation and Cleaning https://github.com/yyjjjjj/SC1015-Mini-Project-Group-7/blob/dccb0618122ddb404d0de755bd4879da5cbf6104/Data_Cleaning.ipynb
2. Exploratory Data Analysis https://github.com/yyjjjjj/SC1015-Mini-Project-Group-7/blob/eb1781519d986be31476ab99835e76d3be338ae7/Data_Exploratory_Analysis.ipynb
3. Machine Learning Techniques
4. Data-Driven Insights and Conclusion https://github.com/yyjjjjj/SC1015-Mini-Project-Group-7/blob/bb4389b0861d4a02d9b102066ab046c6fc224b7c/Remarks_Data_driven_Insights_%26_Conclusion.ipynb

**Contributors**
---
all - Data Preparation and Cleaning  
@yyjjjjj - Exploratory Data Analysis, Data-Driven insights  
@nadyacheng - Binary Decision Tree Classification  
@deleahtan - Random Forest Classification, Conclusion

**Problem Definition**
---
1. Which factor(s) are the most important in predicting obesity?
2. Which model does this best?

**Models Used**
---
1. Binary Decision Tree Classification https://github.com/yyjjjjj/SC1015-Mini-Project-Group-7/blob/f5aa1df37d2bfd679c82804b8a68bc688a1e787d/Model_1_Binary_Decision_Tree_Classification.ipynb
2. Random Forest Classification https://github.com/yyjjjjj/SC1015-Mini-Project-Group-7/blob/8fb2ad83e356a80ddff3d7374ad0e5e5978b31b3/Model_2_Random_Forest_Classification.ipynb
   
**Process:**
---
- Proper data cleaning were essential to ensuring our models could learn effectively.
- Exploratory Data Analysis (EDA) and visualization helped us identify key trends and correlations that guided our model-building process.
- Decision Tree Classifiers provided clear, interpretable models and gave us insight into how different features contributed to predictions.
- Random Forest Classifiers outperformed basic decision trees in terms of accuracy and generalization, showing the power of ensemble methods.
- GridSearchCV helped us fine-tune hyperparameters to improve model performance, demonstrating the value of systematic tuning.
- Our final models achieved good predictive performance, confirming that it's feasible to classify the data accurately using machine learning techniques.

**Conclusions:**
---
- Higher physical activity frequency lowers obesity risk most significantly.
- A family history of obesity also has a strong impact on obesity risk.
- Lower alcohol consumption reduces obesity risk, but only to a small extent.
- Less frequent consumption of high-calorie foods lowers obesity risk to the smallest extent.
- Strategies to reduce Obesity should focus mainly on encouraging physical activity. Addiitonally, early screening andtargeted interventions should be offered to individuals with a family history of Obesity to enable early lifestyle changes and prevent obesity before it develops.
- Both our Decision Tree Classification and Random Forest Classification models have rather high classification accuracy of above 0.777. However, Random Forest Classification demonstrates better balance between minimising incorrect classifications (FPs and FNs) and identifying TPs, thus Random Forest Classification can be considered slightly more effective than Decision Tree Classification.



**What we learnt from this project**
---
- How to collaborate using GitHub for sharing code, managing versions, and working as a team.
- Implementation and comparison of multiple classification models (Decision Trees and Random Forests)
- How to use GridSearchCV to perform hyperparameter tuning and improve model performance.
- Techniques for data preprocessing, including handling missing data, label encoding, and standardization.
- Importance of feature selection and its impact on model accuracy and interpretability.
- Use of visualization libraries like matplotlib and seaborn to analyze data and model outcomes.
- Evaluation of model performance using metrics like accuracy, precision, recall, and F1 score.
- How different model architectures affect overfitting, interpretability, and computational efficiency.
- The end-to-end process of building a machine learning project, from raw data to final predictions.


**References**
---
https://www.kaggle.com/datasets/mandysia/obesity-dataset-cleaned-and-data-sinthetic/data
