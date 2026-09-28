# Genomic Variant Calling Pipeline for Hemoglobinopathies

* **Pipeline Tool:** GATK4 (HaplotypeCaller)
* **Target Coordinates:** Chromosome 11 (HBB Gene Region)
* **Objective:** Screening for Hemoglobin E (Hb E) traits and diseases.

## Workflow Strategy
* **Phase 1:** Designed a targeted variant calling workflow using GATK4 to parse patient NGS data.
* **Phase 2:** Modeled a diagnostic interpretation worksheet to classify patient phenotypes (Normal, Heterozygous Trait, Homozygous Disease) using VCF metadata analysis.
* **Phase 3:** Evaluated Allele Depth (AD) and depth configuration metrics to optimize clinical reporting accuracy.
