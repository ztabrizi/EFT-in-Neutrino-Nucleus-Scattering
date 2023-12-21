# EFT in Neutrino Nucleus Scattering

This GitHub repository contains tables of charged current quasi-elastic (CCQE) neutrino--nucleus cross-sections for $A=16$ (oxygen), for different neutrino flavors, and for the full set of Weak Effective Field Theory (WEFT) operators. These are the results derived in a 2024 paper by Joachim Kopp, Noemi Rocco, and Zahra Tabrizi.

The naming conventions of the files are ``xsec_cc_Oxygen_[dip|D2|LQCD]_[XY][0|1].txt``, where ``X, Y = L, R, S, P, T`` corresponds to the Lorentz-structure of the interaction (``LL`` = Standard Model). For cross sections that depend on the axial form factor of the nucleon, the prefix indicates how this form factor has been determined, with ``dip`` corresponding to a simple dipole form (which included here merely for comparison, but should not be used in precision studies), ``D2`` corresponds to the $z$-expansion parameterization fitted to neutrino–deuterium scattering data, and ``LQCD`` to the $z$-expansion fitted to lattice QCD calculations. For cross sections that depend on the induced scalar form factor, a suffix ``0'' indicates that this form factor has been set to zero, whereas a suffix ``1`` indicates that it has determined using a constituent quark model (with $\mathcal{O}(1)$ uncertainty).

These cross-section files follow the format that is used in [GLoBES](https://www.mpi-hd.mpg.de/personalhomes/globes/), where the seven columns in each file correspond to

$$
\log_{10}\Big[\frac{E_{\nu}}{\text{GeV}} \Big],\quad
\frac{\hat\sigma_{\nu_e}}{E_\nu},\quad
\frac{\hat\sigma_{\nu_\mu}}{E_\nu},\quad
\frac{\hat\sigma_{\nu_\tau}}{E_\nu},\quad
\frac{\hat\sigma_{\bar\nu_e}}{E_\nu},\quad
\frac{\hat\sigma_{\bar\nu_\mu}}{E_\nu},\quad
\frac{\hat\sigma_{\bar\nu_\tau}}{E_\nu},
$$

where $E_\nu$ is the neutrino energy. The units in columns 2–7 are $10^{-38} \text{cm}^2 / \text{GeV}$. The notation $\hat\sigma$ indicates that these are individual contributions to the cross-section, not total cross sections. (For instance, the interference contributions $\hat\sigma_{XY}$ with $X \neq Y$, can be negative.) Only the sum of all the $\hat\sigma$, weighted with the appropriate Wilson coefficients, is a meaningful physical quantity that can be compared to experimental data.

Additions, comments, or suggestions should be directed to:
* Joachim Kopp (jkopp@cern.ch)
* Noemmi Rocco (nrocco@fnal.gov)
* Zahra Tabrizi (ztabrizi@northwestern.edu)

--- 
**Citation info:**

``arxiv.org/abs/...``

```
@article{...
}
```
