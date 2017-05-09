# GWAS-in-Crop-Species

This objective for this project is simulate and compare GWAS power in different crop speices under vairous situations including number of QTNs, effect values, and heritability.  
All the files about this project are located at `/work/schnablelab/cmiao/GWAS-in-Crop-Species` in UNL HCC crane cluster.

We collected several crop spieceis genotype data from published papers
- *[Sorghum bicolor](http://advances.sciencemag.org/content/1/6/e1400218.short)*
  - including **1,943** georeferenced landraces and **404,627** SNPs
  - Genotyping-by-sequecing with 23% having MAF < 0.01 and 65% of SNPs having MAF < 0.1.
- *[Setaria italica](http://www.nature.com/ng/journal/v45/n8/abs/ng.2673.html)*
  - including **916** diverse varieties and **726,080** SNPs
  - low coverage genome resquecing with about 0.7X.
- *[Oryza sativa](https://www.nature.com/articles/ncomms10532)*
  - A total of **1,568** rice accessions and **700,000** SNPs.
  - using micro-array technology.
- *[Zea mays Whole genome resquecning](http://biorxiv.org/content/biorxiv/early/2015/09/16/026963.full.pdf)*
  - The paper wasn't published.
  - This data also contains other close species, like teosinte and tripsacum.
  - **916** maize lines and **60 million** SNPs
  - whole genome resquencing technology with 1X ~ 46X
- *[Zea mays GBS](https://genomebiology.biomedcentral.com/articles/10.1186/gb-2013-14-6-r55)*
  - **2,815** maize inbred accessions and **681,257** SNPs
  - Genotyping by sequencing technology was used

All the raw genotype data are loated at `/work/schnablelab/cmiao/GWAS-in-Crop-Species/Genotypes` with a readme file describing the data resource in each speices directory.
