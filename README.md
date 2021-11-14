# WT-RNA-Seq

## Summary

These scripts were used to analyse data obtained from Ion Torrent sequencing of mouse brain tissue.

These data are available on GEO at GSE163878 (https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE163878).

Input files were .fastq files. Data cleanup and read alignment performed in shell languages. Feature counting and differential expression analysis performed in R. A list of programmes and R packages is found below.


## Dependencies

FastQC v0.11.5 (https://www.bioinformatics.babraham.ac.uk/projects/fastqc/)

AdapterRemoval v2.1.7 (https://github.com/MikkelSchubert/adapterremoval/) 

Trimmomatic v0.38 (http://www.usadellab.org/cms/?page=trimmomatic)

STAR v2.5.4b (https://github.com/alexdobin/STAR)

miRDeep2 v0.1.2 (https://github.com/rajewsky-lab/mirdeep2) 


### R packages
- Rsamtools
- Rsubread
- edgeR
- ggplot2
- ggpubr
- tidyverse
- dbplyr
- stringr
- pheatmap

