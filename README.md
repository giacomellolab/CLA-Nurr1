# CLA-Nurr1
This repository contains all the necessary code required to run the Spatial Transcriptomics data analysis for the data in the study "Nurr1 regulates claustral cell identity and hallucinogenic-like states"

Once the count matrices have been generated from the visium libraries using spaceranger, the file [1_quality_check_nurr1.Rmd](CLA-Nurr1/1_quality_check_nurr1.Rmd) can be run to perform necessary quality checks on the data and also to apply filtering parameters. The metadata sheet that is called in this script is <>.This is followed by normalization, code of which is found under 2_normalisation_nurr1.Rmd and the dimensionality reduction and clustering steps are found in the script 3_clustering_analysis_nurr1.Rmd. The final analysed seurat object containing the clusters information can be downloaded from <url>.
4_claustrum_selection_DE.Rmd contains the code for the DE analysis performed on the CLA selected spots after the clustering analysis.
The selected spots for each tissue section (files with extension .csv) and the corresponding analysed seurat object containing these spots can be found under <url>.
