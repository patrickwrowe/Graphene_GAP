# Graphene_GAP

We present an accurate interatomic potential for graphene, constructed using the Gaussian approximation potential (GAP) machine learning methodology. This GAP model obtains a faithful representation of a density functional theory (DFT) potential energy surface, facilitating highly accurate (approaching the accuracy of ab initio methods) molecular dynamics simulations. This is achieved at a computational cost which is orders of magnitude lower than that of comparable calculations which directly invoke electronic structure methods. We evaluate the accuracy of our machine learning model alongside that of a number of popular empirical and bond-order potentials, using both experimental and ab initio data as references. We find that whilst significant discrepancies exist between the empirical interatomic potentials and the reference data—and amongst the empirical potentials themselves—the machine learning model introduced here provides exemplary performance in all of the tested areas. The calculated properties include: graphene phonon dispersion curves at 0 K (which we predict with sub-meV accuracy), phonon spectra at finite temperature, in-plane thermal expansion up to 2500 K as compared to NPT ab initio molecular dynamics simulations and a comparison of the thermally induced dispersion of graphene Raman bands to experimental observations. We have made our potential freely available online at [http://www.libatoms.org].

# Repository for Graphene GAP Machine Learning Potential & Training Data

For testing and validation of this machine learning model, please see: P. Rowe, G. Csányi, D. Alfè, A. Michaelides, “Development of a machine learning potential for graphene”, Phys. Rev. B., 97, 5, 054303, (2018) 

This paper has been made open source and is freely available online at: https://discovery.ucl.ac.uk/id/eprint/10044678/

# Additional Information

For installation instructions of the supporting GAP and QUIP codes, please see: https://libatoms.github.io/GAP/installation.html

The GAP potential and training data here may be used under the Creative Commons (CC BY 4.0) license, for the license conditions of the supporting QUIP and GAP source code, however, please see: https://github.com/libAtoms/GAP/blob/main/LICENSE.md and http://www.libatoms.org/gap/gap_download.html

If making use of this potential, please cite the following papers:

- P. Rowe, G. Csányi, D. Alfè, A. Michaelides, “Development of a machine learning potential for graphene”, Phys. Rev. B., 97, 5, 054303, (2018) 
- A. P. Bartók, M. C. Payne, R. Kondor, G. Csányi, "Gaussian Approximation Potentials: The Accuracy of Quantum Mechanics, without the Electrons", Phys. Rev. Lett., 104, 136403
