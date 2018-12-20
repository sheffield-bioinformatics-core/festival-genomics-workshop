FROM bioconductor/release_base2:R3.5.1_Bioc3.8
MAINTAINER Mark Dunning<m.j.dunning@sheffield.ac.uk>
RUN R -e 'install.packages("BiocManager")'
RUN R -e 'BiocManager::install("tidyverse")'
RUN R -e 'BiocManager::install("VariantAnnotation", version = "3.8")'
RUN R -e 'BiocManager::install("TxDb.Hsapiens.UCSC.hg19.knownGene", version = "3.8")'
RUN R -e 'BiocManager::install("org.Hs.eg.db", version = "3.8")'
RUN R -e 'BiocManager::install("BSgenome.Hsapiens.UCSC.hg19", version = "3.8")'
RUN R -e 'install.packages("devtools")'
RUN R -e 'devtools:::install_github("sheffield-bioinformatics-core/sbcMisc")'
RUN R -e 'devtools::install_github("cttobin/ggthemr")'
RUN R -e 'install.packages("caTools")'
RUN R -e 'install.packages("rprojroot")'
