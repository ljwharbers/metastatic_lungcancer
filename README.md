# Metastatic Lungcancer
Scripts and pipelines used for the analysis of 'Comparative genomic profiling identifies targetable brain metastasis drivers in non-small cell lung cancer'

# Preprocessing
In the folder `preprocessing` you can find all the snakefiles used to preprocess all data (demultiplexing, alignment, sorting, etc.). Simply edit the config file with the required paths to run the preprocessing. Due to patient confidentiality, raw `fastq` files are not included. 

# Analysis
In the folder `analysis` you can find all data required to regenerate all the plots used in this manuscript. You can also find an `Rmarkdown` file that can be run with this data to generate the plots. The plots are also already available in the `plots` subdirectory. 

Any questions can be emailed to luuk.harbers@scilifelab.se