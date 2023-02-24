# Python for Biomedical Data Statistical Analysis
### CCU 2020 Autumn Course
Instructor: Cheng-ChungChou

## Project 1: Finding Restriction Enzyme Cut Sites in a DNA Sequence and Identifying Suitable Enzymes for Cloning

This project involves developing a program that can identify restriction enzyme cut sites in a given DNA sequence and print the names, cut sequences, start and end positions of the enzymes found. The program requires the user to input the filename of a `Fasta` file containing the DNA sequence. The code will scan the entire sequence for the cut sites of the enzymes provided in the `enzymes` variable. If any cut sites are found, the program will print the necessary information.

Furthermore, the project also requires identifying suitable `restriction enzymes` for cloning the DNA sequence into a plasmid with a multiple cloning site (MCS). Given that the CDS of the MCS is from position 84 to 2123, the program should output the names of the enzymes in the "enzymes" variable that have cut sites within this range.

File required: `hsp70.txt`
Variables required: `enzymes` (can be set to any data type)

## Project 2: Gene Expression Analysis

### 2.1 Differential Expressed Gene Analysis Using Microarray Data

The project is to perform a differential expressed gene analysis on microarray data. We are required to input the data `array_data.csv`. The data is then pre-processed to subtract background values, filter out unreliable extreme values, and normalized using global normalization. The expression analysis is then conducted by taking the ratio of normalized signals between cancerous and normal tissue, which is then transformed using `log2`. Finally, the top five upregulated and downregulated genes, along with their log2 ratios, are identified. This analysis can provide insights into the molecular mechanisms underlying cancer development and progression.

### 2.2 Clustering by gene expression

In this project, we are provided with gene expression data of different subtypes of lung cancer including small cell lung cancer (SCLC), non-small cell lung cancer (NSCLC) with further subtypes including large cell carcinoma (LCLC), squamous cell carcinoma (SCC), and adenocarcinoma (Adeno/AC). The `clustered.csv` file contains 70 samples (columns) with 258 genes (rows) and the first column records the gene names while the first row records the subtype of lung cancer. The `unknown.csv` file contains the gene expression of 258 genes for a patient X, but we do not know which subtype of lung cancer it belongs to.

We are required to use clustering methods to determine which subtype of lung cancer the unknown sample belongs to and provide evidence for our decision. The answer should be printed as "X belongs to..." along with the reasoning. The provided files needed for this project are `clustered.csv` and `unknown.csv`. The functions that may be used include `.join(), .concat(), and .append()`.

## Project 3. Similarity comparison





