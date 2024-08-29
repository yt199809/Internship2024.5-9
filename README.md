## For who use the scripts

Be caution when you use the script, cause it is a 'mediocre' work hhhhh!!! The codes are used to explore microbial signature. 
(It gradually turns out to be digging AMR genes, although I do not think it is doable and this is definitely a wrong dataset to use)

## Aims of the codes

In this internship, it uses bulk transcriptome from study of Joanito et. al (2022). (https://doi.org/10.1038/s41588-022-01100-4)

This is a single cell papers that they use bulk transcriptome to validate their finding of two tumor cell state iCMS2 and iCMS3. 

Let's see the dataset is used in the internship. 

Due to the publishment  famous Poore et al. 2020 paper (In their paper they used TCGA WGS data and machine learning method to distinguish different cancers by the microbiome on it ), digging microbiome data in cancer tissue become very popular.  This paper was retracted in 2024 because other scientists found there are problems happened in the reference database, so there are human reads recognized as microbial reads. The guy even opened an company, but now it is possibly  broken. 

Sad story.

But still, there are quite a lot of people interesting in digging these data, like this group. And that's why they try to utilize this bulk transcriptome to explore microbiome and even ARGs……..

It is known that in these kind of data, only 2-3% of the sequences are microbial data, within these microbial data, 80-90% are rRNA. Therefore, it can be really hard to investigate mRNA expression data.
Therefore, it is almost beyond wildest dream using the data to study AMR and their expression, especially imagine how many microbes will penetrate the cell and how many of them have ARGs......
Anyway.

In this project, the code will be used to explore microbial signature between MSI and MSS CRC (colorectal cancer) subtypes .
The decotamination process was done with a pipline made by another student Birgit called CanMicrob. Import data will be the abundance feature table outputed by a kraken/braken combination.

That's the info.
