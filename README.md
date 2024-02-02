# RNAseq

# In vivo RNA-Seq raw data location
The fastq files can be found in the Salvör-phd2 hard drive or in ELja: 

´´´
"E:\RNAseq_rawdata_novogene_invivo_hc_ctx\01.RawData\Ctx_1F0_32"
"hpcdata/Mimir/sar10/rnaseq_invivo_32_37"
´´´

# In vivo RNA-Seq alignment
We used kallisto on ELja to align the transcript to the refernce genome. 
kimberley had already made an index file which can be found at: /hpcdata/Mimir/kimberl/mm39_ncRNA_cDNA.idx 

´´´
kallisto quant -i transcripts.idx -b 100 -t 65 -o [file.name] - [file.name]reads_1.fq.gz [file.name]reads_2.fq.gz
´´´

# DESeq analysis 


