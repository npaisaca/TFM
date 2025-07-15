# Bioinformatic pipeline of RRBS for differential methylation analysis - TFM 24/25

## Overview

Bioinformatic analysis of the methylome of blood, brain, liver, gonad and muscle of the European sea bass (_Dicentrarchus labrax_). DNA extracted from the tissues was sequenced with NGS methods; this repository includes the code files devised for the appropriate manipulation and preparation of the reads through bisulfite conversion and DMC extraction.

The contents of this repository and the results of the analysis were included in my TFM (Master's Thesis 2024-2025).

## Files

- **RRBS_pipeline.Rmd**: code to perform the bioinformatic pipeline of the RRBS analysis, from file download to CpG report extraction and bisulfite conversion efficiency calculation.
- **R_pipeline.Rmd**: code to perform the R part of the RRBS analysis, through the use of `methylKit` and additional R packages, from file upload to the permutation test.

All files were created in an R-markdown format.
