# Supporting data for the publication "Using Machine Learned Force Fields for Lattice Dynamics at Coupled-Cluster level Accuracy"

Folder "c" contains training data for carbon diamond, folder "lih" for lithium hydride.


c/200221forcc.xyz contains the 200 data points used for training ML(DFT E,F), with DFT energies and forces for each of the 200 structures.

All other files contain the same 200 structures with the same forces (unused), but energies at the respective levels:

hfe - Hartree-Fock

mp2 - Moller-Plesset perturbation theory

ccsd - Coupled Cluster singles and doubles

ccsdt - Coupled Cluster singles doubles and pertubative triples


lih/lih_md_sweep222.xyz contains the 2000 data points used for training ML(DFT E,F), with DFT energies and forces for each of the 2000 structures.

lih/200221forcc.xyz contains the 200 data points with DFT energies and forces for each of the 200 structures - they are used in training ML(DFT E).

All other files contain the same 200 structures with the same forces (unused), but energies at the respective levels:

hfe - Hartree-Fock

mp2 - Moller-Plesset perturbation theory

ccsd - Coupled Cluster singles and doubles

ccsdt - Coupled Cluster singles doubles and pertubative triples

