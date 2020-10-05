[![](https://img.shields.io/badge/arXiv-2002.06127%20-red.svg)](https://arxiv.org/abs/2002.06127)

# Modification of CLASS (v2.9) for interacting DM-DE

This modified version of the [CLASS](https://github.com/lesgourg/class_public) code allows the computation of background quantities and perturbation equations for the interacting dark matter-dark energy scenario discussed in [Lucca & Hooper 2020](https://arxiv.org/abs/2002.06127) (arXiv:2002.06127). This code can be used freely provided you cite the specific release paper ([Lucca & Hooper 2020](https://arxiv.org/abs/2002.06127)) and the original CLASS release paper ([Blas et al. 2011](https://arxiv.org/abs/1104.2933)).

The code has been edited by M. Lucca (mlucca AT ulb.ac.be). We refer to the main CLASS code [wiki](https://github.com/lesgourg/class_public/wiki/Installation) for installations instructions. The main modifications with respect to the original version are in input.c, background.c and .h, and perturbations.c (always enclosed in the comments "BEGIN/END MODIFICATION ML"). An input file test_iDMDE.ini has been created with the basic quantities needed in order to run the modified code.




