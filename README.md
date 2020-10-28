# TRGN510_FinalProject

## Title: Differential expression analysis of clear cell renal cell carcinoma genes for white male versus black/African American male

## Author:
- Yu-Wen Lin (linyuwen@usc.edu)

## Overview of project
- RNA-Seq is now widely used as a tool for gene expression profiling. It detects differentially expressed genes between conditions. For my project, I am looking at clear cell renal cell carcinoma and people who self-report is while male versus black/African American.
- The objective is to identify differentially expressed genes by using Bioconductor and pathway using limma.
- This is the link to Vignettes: https://www.bioconductor.org/packages/devel/workflows/vignettes/RNAseq123/inst/doc/limmaWorkflow.html

## Data
- This link is where I got the data. [GDC Data Protal](https://portal.gdc.cancer.gov). 
- Fifteen data files of white male with clear cell renal cell carcinoma:
  - ba514dbb-42e6-44fd-9c72-73839e1226e6.htseq.counts.gz
  - 45db4b6d-e0d3-430f-b88e-cda7a388c2af.htseq.counts.gz
  - 679e7bab-b24d-415e-a341-da3955e8d47a.htseq.counts.gz
  - 3cd45be6-69d7-41c2-897a-44f8a70a451f.htseq.counts.gz
  - 777d1602-66be-4673-b69d-d651abf7bb35.htseq.counts.gz
  - b197f3a7-4bb6-4e88-b1cf-9ad513873739.htseq.counts.gz
  - a60560b3-962b-4155-8aa5-46c8a5aaf9fa.htseq.counts.gz
  - 137d53ea-eb81-427d-ba2a-c346b904bf4d.htseq.counts.gz
  - 1d5e00c4-5c82-4035-8304-841ba81c61fd.htseq.counts.gz
  - 6134c694-922d-4559-8f55-e03cc58d66dc.htseq.counts.gz
  - fe1e1f62-8e18-4400-9b25-2c439fa25b6f.htseq.counts.gz
  - 275f4377-31b7-436f-bded-1928c2b4f8e1.htseq.counts.gz
  - 3e5cd7b6-1f38-4ca3-a391-414b817a2203.htseq.counts.gz
  - d9c7a1f7-f303-4617-b46c-2003e871095b.htseq.counts.gz
  - d88996bb-af00-4040-b251-29807506ac1f.htseq.counts.gz
- Fifteen data files of black/African American male with clear cell renal cell carcinoma:
  - ef700f61-d8b0-43d0-92d1-feec949adc72.htseq.counts.gz
  - 175e2233-28a0-47c7-b395-19dd033b79d8.htseq.counts.gz
  - 7223f19a-017e-465b-b81b-bed54252c6b0.htseq.counts.gz
  - 1e69236e-5526-4bf1-8de5-35d50a71f227.htseq.counts.gz
  - 6e264598-c25a-4d37-aa61-e3042c2265be.htseq.counts.gz
  - 0ade05fe-5f98-477d-b7fa-c56ea93247cf.htseq.counts.gz
  - 13fe6d54-192b-4e93-92a8-02ab20e589ed.htseq.counts.gz
  - 3c5c3b14-62d4-431a-ba60-cf2eb96d7e8a.htseq.counts.gz
  - 01ae4201-f15c-4790-a7ea-41290808c5fa.htseq.counts.gz
  - 5d065eaa-e3a8-420e-b983-c1a80e713ac9.htseq.counts.gz
  - 208e8d62-0277-404e-9246-55d36eb3ec7d.htseq.counts.gz
  - 891f9d70-e716-4fc9-b53e-f120da74eea3.htseq.counts.gz
  - dba87d20-a3ed-4ca3-93f7-0fe979f7923a.htseq.counts.gz
  - 9f2932d6-bb5c-4ce0-9ea7-281a459fb64a.htseq.counts.gz
  - 38096336-4257-481c-b653-91804af5b2a1.htseq.counts.gz

## Milestone 1
- I want to filter ten data files of white male and ten data files of black/African American from GDC Data Portal. Then, I want to download the data files in HT-seq format and import them into R.

## Milestone 2
- I want to analyze tha data that can turn raw counts into biological insights and generate some plots.

## Deliverable:
- R Markdown
