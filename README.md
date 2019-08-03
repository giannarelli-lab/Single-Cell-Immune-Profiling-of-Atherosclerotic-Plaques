# Single Cell Immune Profiling of Atherosclerotic Plaques
This repository contains notebooks for interactively visualizing the single cell gene expression data from the study: **Immune Profiling of Atherosclerotic Plaques Identifies Innate and Adaptive  Dysregulations Associated with Ischemic Cerebrovascular Events (Fernandez et al.)**. The interactive visualizations are made using the single cell data analysis and visualization toolkit [Clustergrammer2](https://clustergrammer.readthedocs.io/) and work best using the Chrome browser.

[![citeseq_adt](img/citeseq_adt.gif)](https://nbviewer.jupyter.org/github/giannarelli-lab/Single-Cell-Immune-Profiling-of-Atherosclerotic-Plaques/blob/master/notebooks/1.0_CITE-seq_ADT_PBMC_and_Plaque.ipynb?flush_cache=true)

### Notebook Directory

*CITE-seq Sample*
* [1.0 CITE-seq PBMC and Plaque: ADT](#10-cite-seq-pbmc-and-plaque-adt)
* [1.1 CITE-seq PBMC and Plaque: GEX](#11-cite-seq-pbmc-and-plaque-gex)
* [1.2 CITE-seq GEX Plaque: T Cells](#12-cite-seq-gex-plaque-t-cells)
* [1.3 CITE-seq GEX Plaque: CD4 T Cells](#13-cite-seq-gex-plaque-cd4-t-cells)
* [1.4 CITE-seq GEX Plaque: CD8 T Cells](#14-cite-seq-gex-plaque-cd8-t-cells)
* [1.5 CITE-seq GEX Plaque: Macrophages](#15-cite-seq-gex-plaque-macrophages)

*Sample Cohort scRNA-seq*
* [2.0 scRNA-seq GEX Cohort: T Cells](#20-scrna-seq-cohort-t-cells)
* [2.1 scRNA-seq GEX Cohort: CD4 T Cells](#21-scrna-seq-cohort-cd4-t-cells)
* [2.2 scRNA-seq GEX Cohort: CD8 T Cells](#22-scrna-seq-cohort-cd8-t-cells)
* [2.3 scRNA-seq GEX Cohort: Macrophages](#23-scrna-seq-cohort-macrophages)

*Ligand-Receptor Interaction Prediction*
* [3.0 Ligand-Receptor Sym-vs-Asym Differential Regulation](#30-ligand-receptor-sym-vs-asym-differential-regulation)

Click above notebook links to navigate to section and find NBViewer linkst to interactive notebooks.

## 1.0 CITE-seq PBMC and Plaque: ADT

[![Nbviewer](https://github.com/jupyter/design/blob/master/logos/Badges/nbviewer_badge.svg)](https://nbviewer.jupyter.org/github/giannarelli-lab/Single-Cell-Immune-Profiling-of-Atherosclerotic-Plaques/blob/master/notebooks/1.0_CITE-seq_ADT_PBMC_and_Plaque.ipynb?flush_cache=true)

[<img src='img/citeseq_adt_pbmc_plaque.png' alt="citeseq_adt_pbmc_plaque" width="500px" >](https://nbviewer.jupyter.org/github/giannarelli-lab/Single-Cell-Immune-Profiling-of-Atherosclerotic-Plaques/blob/master/notebooks/1.0_CITE-seq_ADT_PBMC_and_Plaque.ipynb?flush_cache=true)

Single cell antibody derived tag data data was obtained from plaque and PBMC from the same subject. Cell type was assigned based on ADT surface marker expression.

## 1.1 CITE-seq PBMC and Plaque: GEX

[![Nbviewer](https://github.com/jupyter/design/blob/master/logos/Badges/nbviewer_badge.svg)](https://nbviewer.jupyter.org/github/giannarelli-lab/Single-Cell-Immune-Profiling-of-Atherosclerotic-Plaques/blob/master/notebooks/1.1_CITE-seq_GEX_PBMC_and_Plaque.ipynb?flush_cache=true)

[<img src='img/citeseq_gex_pbmc_plaque.png' alt="citeseq_gex_pbmc_plaque" width="500px" >](https://nbviewer.jupyter.org/github/giannarelli-lab/Single-Cell-Immune-Profiling-of-Atherosclerotic-Plaques/blob/master/notebooks/1.1_CITE-seq_GEX_PBMC_and_Plaque.ipynb?flush_cache=true)

Single cell gene expression data data was obtained from plaque and PBMC from the same subject. Cell type was assigned based on ADT surface marker expression.

## 1.2 CITE-seq GEX Plaque: T Cells
[![Nbviewer](https://github.com/jupyter/design/blob/master/logos/Badges/nbviewer_badge.svg)](https://nbviewer.jupyter.org/github/giannarelli-lab/Single-Cell-Immune-Profiling-of-Atherosclerotic-Plaques/blob/master/notebooks/1.2_CITE-seq_GEX_Plaque_T_Cells.ipynb?flush_cache=true)

[<img src='img/citeseq_gex_t_cells_plaque.png' alt="citeseq_gex_t_cells_plaque" width="500px" >](https://nbviewer.jupyter.org/github/giannarelli-lab/Single-Cell-Immune-Profiling-of-Atherosclerotic-Plaques/blob/master/notebooks/1.2_CITE-seq_GEX_Plaque_T_Cells.ipynb?flush_cache=true)

Single cell gene expression data data was obtained from plaque and PBMC from the same subject. Cell type was assigned based on ADT surface marker expression.

## 1.3 CITE-seq GEX Plaque: CD4 T Cells
[![Nbviewer](https://github.com/jupyter/design/blob/master/logos/Badges/nbviewer_badge.svg)](https://nbviewer.jupyter.org/github/giannarelli-lab/Single-Cell-Immune-Profiling-of-Atherosclerotic-Plaques/blob/master/notebooks/1.3_CITE-seq_GEX_Plaque_CD4_T_Cells.ipynb?flush_cache=true)

[<img src='img/citeseq_gex_cd4_t_cells_plaque.png' alt="citeseq_gex_cd4_t_cells_plaque" width="500px" >](https://nbviewer.jupyter.org/github/giannarelli-lab/Single-Cell-Immune-Profiling-of-Atherosclerotic-Plaques/blob/master/notebooks/1.3_CITE-seq_GEX_Plaque_CD4_T_Cells.ipynb?flush_cache=true)

Single cell gene expression data data was obtained from plaque and PBMC from the same subject. Cell type was assigned based on ADT surface marker expression.

## 1.4 CITE-seq GEX Plaque: CD8 T Cells
[![Nbviewer](https://github.com/jupyter/design/blob/master/logos/Badges/nbviewer_badge.svg)](https://nbviewer.jupyter.org/github/giannarelli-lab/Single-Cell-Immune-Profiling-of-Atherosclerotic-Plaques/blob/master/notebooks/1.4_CITE-seq_GEX_Plaque_CD8_T_Cells.ipynb?flush_cache=true)

[<img src='img/citeseq_gex_cd8_t_cells_plaque.png' alt="citeseq_gex_cd8_t_cells_plaque" width="500px" >](https://nbviewer.jupyter.org/github/giannarelli-lab/Single-Cell-Immune-Profiling-of-Atherosclerotic-Plaques/blob/master/notebooks/1.4_CITE-seq_GEX_Plaque_CD8_T_Cells.ipynb?flush_cache=true)

Single cell gene expression data data was obtained from plaque and PBMC from the same subject. Cell type was assigned based on ADT surface marker expression.

## 1.5 CITE-seq GEX Plaque: Macrophages
[![Nbviewer](https://github.com/jupyter/design/blob/master/logos/Badges/nbviewer_badge.svg)](https://nbviewer.jupyter.org/github/giannarelli-lab/Single-Cell-Immune-Profiling-of-Atherosclerotic-Plaques/blob/master/notebooks/1.5_CITE-seq_GEX_Plaque_Macrophages.ipynb?flush_cache=true)

[<img src='img/citeseq_gex_macrophages_plaque.png' alt="citeseq_gex_macrophages_plaque" width="500px" >](https://nbviewer.jupyter.org/github/giannarelli-lab/Single-Cell-Immune-Profiling-of-Atherosclerotic-Plaques/blob/master/notebooks/1.5_CITE-seq_GEX_Plaque_Macrophages.ipynb?flush_cache=true)

Single cell gene expression data data was obtained from plaque and PBMC from the same subject. Cell type was assigned based on ADT surface marker expression.

## 2.0 scRNA-seq Cohort: T Cells
[![Nbviewer](https://github.com/jupyter/design/blob/master/logos/Badges/nbviewer_badge.svg)](https://nbviewer.jupyter.org/github/giannarelli-lab/Single-Cell-Immune-Profiling-of-Atherosclerotic-Plaques/blob/master/notebooks/2.0_scRNA-seq_Cohort_T_Cells.ipynb?flush_cache=true)

[<img src='img/scrnaseq_cohort_t_cells.png' alt="scrnaseq_cohort_t_cells" width="500px" >](https://nbviewer.jupyter.org/github/giannarelli-lab/Single-Cell-Immune-Profiling-of-Atherosclerotic-Plaques/blob/master/notebooks/2.0_scRNA-seq_Cohort_T_Cells.ipynb?flush_cache=true)

Single-cell gene expression data was obtained from atherosclerotic plaque samples from a cohort of six patients.


## 2.1 scRNA-seq Cohort: CD4 T Cells
[![Nbviewer](https://github.com/jupyter/design/blob/master/logos/Badges/nbviewer_badge.svg)](https://nbviewer.jupyter.org/github/giannarelli-lab/Single-Cell-Immune-Profiling-of-Atherosclerotic-Plaques/blob/master/notebooks/2.1_scRNA-seq_Cohort_CD4_T_Cells.ipynb?flush_cache=true)

[<img src='img/scrnaseq_cohort_cd4_t_cells.png' alt="scrnaseq_cohort_cd4_t_cells" width="500px" >](https://nbviewer.jupyter.org/github/giannarelli-lab/Single-Cell-Immune-Profiling-of-Atherosclerotic-Plaques/blob/master/notebooks/2.1_scRNA-seq_Cohort_CD4_T_Cells.ipynb?flush_cache=true)

Single-cell gene expression data was obtained from atherosclerotic plaque samples from a cohort of six patients.


## 2.2 scRNA-seq Cohort: CD8 T Cells
[![Nbviewer](https://github.com/jupyter/design/blob/master/logos/Badges/nbviewer_badge.svg)](https://nbviewer.jupyter.org/github/giannarelli-lab/Single-Cell-Immune-Profiling-of-Atherosclerotic-Plaques/blob/master/notebooks/2.2_scRNA-seq_Cohort_CD8_T_Cells.ipynb?flush_cache=true)

[<img src='img/scrnaseq_cohort_cd8_t_cells.png' alt="scrnaseq_cohort_cd8_t_cells" width="500px" >](https://nbviewer.jupyter.org/github/giannarelli-lab/Single-Cell-Immune-Profiling-of-Atherosclerotic-Plaques/blob/master/notebooks/2.2_scRNA-seq_Cohort_CD8_T_Cells.ipynb?flush_cache=true)

Single-cell gene expression data was obtained from atherosclerotic plaque samples from a cohort of six patients.

## 2.3 scRNA-seq Cohort: Macrophages
[![Nbviewer](https://github.com/jupyter/design/blob/master/logos/Badges/nbviewer_badge.svg)](https://nbviewer.jupyter.org/github/giannarelli-lab/Single-Cell-Immune-Profiling-of-Atherosclerotic-Plaques/blob/master/notebooks/2.3_scRNA-seq_Cohort_Macrophages.ipynb?flush_cache=true)

[<img src='img/scrnaseq_cohort_macrophages.png' alt="scrnaseq_cohort_macrophages" width="500px" >](https://nbviewer.jupyter.org/github/giannarelli-lab/Single-Cell-Immune-Profiling-of-Atherosclerotic-Plaques/blob/master/notebooks/2.3_scRNA-seq_Cohort_Macrophages.ipynb?flush_cache=true)

Single-cell gene expression data was obtained from atherosclerotic plaque samples from a cohort of six patients.

## 3.0 Ligand-Receptor Sym-vs-Asym Differential Regulation
[![Nbviewer](https://github.com/jupyter/design/blob/master/logos/Badges/nbviewer_badge.svg)](https://nbviewer.jupyter.org/github/giannarelli-lab/Single-Cell-Immune-Profiling-of-Atherosclerotic-Plaques/blob/master/notebooks/3.0_Ligand-Receptor_Sym-vs-Asym_Differential_Regulation.ipynb?flush_cache=true)

[<img src='img/lig-rec_sym-asym_diff_interactions.png' alt="lig-rec_sym-asym_diff_interactions" width="500px" >](https://nbviewer.jupyter.org/github/giannarelli-lab/Single-Cell-Immune-Profiling-of-Atherosclerotic-Plaques/blob/master/notebooks/3.0_Ligand-Receptor_Sym-vs-Asym_Differential_Regulation.ipynb?flush_cache=true)

Putative ligand-receptor interactions between cell types were predicted based on the product of ligand and receptor expression across pairs of cell types. Differentially regulated interactions across symptomatic vs asymptomatic plaques are shown in interactive heatmaps.

## Contact
https://www.mountsinai.org/profiles/chiara-giannarelli
