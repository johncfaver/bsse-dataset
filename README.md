This is a dataset for building empirical models for fast BSSE estimation.

It was used in:
Faver, J. C., Zheng, Z, Merz, K. M. Model for the Fast Estimation of Basis Set Superposition Error in Biomolecular Systems 
	     Journal of Chemical Physics, 2011, 135, 144110.10.1063/1.3641894

Chemical structures are fragments generated from proteins in the PDB.
There are four folders for different interaction types:

	p=polar (peptide backbone-backbone hydrogen bonds)
	np=nonpolar
	pc=positively charged (cationic)
	nc=negatively charged (anionic)

Each folder contains xyz files for each monomer in the data set, and a CSV file with each fragment's name, and BSSE at mp2/6-31G* and mp2/aDZ in kcal/mol.

