# 24-Gene Signature for Hepatocellular Carcinoma

Hepatocellular carcinoma (HCC) is a major cause of cancer-related mortality globally, largely
due to late-stage diagnosis and limitations of existing biomarkers. To address this, we analyzed
RNA-seq data from TCGA-LIHC (371 tumor samples, 50 normal tissues) and three GEO datasets
(GSE57957, GSE62232, GSE112790; 367 samples) using TCGAbiolinks and DESeq2 to identify a
24-gene signature with robust diagnostic and prognostic value. 

We identified 251 common differentially expressed genes across all datasets, from which Boruta analysis selected 79 key genes.
Survival analysis further refined this to 24 prognostically significant genes (20 upregulated, 4
downregulated; p < 0.05). 

The resulting 24-gene signature achieved perfect classification performance in distinguishing tumor from normal liver tissue and demonstrated significant prognostic
value, with all 24 genes associated with overall survival. 

Collectively, these genes regulate DNA
repair (RAD51, FANCD2, FANCB), cell cycle regulation (CLSPN, BUB1, CENPI), extracellular matrix remodeling (COL24A1, COL9A1, COL25A1), as well as chromosomal instability and
epithelial-mesenchymal transition. External validation in independent cohorts is required to fully
clarify the biological roles of less-characterized genes within the signature. This signature may
serve as a valuable tool for early HCC detection and risk stratification.
