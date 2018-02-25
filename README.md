The ReCounts project <http://bowtie-bio.sourceforge.net/recount/> is a Johns Hopkins University project that has made the transcript counts of processed RNA-Seq data from multiple published papers publicly available. My objective in the current project is to download and analyze the count data for one paper in particular: *"Transcript assembly and quantification by RNA-Seq reveals unannotated transcripts and isoform switching during cell differentiation."* by [Trapnell et. al., 2010](https://www.ncbi.nlm.nih.gov/pubmed?term=20436464).


The Trapnell paper performed RNA-Seq on the cell line C2C12 from C57BL/6 mice at 4 time points during a time course experiment. Cells were cultured in 20% fetal bovine serum in DMEM until confluent and then switched to low serum medium for 168 hours. The time points sampled were -24, 60, 120, and 168 hours after switching to low serum medium.


Differential expression analysis was performed on these data.


The dependencies for this project are as follow:


R version 3.4.3 (2017-11-30)
Platform: x86_64-w64-mingw32/x64 (64-bit)
Running under: Windows >= 8 x64 (build 9200)

Matrix products: default

locale:
[1] LC_COLLATE=English_United States.1252  LC_CTYPE=English_United States.1252   
[3] LC_MONETARY=English_United States.1252 LC_NUMERIC=C                          
[5] LC_TIME=English_United States.1252    

attached base packages:
[1] stats     graphics  grDevices utils     datasets  methods   base     

loaded via a namespace (and not attached):
 [1] compiler_3.4.3  backports_1.1.2 magrittr_1.5    rsconnect_0.8.5 rprojroot_1.3-2 htmltools_0.3.6
 [7] tools_3.4.3     yaml_2.1.16     Rcpp_0.12.15    stringi_1.1.6   rmarkdown_1.8   knitr_1.18     
[13] stringr_1.2.0   digest_0.6.14   evaluate_0.10.1
