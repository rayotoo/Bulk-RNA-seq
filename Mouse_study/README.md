# Bulk-RNA-seq
[![LICENSE](https://img.shields.io/github/license/rayotoo/Bulk-RNA-seq?style=flat-square&color=green)](https://github.com/rayotoo/Bulk-RNA-seq/blob/main/LICENSE)
[![GitHub issues](https://img.shields.io/github/issues/rayotoo/Bulk-RNA-seq?style=flat-square)](https://github.com/rayotoo/Bulk-RNA-seq/issues)
[![GitHub stars](https://img.shields.io/github/stars/rayotoo/Bulk-RNA-seq?style=flat-square&color=important)](https://github.com/rayotoo/Bulk-RNA-seq/stargazers)
[![GitHub forks](https://img.shields.io/github/forks/rayotoo/Bulk-RNA-seq?style=flat-square&color=blueviolet)](https://github.com/rayotoo/Bulk-RNA-seq/network/members)

This resource demonstrates with a step-by-step tutorial, an end-to-end RNA seq pipeline. Generally, from my experience, having a reproducible bioinformatics pipeline has been very difficult to achieve. As a results, curious learners often times find it difficult to navigate through and complete most of the very few complete bioinformatics analysis pipelines. To address this challenge, this resource is being developed. To resolve the reprodicibility challenges resulting from dependencies conflicts, this tutotial together with all of the resources contained herein will be containerized using docker. 

At the end of this tutorial, you will have had a complete step-by-step walk through of an RNA-seq pipeline with a full real world example. Data used is from and insect and as such presents an opportunity to be able to run the entire analysis on your personal computer (since the genome is fairly small). 

# Work in progress...

# General RNA-seq workflow overview
Insert workflow image here...


# General RNA-seq workflow
- Preprocessing - Raw data QC 
- Mapping/quantification
- Sample-level assessment
- Count modeling and hypothesis testing
- Visualization of results
- Functional analysis

# Data
- Data used for this study is from a mouse study.12 fastq files with 1000 reads each, 4 index files for chr 1 for mm10, targets files with sample information
- Data: Mouse mammary data (fastq files): https://figshare.com/s/f5d63d8c265a05618137
- Read the paper to better understand the data.
