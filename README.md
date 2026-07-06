# PangoFormer
## Bacformer for Pangenome Analysis
<p align="justify">
Recent advances in genomic foundation models have opened new opportunities for representing bacterial genomes through contextualized protein embeddings. Building upon Bacformer, a transformer-based genomic language model, this project investigates its application to pangenome analysis.
</p>

## Overview
<p align="justify">
The objective of this work is to adapt and evaluate Bacformer for the analysis of bacterial pangenomic data. The study was conducted in two stages: first on a single bacterial strain to validate the adapted pipeline, and subsequently on a complete pangenome to assess scalability and identify challenges associated with larger datasets.
</p>

## Single-Strain Validation

### Dataset: 
Acinetobacter baumannii AYE (~3,770 genes, 3,639 gene families)

### Objective: 
Validate the adapted pipeline and ensure correct protein embedding generation.

## Pangenome Extension

### Dataset: 
Acinetobacter baylyi pangenome (21 genomes from PanGBank)

### Objective: 
Extend the approach to pangenome-scale data and explore challenges related to scaling the model to larger and more diverse genomic datasets.

# Reference
[1] Wiatrak M et al. bioRxiv. 2025. doi:10.1101/2025.07.20.665723.
