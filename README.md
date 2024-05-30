# Analysis of Gene Expression Detection in Classifying Types of Cancer: Acute Myeloid Leukemia and Acute Lymphoblastic Leukemia Using Principal Component Analysis and Support Vector Machine

#### -- Project Status: [Completed]

### Objective
1. Understanding the explanation of gene expression and how to analyze gene expression.
2. Knowing the methods of Principal Component Analysis (PCA) and Support Vector Machine (SVM).
3. Learning how to classify types of cancer such as Acute Myeloid Leukemia (AML) and Acute Lymphoblastic Leukemia (ALL) using gene expression data with the methods mentioned in point 2.

### Methods Used
* Machine Learning
* Principal Component Analysis
* Support Vector Machine

### Technologies
* Python
* Scikit-Learn
* SciPy
* Seaborn
* GEOparse
* Pandas
  
### Project Description
* The dataset we used consists of datasets for AML (Acute Myeloid Leukemia) titled "Genome-wide DNA methylation profiling of Acute Myeloid Leukemia" (GSE18700) [here](https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE18700) and for ALL (Acute Lymphoblastic Leukemia) titled "Integrative Epigenomic Analysis Identifies Biomarkers and Therapeutic Targets in Adult B-Acute Lymphoblastic Leukemia" (GSE34937) [here](https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE34937). The platform used to acquire this data is HG17_HELP_Promoter (GPL6604) with in-situ oligonucleotide technology in humans (Homo sapiens) [here](https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GPL6604).
* Combining two dataset
* Data preprocessing
* Reduction of Dimension using Principal Component Analysis
* Machine Learning Modeling using Support Vector Machines Classifier
* Evaluation using ROC AUC
 
