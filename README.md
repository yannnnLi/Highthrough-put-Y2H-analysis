# Highthrough-put-Y2H-analysis
The program to analyze highthrough-put sequecing data generated from Y2H experiment to find PPIs

We present a highthrough-put yeast two hybird systems to detect protein-protein interactions of non-model biology. The programe to analyze the 2nd and 3rd sequencing data are as follow:

2nd: y2h_2nd.py

3rd: y2h_3rd.py

Moreover, for the 3rd sequencing data, we design more strict standards to filter PPIs, leveraging long reads of Pacbio sequencing. As the result the sequence of primer, reconbination site(ATTL) and their reverse complement sequence are necessary in the current directory.

ORFchecker.py
The script is used to check if the protein coding sequence in the plastid comply with the ORF of protein coding gene of maize.
