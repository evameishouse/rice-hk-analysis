# RNA-seq and Data Analysis for "Phenotypic effects of disruption of all four rice HK cytokinin receptors"

This repository contains code, input, and output files associated with the analysis described in  
**Cytokinin histidine kinase receptors regulate multiple aspects of rice growth and development**, submitted to *Plant Physiology*.

The repository includes:
- RNA-seq quantification and differential expression analysis
- Principal Component Analysis (PCA) of average traits from mutant lines
- Generalized Linear Model (GLM) analysis of phenotypes from mutant lines

---

## Repository Structure
```
rice-hk-analysis/
├── data/
│   ├── kallisto_output/
│   │   ├── sample1/abundance.h5
│   │   ├── sample2/abundance.h5
│   │   └── ... (one folder per sample)
│   ├── averagetraitstrim.csv
│   ├── Oryza_sativa.IRGSP-1.0.cdna.all.fa.gz
│   ├── phenotypedata.sqlite
│   ├── seeds.sqlite
│   └── typeackxgenes.csv
├── output/
│   ├── traitplots/
│   ├── de_hk3456_ba_sig_with_tpm.csv
│   ├── de_hk3456_wt_sig_with_tpm.csv
│   ├── de_wt_ba_sig_with_tpm.csv
│   ├── fwd_glm_coefficients.csv
│   ├── fwd_glm_pvalue.csv
│   ├── rev_glm_coefficients.csv
│   └── rev_glm_pvalue.csv
├── avg_trait_pca.Rmd
├── avg_trait_pca.html
├── forward_glm.Rmd
├── forward_glm.html
├── reverse_glm.Rmd
├── reverse_glm.html
├── rnaseq_analysis.Rmd
├── rnaseq_analysis.html
├── README.md
└── LICENSE
```


## License

This repository is licensed under the MIT License. See the LICENSE file for details.
