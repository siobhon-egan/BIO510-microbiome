# BIO510

Material for teaching BIO510 microbiome data analysis components

Website: https://siobhonlegan.com/BIO510-microbiome

Updated: December 2021

---

## Software

**REQUIRED** - We will be using RStudio to analyse the data set. It is recommend you have the following installed: [*RStudio version 1.4*](https://rstudio.com/products/rstudio/download/) or later and [*R version 4.0*](https://www.r-project.org/) or later. Further details on getting started in RStudio [here](http://siobhonlegan.com/research_site/rstudio/).

**Optional** (*not needed for today's workshop*) - We will not be doing the sequence processing steps today but if you did want to do this you will need to download [conda](https://conda.io/projects/conda/en/latest/user-guide/install/index.html) and [QIIME2](https://qiime2.org/).

## Download data

1.  **Raw Sequence data** (*optional*)

The input for analysis is raw sequence data in `.fastq` format. Zipped files come in the format `.fastq.gz`

Rename so `fastq.gz` files are in the format `SAMPLEID_INITIALS_LIBRARYID_L001_R1_001.fastq.gz` (forward) or `SAMPLEID_INITIALS_LIBRARYID_L001_R2_001.fastq.gz` (reverse).

The raw sequence data can be downloaded from repository link [here](https://figshare.com/s/804cc8b2a17d4f01f2c7).

2.  **Code and R Data** (*REQUIRED*)

The easiest way to follow along with this tutorial is to download this GitHub repository using either option **A** or **B** below:

**OPTION A**.  Go to <https://github.com/siobhon-egan/BIO510-microbiome> and click on the green **Code** button. Select **Download ZIP**, open/unzip the file. Open the `.Rproj` file which should automatically open a project in RStudio.

**OPTION B**.  Use terminal and clone the GitHub repo.

```
git clone https://github.com/siobhon-egan/BIO510-microbiome.git
```
