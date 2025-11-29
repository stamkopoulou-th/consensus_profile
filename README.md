# Consensus Sequence and Profile Matrix

This Python script computes the **consensus sequence** and **nucleotide profile matrix** from a collection of DNA sequences in FASTA format.  
Inspired by the **Rosalind "Consensus and Profile" problem**.



## Features

- Reads a FASTA file containing DNA sequences.
- Computes the **profile counts** (number of A, C, G, T nucleotides at each position).
- Determines the **consensus sequence** based on the profile.
- Prints both the consensus sequence and the profile counts in a readable format.



## Input

- A FASTA file (`.fasta`) containing **one or more DNA sequences of equal length**.  



## Output

- **Consensus sequence** – a string representing the most common nucleotide at each position.  
- **Profile matrix** – number of each nucleotide at each position across all sequences.  
