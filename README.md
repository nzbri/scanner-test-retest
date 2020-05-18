# scanner-test-retest
MRI Scanner test and retest before and after moving to a new location
This is the analysis script to accompany the manuscript: "Test-retest reliability and sample size estimates after MRI scanner relocation".

'Scanner_move_R_analysis.Rmd' is the rmarkdown analysis script. This script loads all the other csv files.

scanner_move_R.csv: average DTI metrics along the white matter skeleton (FA=fractional anisotropy, MD=mean diffusivity, AD=axial diffusivity,
RD=radial diffusivity). 

CorticalMeasuresENIGMA_SurfAvg.csv & *_ThicknAvg.csv: average thickness and surface area from the Desikan-Killiany Freesurfer regions.
Subcort_vol.csv: Freesurfer-derived subcortical volumes + global GM/cortical/subcortical/WM/ventricle volumes.
scbf_cortex.csv & scbf_sub_cort: Perfusion values from the Desikan-Killiany parcellations.
sample_size_table_R1.csv: Sample size estimates for plotting.
dice_cortex.cvs: The dice similarity coefficients comparing the cortical segments between and within-sites.

