Genome sequence analysis of several organisms and high throughput screening of X-ray structure analysis provided scientific information about structural and sequence information of several proteins which are applicable in understanding fundamentals of evolution theories and structure predictions. In a broader sense, sequence analysis is the simplest approach for discovering structural, functional and evolutionary relationships of proteins. Alignment-based approaches for comparing protein sequence included algorithm to produce alignments and amino acid substitution matrices for scoring aligned amino acid residues.  

A biological sequence alignment represents relationship between a pair of deoxyribonucleic acid (DNA) or protein sequences. It compares two or more sequences by finding series of individual patterns in the same order of sequences of interest. In global sequence alignment, the entire sequence (end to end) is aligned in the given query or target sequence. Sequences having approximately same length or quite similar sequences, which is closely related sequences were suitable for global alignment. This includes comparison of homologous genes or proteins with similar function. A general global alignment technique is Needleman – Wunsch algorithm. In local alignment, distantly related sequences were aligned to find out regions with highest similarity in sequences identify conserved regions. The Smith- Waterman algorithm is a general local alignment algorithm. Needleman-Wunsch and Smith-Waterman algorithms for sequence alignment are dynamic programming approach as the alignment was performed in a more quantitative manner. Basically all alignments needs to have comparisons for matches and mismatches and scoring matrices are aligned to have scores for sequence comparison. In 1970’s, constructing scoring matrices has become a key aspect in sequence alignment and comparison, psychochemical and three-dimensional structural properties of aminoacids were taken to consideration for computing scoring matrices. The scores in the matrix were integer values, were positive score indicates similar or identical sequences, and negative or zero score indicates dissimilar pairs. This represents simplest scoring scheme and is noted as identity scoring matrix. In molecular biology, scores are defined as sequence similarity. There are many other scoring matrices which are predefined mostly, used in the case of amino acid substitutions. In general, an alignment score defines sum of scores given for pairs of nucleotide or amino acids substitution scores in a sequence alignment and gap scores for null characters inserted in a sequence. There are different ways that introduce mutational process in aminoacids that leads to aminoacids substitutions, including, altering of DNA sequence that encodes a specific protein, changes in the chemical properties of aminoacids, silent and non-silent substitutions in the given sequences. 

Scoring matrices that were used ad default parameters in alignment tools such as EMBOSS Needle, Clustal Omega, Muscle, T-Coffee, MAFFT and homology search tools such as FASTA, BLAST are termed as General purpose amino acid substitution scoring matrices. Examples include PAM, BLOSUM, MD and VTML series of matrices. 
&nbsp;

&nbsp;


**Percent/Point Accepted Mutation (PAM)**
&nbsp;

Margaret Dayhoff and co-workers introduced PAM model in 1978, a family of substitution matrices which were aligned by PAM distance, a unit of evolutionary divergence. It was derived from global alignments of protein families that share at least 85% identity. PAM is a substitution of one amino acid in the primary structure of protein by another aminoacid that which has been accepted by evolution. In PAM matrix, each column and row represents twenty standard aminoacids translated by the genetic code. The value in each cell of a PAM matrix represents the probability of a row amino acid before the mutation being aligned with a column amino acid after the mutation. The frequency or the probability one residue substitutes another one is an indicator of their similarity. 'PAMn matrix' denotes the PAM matrix that corresponds to a time frame for n mutations occuring per 100 amino acids (1 accepted point mutation per 100 residues = PAM1,that is specifically 1% change and 99% remains as such). PAMn matrix is obtained from PAM1 Markov model assumption of protein evolution where transition probabilities in 1 PAM step are given by PAM1. Other PAM matrices are extrapolated from PAM 1 matrix.
&nbsp;

•	PAM matrix rely on explicit evolutionary model.
&nbsp;

•	Based on global alignments of sequences for finding mutations including highly conserved and highly mutable regions of closely related proteins.&nbsp;

•	Higher PAM numbers denotes larger evolutionary distances.
&nbsp;


**BLOSUM**
&nbsp;
&nbsp;

BLOSUM (BLOck SUbstitution Matrices) were developed by Henikoff and Henikoff in 1992. It was based on highly conserved local alignment of sequences. BLOSUM matrices have ungapped alignments;blocks., that were derived from evolutionary divergent family of protein sequences. Blocks represents the conserved regions within related proteins that were assumed to be of higher functional relevance. More constrained regions of amino acid sequences were likely have related structure and function. Aminoacid substitution frequencies in bocks were calculated to produce a numeraical table, block substritution matrix. Lower value of BLOSUM number indictaes more divergent sequences. BLOSUM 62 is the most widely used matrix. BLOSUM 62 indicates protein sequences clustered with greater than 62% identity and BLOSUM 80 indicates sequences clustered with greater than 80% identity. Positive BLOSUM score in matrix indicates substitutions occurring more frequently than expected in evolutionary conserved replacements. Larger numbers in matrices denotes higher sequence similarity and smallest evolutionary distances. 
