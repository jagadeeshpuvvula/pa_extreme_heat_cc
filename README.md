# Pediatric Risk Mapping from Co-Exposure to Extreme Temperatures and Air Pollutants

# R version and dependencies
R version 4.5.0 (2025-04-11 ucrt)
Platform: x86_64-w64-mingw32/x64
Running under: Windows 11 x64 (build 26100)

Matrix products: default
  LAPACK version 3.12.1
  
attached base packages:
[1] stats     graphics  grDevices utils     datasets  methods   base     

other attached packages:
 [1] RANN_2.6.2           scales_1.4.0         patchwork_1.3.2      ggpattern_1.2.1      broom_1.0.10        
 [6] ncdf4_1.24           fs_1.6.6             httr_1.4.7           glue_1.8.0           terra_1.8-60        
[11] prism_0.2.3          biscale_1.1.0        cowplot_1.2.0        plotly_4.11.0        umap_0.2.10.0       
[16] spdep_1.4-1          spData_2.3.4         raster_3.6-32        sp_2.2-0             psych_2.5.6         
[21] GPArotation_2025.3-1 Rtsne_0.17           keras_2.16.0         ggcorrplot_0.1.4.1   gridExtra_2.3       
[26] ggfortify_0.4.19     factoextra_1.0.7     knitr_1.50           reshape2_1.4.4       viridis_0.6.5       
[31] viridisLite_0.4.2    tigris_2.2.1         sf_1.0-21            janitor_2.2.1        tidycensus_1.7.3    
[36] lubridate_1.9.4      forcats_1.0.0        stringr_1.5.2        dplyr_1.1.4          purrr_1.1.0         
[41] readr_2.1.5          tidyr_1.3.1          tibble_3.3.0         ggplot2_4.0.0        tidyverse_2.0.0     
[46] pacman_0.5.1         usethis_3.2.1       

loaded via a namespace (and not attached):
 [1] RColorBrewer_1.1-3 tensorA_0.36.2.1   rstudioapi_0.17.1  jsonlite_2.0.0     wk_0.9.4           magrittr_2.0.4    
 [7] farver_2.1.2       rmarkdown_2.29     vctrs_0.6.5        askpass_1.2.1      base64enc_0.1-3    htmltools_0.5.8.1 
[13] s2_1.1.9           KernSmooth_2.23-26 htmlwidgets_1.6.4  plyr_1.8.9         uuid_1.2-1         whisker_0.4.1     
[19] lifecycle_1.0.4    pkgconfig_2.0.3    Matrix_1.7-4       R6_2.6.1           fastmap_1.2.0      snakecase_0.11.1  
[25] digest_0.6.37      RSpectra_0.16-2    latex2exp_0.9.6    tfruns_1.5.4       timechange_0.3.0   compiler_4.5.0    
[31] proxy_0.4-27       withr_3.0.2        S7_0.2.0           backports_1.5.0    DBI_1.2.3          hexbin_1.28.5     
[37] tensorflow_2.20.0  MASS_7.3-65        bayesm_3.1-6       openssl_2.3.3      rappdirs_0.3.3     classInt_0.4-11   
[43] tools_4.5.0        units_0.8-7        nlme_3.1-168       grid_4.5.0         generics_0.1.4     gtable_0.3.6      
[49] tzdb_0.5.0         class_7.3-23       data.table_1.17.8  hms_1.1.3          xml2_1.4.0         ggrepel_0.9.6     
[55] pillar_1.11.1      robustbase_0.99-6  lattice_0.22-7     deldir_2.0-4       compositions_2.0-9 tidyselect_1.2.1  
[61] xfun_0.53          DEoptimR_1.1-4     proto_1.0.0        stringi_1.8.7      lazyeval_0.2.2     yaml_2.3.10       
[67] boot_1.3-32        evaluate_1.0.5     codetools_0.2-20   cli_3.6.5          reticulate_1.43.0  Rcpp_1.1.0        
[73] zeallot_0.2.0      png_0.1-8          parallel_4.5.0     e1071_1.7-16       crayon_1.5.3       rlang_1.1.6       
[79] rvest_1.0.5        mnormt_2.1.1