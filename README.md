# Multi-ancestry GWAS and fine-mapping for restless legs syndrome

## Summary

This repository contains all analyses for the manuscript titled "Multi-ancestry genome-wide association study and fine-mapping of restless legs syndrome". This study represents the first ancestry-specific meta-analyses for African, Latin American, and European ancestry cohorts, as well as a large-scale multi-ancestry meta-analysis integrating results from the All of Us Research Program, the Million Veteran Program, the UK Biobank, the Canadian Longitudinal Study on Aging, and CARTaGENE biobanks. 

For the African and Latin American ancestry groups, we included data from the All of Us Research Program and the Million Veteran Program. For the European ancestry group, we included data from All of Us, UK Biobank, the Canadian Longitudinal Study on Aging, CARTaGENE, and Million Veteran Program. GWAS in All of Us and UK Biobank were performed in the current study using individual-level case-control data, whereas  previously published summary statistics were used for the remaining cohorts.

### Datasets

| Dataset                                                                  | Ancestry | Cases | Controls | Total cases | Total controls |
|--------------------------------------------------------------------------|----------|-------|----------|-------------|----------------|
| All of Us AFR (current study)                                            | AFR      | 873   | 33,876   | 2,176       | 153,313        |
| Million Veteran Program African American or Afro-Caribbean (Verma et al) |          | 1,303 | 119,437  |             |                |
| All of Us AMR (current study)                                            | AMR      | 876   | 33,909   | 2,024       | 91,902         |
| Million Veteran Program Hispanic or Latin American (Verma et al)         |          | 1,148 | 57,993   |             |                |
| All of Us EUR (current study)                                            | EUR      | 8,300 | 86,961   | 36,993      | 639,182        |
| UK Biobank (current study)                                               |          | 7,317 | 106,479  |             |                |
| CARTaGENE (Akcimen et al, 2023)                                          |          | 921   | 1,307    |             |                |
| Canadian Longitudinal Study on Aging (Akcimen et al, 2023)               |          | 4,980 | 15,990   |             |                |
| Million Veteran Program European (Verma et al)                           |          | 15,475| 428,445  |             |                |
| **Total**                                                                |          |       |          | **41,193**  | **884,397**    |


### Analysis notebooks

1. Ancestry-stratified GWAS meta-analyses
2. Multiancestry meta-analysis
3. Annotate dbSNP IDs
4. LDSC heritability analysis
5. Fine-mapping of risk regions
