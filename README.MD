# README

## Instruction
This repository contains the analysis from group 4 for the course **Hands-on metagenomics using Oxford Nanopore DNA sequencing (2021)** at Aalborg University

```{bash}
git clone git@github.com:matinnuhamunada/AAU_metagenome_course.git
```

Download the data to `data/` folder. **Please update the dropbox link for group 4 data!**

```{bash}
cd AAU_metagenome_course
wget {dropbox link here} -O data.zip
unzip data.zip
mv group_4 data/
```

## Using renv to reproduce R dependencies

Launch new project in the cloned directory. When it first launches in this project, `renv` should automatically bootstrap itself, thereby downloading and installing the appropriate version of `renv` into the project library. After this has completed, use `renv::restore()` to restore the project library locally on their machine.

Find more information here: https://rstudio.github.io/renv/articles/collaborating.html

## Slides
- Please find the slides here: https://docs.google.com/presentation/d/1-R4Rth3KXFEnMgla0WLaye8rcdBxiyhp3pHSjuHqvbQ/edit?usp=sharing 

## Notebooks
- [Rodent virus contigs](https://htmlpreview.github.io/?https://github.com/matinnuhamunada/AAU_metagenome_course/blob/main/2021-12-09_matinnu-analysis.html)
