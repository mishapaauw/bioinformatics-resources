# bioinformatics-resources

Useful bioinformatics resources, collected from diverse sources (blogs, Bluesky, papers, etc...). Might make a nice browsable page in the future, for now I just use this rendered README file on github.

## Data visualization

* [tidyplots](https://jbengler.github.io/tidyplots/index.html)
* [tidyheatmaps](https://jbengler.github.io/tidyheatmaps/index.html)
* [Practical considerations for data exploration in quantitative cell biology](https://journals.biologists.com/jcs/article/138/7/jcs263801/367617/Practical-considerations-for-data-exploration-in)
* [From zero to figure hero. A checklist for designing scientific data visualizations](https://arxiv.org/abs/2408.16007)
* [vayr](https://alexandercoppock.com/vayr/): `position_sunflower` for visualizing count data (e.g. number of infected hydathodes)
* [Slidecrafting with Quarto](https://slidecrafting-book.com)

## Genome browsers

* [JBrowse](https://jbrowse.org/jb2/download/#rshiny-widget) and [JBrowseR](https://gmod.org/JBrowseR/articles/JBrowseR.html)

## Bioinformatics 

* [Todos Santon computational biology workshop (1 week)](https://dbsloan.github.io/TS2019/)
* [Plotting SRA NCBI data size](https://pascal-martin.netlify.app/post/plotting-sra-database-growth/)
* [Deeptools](https://deeptools.readthedocs.io/en/latest/) Python fastq mapping visualization (See also [scPlants workshop material](https://colab.research.google.com/gist/maschon0/1021e74784527015d442b625585b4ef5/scplants_practical_0.ipynb#scrollTo=2hwc_B1Vz3PY))
* [Finding overrepresented taxa in microbiome data](https://github.com/feargalr/TaxSEA)

## Pipeline tools

* [Tips for running nextflow on HPC](https://gencore.bio.nyu.edu/nextflow-nf-core-on-nyu-hpc/)
* [Snakemake tutorial](https://farm.cse.ucdavis.edu/~ctbrown/2023-snakemake-book-draft/chapter_3.html) from UCDavis.

## Terminal commands tutorials

* [Six glorious unix commands](https://astrobiomike.github.io/unix/six-glorious-commands)
* [Sandbox tutorial: terminal basics](https://sandbox.bio/tutorials/terminal-basics)
* [Sandbox tutorial: DNA quality control and trimming](https://sandbox.bio/tutorials/fastp-intro)

## GWAS

* [vcf2GWAS](https://academic.oup.com/bioinformatics/article/38/3/839/6390796)
* [GWAS on Capeverdian Arabidopsis accessions](https://www.science.org/doi/10.1126/sciadv.adq8210)

## Plant genome resources

* [*Arabidopsis* long read genomes](https://www.biorxiv.org/content/10.1101/2024.12.23.629943v2.abstract)
* [Plant genomics tool overview](https://github.com/bpucker/ToolOverview), with associated [preprint](https://www.preprints.org/manuscript/202402.0645/v1)
* [Potato pangenome](https://www.nature.com/articles/s41586-025-08843-0)
* [Tomato pangenome](https://www.nature.com/articles/s41588-023-01340-y)
* [Many more plant pangenomes](https://www.nature.com/articles/s41576-024-00691-4)
* [Major orthofinder upgrade](https://bsky.app/profile/lauriebelch.bsky.social/post/3lu3y7blig22j)


## Bacterial genome analysis

* [seabreeze](https://joss.theoj.org/papers/10.21105/joss.08065.pdf): analyzing structural variation between bacterial genome assemblies

## Statistics and experimental design

* [A reckless guide to p-values](https://link.springer.com/chapter/10.1007/164_2019_286)
* [Thoughtful experimental desing in the omics era](https://www.nature.com/articles/s41467-025-62616-x)

## Data management

* [Science Park Study Group draft lesson on data management](https://scienceparkstudygroup.github.io/research-data-management-lesson/03-plan-project-and-file-management/index.html)

## Mini code snippets

Connecting to Crunchomics (I always forget this one):
```bash
ssh -X mpaauw@omics-h0.science.uva.nl
```