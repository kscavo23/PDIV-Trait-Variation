# PDIV-Trait-Variation

Scripts and code for analyzing phenotypic variation among Porites divaricata clones 

Part 1: 2bRAD genotyping and clone identification
- Pipeline for demultiplexing, trimming, genome mapping (see https://github.com/kscavo23/PDIV_denovo_RefGenome for details of PDIV genome assembly), and identity by state and clustering (modified from Dr. Mikhail Matz's scripts at https://github.com/z0on/2bRAD_denovo)
- New sequenced samples (Accession #PRJNA987336) were run with previously sequenced samples (Accession #PRJNA833675) to verify clonal lineage identity

Part 2: Environmental site variation
- R code for analyzing temperature and light data from the three transplant sites using likelihood based mixed effect models in lme4

Part 3: Trait mixed effect models
- R code for identifying the percentage of variation explained by different study variables (variance components) using likelihood based and Bayesian mixed effect models in lme4 and MCMCglmm
