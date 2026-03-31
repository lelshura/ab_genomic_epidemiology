# AB Genomic Epidemiology

Genomic epidemiology analysis of *Acinetobacter baumannii* to investigate sequence type distribution, clinical source patterns, clonal relationships, and antimicrobial resistance profiles.

---

## Overview

This project analyzes clinical *Acinetobacter baumannii* isolates to characterize sequence type (ST) distribution, clinical source associations, antimicrobial resistance patterns, and genomic relationships across a national dataset.

The analysis also incorporates global data from NCBI Pathogen Detection to place the isolates within a broader population context.

---

## Objectives

- Describe the distribution of major sequence types (STs)  
- Assess associations between ST and clinical source  
- Characterize antimicrobial resistance gene profiles  
- Apply statistical testing to evaluate distribution patterns  
- Compare isolates within global SNP clusters  
- Explore genomic relationships between isolates  

---

## Methods

- Cleaning and standardization of isolate metadata  
- Classification of clinical sources (blood, urine, respiratory, wound/tissue)  
- Identification of antimicrobial resistance genes (AMRFinderPlus)  
- Aggregation and visualization of ST distributions  
- Chi-square testing of ST and source associations  
- Integration with NCBI SNP cluster data  
- Distance-based analysis from phylogenetic trees  

---

## Data

- Clinical isolate metadata  
- NCBI Pathogen Detection (`isolates.tsv`)  
- SNP cluster assignments and phylogenetic trees  

---

## Repository Structure

scripts/ # Analysis scripts
results/ # Figures and output tables
docs/ # Notes

---

## Acknowledgments

This work was conducted during a visiting research internship at King Abdullah University of Science and Technology (KAUST).
