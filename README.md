# Preprocess_pdb_files

Use these file to set up PDB files for use. 

Necessary input:
- File containing list of PDB codes to use, one per line

Neceseary software: Reduce, see instructions to download and install

Output:
- PDB file with hydrogen added for each protein

What does the code do:
1. Removes heteroatoms from the protein
2. Removes alternative configurations
3. Adds hydrogen atoms
