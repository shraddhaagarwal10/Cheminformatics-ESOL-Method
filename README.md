# Cheminformatics-Predicting-Aqueous-Solubility-of-Molecules
AIM:

The project aims to determine the aqueous solubility of the compounds directly from their structures. The model was built using 1144 observed solubilities and tested against eight molecular properties using linear regression and artificial neural networks.

INTRODUCTION:

One of the most important physical characteristics of a medicinal or agrochemical chemist is aqueous solubility. Solubility influences the absorption and dispersion of physiologically active chemicals in living matter and the environment, influencing their efficacy and marketability. It is helpful to measure solubility in the absence of a physical sample since accurate equilibrium solubility assessment is a time-consuming experiment.
Many techniques for predicting solubility have been devised, either based simply on chemical structure or employing more easily acquired data. Techniques based on some kind of nonlinear regression coupled with topological parameters have been developed, as have a number of methods based on some form of nonlinear regression mixed with topological parameters.
The approach presented in this project which is called as ESOL (Estimated SOLubility) uses descriptors of molecules to get a pretty accurate log of aqueous solubility estimate. If ESOL has a distinguishing feature, it is its relative simplicity compared to its predictive ability. Using simple linear regression and artificial neural network, eight molecular descriptors were examined to predict the log of aqueous solubility.

INFORMATION OF THE DATASET

The dataset which is used in the project includes the following data:

•	1144 compounds in the form of SMILES,

•	their measured log(solubility),

•	and the actual ESOL predicted log(solubility).

DESCRIPTION OF FEATURES:

The molecules required to make the model were first characterized by eight parameters computed from their two-dimensional connectivity using the RDKit program. The following are the set of parameters included:

1)	Octanol-water partition coefficient (clogP): In a two-phase octanol/water system, it is defined as the ratio of a chemical's concentration in the octanol phase to its concentration in the aqueous phase.
2)	Molecular Weight (MWT): It is defined as a measure of the sum of the atomic weight values of the atoms in a molecule.
3)	Rotatable Bonds (RB): It is defined as any single non-ring bond connected to a non-terminal and non-hydrogen atom.
4)	Hydrogen-bond Donor Count (HBD): It is defined as the count of atoms that donate the hydrogen atom of a hydrogen bond.
5)	Hydrogen-bond Acceptor Count (HBA): It is defined as the count of atoms that accept the hydrogen atom of a hydrogen bond.
6)	Topological Polar Surface Area (TPSA): It is defined as the surface sum over all polar atoms or molecules, primarily oxygen and nitrogen, including their associated hydrogen atoms.
7)	Aromatic Proportion (AP): It is defined as the ratio of the number of aromatic atoms to the count of heavy atoms present in a molecule.
8)	Non-Carbon Proportion (NCP): It is defined as the ratio of the number of heavy atoms which are not carbon (also known as heteroatoms) to the count of heavy atoms present in a molecule.

REFERENCES

[1]	ESOL: Estimating Aqueous Solubility Directly from Molecular Structure

[2]	Prediction of aqueous solubility of compounds based on neural network
