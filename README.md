# **Single-Cell Analysis Coursework Projects**

This repository contains coursework projects on **single-cell analysis** and related methods, focusing on **malaria-infected mice**, **B-cell trajectory analysis using PAGA**, and **comparisons of pseudobulk performance** using **Harmony** and **BBKNN** integration methods. 

The repository provides key insights and findings derived from the **single-cell RNA sequencing (scRNA-seq)** analysis.

---

## **Key Findings from the Report**

### **1. Malaria-Infected Mice Single-Cell Analysis**
The analysis of **malaria-infected mice** revealed several important insights:
- **Differential expression analysis** showed a strong contrast between infected and non-infected cells, with numerous **genes related to immune response** being upregulated in the infected mice.
- The scRNA-seq data was cleaned and normalized to ensure **quality control** before the analysis, resulting in highly accurate gene expression results.
- **Clusters of interest** were identified within the immune cells, providing insights into the immune response to malaria infection.

### **2. B-cell Trajectory Analysis using PAGA**
- The **B-cell trajectory analysis** using **PAGA** highlighted the **differentiation pathways** of B-cells in malaria-infected mice. 
- The analysis showed that B-cells undergo significant changes in response to infection, revealing distinct **subpopulations** at various differentiation stages.
- The **PAGA method** allowed for a clear visualization of these differentiation processes, identifying the transition of B-cells within their life cycle states like pre-B cell, intermediate B cell stages and mature B cell stages.

### **3. Pseudobulk Performance Comparison (Harmony vs. BBKNN)**
- The comparison of **pseudobulk analysis** using **Harmony** and **BBKNN** integration methods showed that both methods have their strengths:
  - **Harmony** was particularly effective in integrating data from multiple samples and removing batch effects, providing a more accurate representation of gene expression patterns.
  - **BBKNN** demonstrated better performance in clustering and identifying subpopulations within the data, offering complementary insights when combined with Harmony.
- Overall, the **pseudobulk analysis** provided accurate results in identifying **differentially expressed genes (DEGs)** across different conditions, with both methods proving useful for downstream analysis.

---

## **Files**

- **`single_cell_exploration_notebook.ipynb`**: The Jupyter notebook containing the full **analysis workflow** for **single-cell analysis** of malaria-infected mice.
- **`single_cell_exploration_notebook.pdf`**: **PDF version** of the notebook for easy sharing and reference.

---

## **Requirements**

This project requires several Python libraries for **data analysis** and **visualization**, including **Scanpy**, **matplotlib**, and **seaborn**. Please install these libraries to run the notebook.

---

## **How to Run the Notebook**

1. **Clone the repository** to your local machine.
2. **Navigate** to the project directory.
3. **Open the notebook** in **Jupyter** and follow the instructions within the notebook to run the analysis.

---

