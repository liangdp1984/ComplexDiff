# Differential Binding Estimation for Protein Complexes

### Introduction

This package provides functions to normalize and estimate 
differential DNA bindings by protein complexes using ChIP-Seq data.

### Installation

First, dependency packages should be pre-installed in R.

```s
source("https://bioconductor.org/biocLite.R")
biocLite(c("matrixStats","IRanges","GenomeInfoDb","GenomicRanges","Rsamtools",
	"rtracklayer","Rsubread","bumphunter","DESeq2","limma","genefilter"))
```

Then, R-package **ComplexDiff** can be installed.

```s
library(devtools)
install_github("tengmx/ComplexDiff")
```

After installation, the package can be loaded into R.

```s
library(ComplexDiff)
```

