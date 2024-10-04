# Differential Gene Expression Analysis in Human Airway Smooth Muscle Cells (GSE52778)

**Description**  
This project involves the analysis of transcriptomic changes in Human Airway Smooth Muscle (HASM) cells under the influence of asthma treatments such as β2-agonists (Albuterol), glucocorticosteroids (Dexamethasone), and their combination. The goal is to understand how these treatments modulate gene expression to alleviate asthma symptoms, aiding the development of targeted therapies.

---

## Table of Contents
- [Study Design](#study-design)
- [Data Preprocessing](#data-preprocessing)
- [Analysis](#analysis)
- [Results](#results)
- [Conclusion](#conclusion)
- [Technologies Used](#technologies-used)
- [License](#license)
- [Contact](#contact)

---

## Study Design
- The project analyzes gene expression changes in HASM cells subjected to three different conditions:
  - Treatment with **β2-agonists** (Albuterol)
  - Treatment with **glucocorticosteroids** (Dexamethasone)
  - Combined treatment of both
  - Control (no treatment)
  
- **Objective**: To identify genes differentially expressed in response to these treatments and assess their biological significance in the context of asthma.

---

## Data Preprocessing
- RNA-Seq data was retrieved, and differential expression analysis was performed.
- Techniques used:
  - MA Plot: Showed the magnitude of expression changes.
  - Volcano Plot: Highlighted significant genes based on fold changes.
  - Dispersion Plot: Measured variability in gene expression.
  - PCA Plot: Identified differences in gene expression patterns across treatments.
  - Heatmaps: Showed gene expression variation across samples.

---

## Analysis
- **MA Plot**: Indicated targeted changes in specific genes without global transcriptional disruption.
- **Volcano Plot**: Identified significant upregulated and downregulated genes with large fold changes.
- **PCA Plot**: Showed clear separation of gene expression profiles across treatments, indicating distinct molecular responses.
- **Heatmaps**: Highlighted specific genes driving responses to β2-agonists and glucocorticosteroids treatments.

---

## Results
- Gene expression was significantly altered by both types of treatments compared to control samples.
- The combined treatment had unique effects, suggesting possible synergistic action between β2-agonists and glucocorticosteroids.
- Identified potential biomarkers and therapeutic targets for asthma treatments.
  
---

## Conclusion
This analysis provides insight into how asthma treatments modulate gene expression in HASM cells. The findings could guide personalized therapy development and the identification of key genes for therapeutic targeting in asthma. These results serve as a basis for future research into asthma treatment mechanisms.

---

## Technologies Used
- **RNA-Seq**: For gene expression profiling.
- **Bioinformatics Tools**: DESeq2, R packages for statistical analysis of RNA-Seq data.
- **Plots**: PCA, MA, Volcano, Heatmaps for data visualization.

---

## License
This project is open-source and licensed under the MIT License. 

---

## Contact
**Shantanu Yadav**  
Email: [shantanu19@kgpian.iitkgp.ac.in](mailto:shantanu19@kgpian.iitkgp.ac.in)
