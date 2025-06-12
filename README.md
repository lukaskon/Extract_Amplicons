HOW TO USE:

You need two files:
1) "genome_list.txt" containing a list of full paths to genomes ending in ".fasta".
2) A fasta file of your primers with the headers labeled "FWD" and "REV" only. The basename is anything before "_primers.fasta" in the file name.

You can change the max amplicon size and the number of primer mismatches allowed. Edit array to the number of genomes you have in the list.

Outputs to a new directory with the name of the primer:
1) Directory called "hits" with all blast hits and filtered results,
2) Directory called "amplicon_fasta" containing the predicted amplicon for each genome, if it has one.
3) File called summary_primer.tsv with the headers Genome, Size, Multiple.
