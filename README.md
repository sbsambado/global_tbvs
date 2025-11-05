# global_tbvs

**Manuscript title:** Ecological and socioeconomic factors associated with globally reported tick-borne viruses

**Corresponding author:** Samantha Sambado (sbsambado at ucsb.edu, ssambado at stanford.edu)


**software:** R version 4.4.1 (2024-06-14)

**packages:** countrycode_1.6.1, easyPubMed_2.13, gbm_2.2.2, ggplot2_4.0.0, ggpubr_0.6.0, InformationValue_1.3.1, janitor_2.2.0, lubridate_1.9.3, naniar_1.1.0, openxlsx_4.2.7.1, patchwork_1.3.0, plotrix_3.8-4, readr_2.1.5, RColorBrewer_1.1-3, rgho_3.0.2, rnaturalearth_1.0.1, ROCR_1.0-11, rsample_1.2.1, rworldmap_1.3-8, scales_1.4.0, sf_1.0-21, stringr_1.5.2, terra_1.8-70, tidyverse_2.0.0, wbstats_1.0.4

**Scripts**
+ 1_Data_Cleaning_TraitMatrix.Rmd: script to process raw covariate data from various sources. Will need data files from `trait_matrix`.
+ 2_DataCleaning_ZOVER.Rmd: script to process raw outcome data from ZOVER. Will need data files from `tickviruses`.
+ 3_Analysis_BRT.Rmd: script to format, run, and diagnose boosted regression tree models
+ 4_Results_SummariesTables.Rmd: script to recreate tables and within text results.
+ 5_Figures.Rmd: script to recreate figures from main and supplementary text.

For more in depth data descriptions please see Dryad repository: https://doi.org/10.5061/dryad.1g1jwsv9w. 
