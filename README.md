# Species Distribution Models for Mesopelagic Mesozooplankton Community🪼🐟🦐

## Introduction
This repository contains the code distribution of mesopelagic mesozooplankton using species distribution models. The main goal is to understand species richness, range-size rarity, and their relationship with environmental variables such as temperature, salinity, and nutrient levels.We aimed to enhance our understanding on distribution of mesopelagic mesozooplankton using species distribution models, assess the performance of various modelling techniques, identify key environmental predictors for mesopelagic mesozooplankton distribution, and compute their habitat suitability indices

## Project Structure💾

#### Data📑

This repo contains a sample data how to prepare the required files to run SDM models. We use *Acanthephyra acanthitelsonis* as an example of a workflow

- **data/** - available to download: Egorova, Yulia (2024). Species Distribution Models for Mesopelagic Mesozooplankton Community. figshare. Journal contribution. [https://doi.org/10.6084/m9.figshare.26499265.v1](https://doi.org/10.6084/m9.figshare.26499265.v1)

#### Scripts📜
- **scripts/**
  - `fun/theme_Publication.R`: Custom theme for publication-quality plots.
  
#### Notebooks📒
- `script.Rmd`: Main RMarkdown file containing the analysis and plots.
- `01-DataPrep.Rmd`- script that shows teh datat prepartaion process using example from single species *Acanthephyra acanthitelsonis*
- `02-RunModels.Rmd`- code to run SDM models using teh full data.

#### Outputs🎨
- **img/**
  - Contains the generated figures and plots from the analysis.

## Installation🔧

If you need to set up the environment on a different machine or restore it to a previous state, use the restore function:
```r
renv::restore()
```
