# Bayesian methods in meta-analysis and prior sensitivity

This repository documents my work conducting a bayesian meta-analysis on the effect of ivermectin as a treatment for COVID-19,
following https://statmodeling.stat.columbia.edu/2022/02/28/answering-some-questions-about-meta-analysis-using-ivermectin-as-an-example/. 
This meta-analysis also includes a prior sensitivity analysis, focusing on the effect of using weakly informative priors.
I draw from the work of https://psyarxiv.com/7tbrm/, in the selection of priors for the sensitivity analysis.

The report written from this work will be made available soon, hopefully as a bookdown document. For now, this repository contains the code necessary
to reconstruct the results. The scripts to do so are src/meta_analysis_stan_gelman_ivermectin.R and src/meta_analysis_stan_functions.R. The data used for 
the meta-analysis is found in src/gelman_meta_analysis_data.txt.

The script src/meta_analysis_markdown.RMD can also be used to reproduce the results and a cursory version of the final report.

