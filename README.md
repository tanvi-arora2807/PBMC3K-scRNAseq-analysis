# Single Cell RNA-Seq Analysis of PBMC3K Dataset

## Overview
This project demonstrates a complete single-cell RNA sequencing (scRNA-seq) workflow using the PBMC3K dataset and the Scanpy framework.

The analysis includes quality control, preprocessing, dimensionality reduction, clustering, and marker gene identification.

## Dataset
- Dataset: PBMC3K (Peripheral Blood Mononuclear Cells)
- Source: 10x Genomics
- Cells analyzed: ~2700 cells

## Workflow
1. Quality control
2. Filtering low-quality cells and genes
3. Data normalization
4. Highly variable gene selection
5. Principal Component Analysis (PCA)
6. Neighborhood graph construction
7. UMAP visualization
8. Leiden clustering
9. Marker gene identification

## Results
### UMAP Clustering
Leiden clustering successfully identified distinct cell populations.

### Marker Genes
Marker genes were identified for each cluster using Scanpy's rank_genes_groups function.

## Tools and Libraries
- Python
- Scanpy
- AnnData
- Pandas
- NumPy
- Matplotlib
- Leidenalg

## Repository Structure
PBMC3K-scRNAseq-analysis/
│
├── data/
├── figures/
├── notebooks/
├── results/
├── README.md
└── requirements.txt
## Skills Demonstrated
- Single-cell RNA-seq analysis
- Data preprocessing and quality control
- Dimensionality reduction (PCA, UMAP)
- Cell clustering
- Marker gene discovery
- Python for bioinformatics
- Git and GitHub version control

## Author
Tanvi Arora
M.Sc.(Ag.) Molecular Biology & Biotechnology
