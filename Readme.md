# Assignment 3
## Name: Shreya Ekande
## Date: 03/19/2024


## Programming language: Python version 3.11.5


## Dependencies: Pandas, Seaborn, Matplotlib
## Input: DecayTimecourse.txt
## Output: B_subtilis_operons.txt, E_coli_i.txt, Halobacterium_operons.txt, Synechocystis.txt, Microbiome,txt

# Project Description:
This project aims to predict operons, defined as longest contiguous multi-gene transcriptional units, using PTT files for various genomes. The genomes included in this analysis are:
1. Escherichia coli K12
2. Bacillus Subtilis
3. Halobacterium
4. Synechocystis

Additionally, operon prediction will be performed on a crop microbiome from Hoatzin using a GFF file (equivalent to a PTT file).

# Script Description:  
1. **Reading Data**: I have written a fucntion to convert ptt file into csv file. Then I converted all the input ptt files into csvs. 

2. **Data Cleaning**: I have cleaned the data by dropping the unwanted columns. I created start and end columns by splitting the Location column and assigning it to new Start and End columns. 

3. **Data Preprocessing**: 

 


