# Simulation of Phase Biased Josephson Junction

Tapas Senapati<sup>1</sup>, Ashwin Kumar Karnad<sup>2</sup>, Kartik Senapati<sup>1</sup>

<sup>1</sup> *School of Physical Sciences, National Institute of Science Education
and Research (NISER) Bhubaneswar, An OCC of Homi Bhabha
National Institute, Jatni, 752050, Odisha, India.*

<sup>2</sup> *Department of Physics, Birla Institute of Technology & Science Pilani - K K Birla Goa Campus, Zuarinagar, 403726, Goa, India.*

| Description | Badge                                                                                                        |
| ----------- | ------------------------------------------------------------------------------------------------------------ |
| Paper       | Coming soon ...                                                                                              |
| Preprint    | [![arXiv:2304.11457](https://img.shields.io/badge/arxiv-2304.11457-green)](https://arxiv.org/abs/2304.11457) |
| Binder | [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/iamashwin99/Phase-biased-Josephson-Junction/HEAD) |
| Google Colab | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/iamashwin99/Phase-biased-Josephson-Junction/blob/main/notebooks/T_IVH_simulations.ipynb) |
| License     | Coming soon …                                                                                                |
| DOI         | Coming soon …                                                                                                |

## About

This repository contains simulation code to establish equivalence between the IcH and V H
(magnetoresistance) characteristics of a Josephson junction ( with and without the second harmonics), then further establish the experimental V H plot and
the simulated V H plot. These equivalences were used to support the results from the paper [arXiv:2304.11457](https://arxiv.org/abs/2304.11457).

For the first part, the simulation was set up by solving the ODE (wash board potential) with input similar to the experimental input of, sweeping the current while equilibrating the system at each step and then repeating this over multiple magnetic fields, then further analyzing this data to obtain IcHand V H plots. 

For the second part,
experimental data was gathered similarly to the simulation steps (calculating IV
data for multiple magnetic field ) and then analyzed to obtain IcH and V H plots, the results obtained from this was matched with the simulation results.
In both of the above method, the equivalence between the IcH and V H
(magnetoresistance) characteristics of a Josephson junction was confirmed and
was also matched with the experimental results.

## Binder

Binder is a free service that allows Jupyter notebooks hosted in this repository to be executed and analysed in the cloud. There is no need to install anything, and no files will be created on your PC. Click on the Binder badge in the table above to access Binder.

## How to cite

Tapas Senapati, Ashwin Kumar Karnad, Kartik Senapati.

[ Simulation of Phase Biased Josephson Junction.](https://github.com/iamashwin99/Phase-biased-Josephson-Junction)
