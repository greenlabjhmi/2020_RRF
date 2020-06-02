# 2020_RRF

The codes to process and analyze FASTQ files obtained from standard ribosome profiling, high-salt ribosome profiling, and RNAseq for the ribosome profiling study of RRF. First run “RRF_DP_Skewer_Bowtie_Density_RPKM” for data processing, then run codes for data analyses.
Dependencies
	•	skewer-0.2.2
	•	bowtie-1.1.2
	•	python 2.7
	•	Anaconda2-5.0.1
	•	Jupyter notebook
	•	pickle
	•	numpy
	•	scipy
	•	pandas
	•	matplotlib
	•	seaborn


Data processing and analyses
	•	RRF_DP_Skewer_Bowtie_Density_RPKM - linker trimming, chromsome mapping, and calculation of RPMs and RPKMs
	•	RRF_DA_makeCSV - makes a spreadsheet of reads and RPKMs
	•	RRF_DA_3UTRscore - calculates 3UTR scores 
	•	RRF_DA_AGP - creates average gene plots on stop codons
	•	RRF_DA_Collision_3UTR - calculates Collision scores and 3UTR scores of high TE genes and low TE genes
	•	RRF_DA_RPMplot - creates bar graphs of rpm
	•	RRF_DA_updown - calculates fold difference of RPKMs of upstream and downstream genes
	•	RRF_DA_upregulated_scatter - compared RPKMs from the wild type and the RRF KO strain and identify upregulated genes in KO strain 


