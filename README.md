# topic-modelling-tools
Topic Modelling with Latent Dirichlet Allocation using Gibbs sampling

by Stephen Hansen, stephen.hansen@economics.ox.ac.uk
Associate Professor of Economics, University of Oxford

Python/Cython code for cleaning text and estimating LDA via collapsed Gibbs sampling as in Griffiths and Steyvers (2004).

Tutorial scripts and notebooks making use of this library, along with some
example data, can be found in:
https://github.com/sekhansen/text-mining-tutorial


## Installation instructions

If you already have Python and pip installed, `pip install topic-modelling-tools` should work.  The package depends on some other python libraries such as
numpy and nltk but this should be taken care of by pip.

The only other requirement is that a C++ compiler is needed to build the Cython
code.  For Mac OS X you can download Xcode, while for Windows you can download
the Visual Studio C++ compiler.

