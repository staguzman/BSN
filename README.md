# _BSN_ Variants and Epilepsy: Exploring Phenotypic Variability and Penetrance


This repository contains scripts used to analyze Human Phenotype Ontology (HPO) terms in individuals with BSN variants. By systematically evaluating clinical and genetic data, we investigate phenotypic patterns and their relevance to BSN-related disorders compared to other developmental and epileptic encephalopathies (DEEs) and neurodevelopmental disorders (NDDs).

### Scripts  

- [**hpo_prop_base**](hpo_prop_base.R) – Extracts propagated and base HPO terms for the joint cohort, forming the foundation for phenotype analysis.  
- [**Radar_plot_analysis**](Radar_plot_analysis.R) – Identifies the frequency of HPO terms and highlights the most common phenotypic features within each group.  
- [**Longitudinal_analysis**](Longitudinal_analysis.R) – Uses ICD-10 data from electronic medical records (EMR) and manually extracted diagnoses to track phenotypic frequencies over time.  
- [**Volcano_plot_analysis**](Volcano_plot_analysis.R) – Conducts phenotypic association analysis, comparing BSN-related phenotypes to a larger reference group to identify significant clinical features.  
