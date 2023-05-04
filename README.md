# Membership Inference Attacks

CS 229br project with Jeff, Marvin, Jason, and Seth.

All of our data here uses the Pile (train/validation). Because the HuggingFace import of the Pile doesn't contain a val split built-in, we consulted with EEleuther's staff and made our own special validation dataset import: `the_pile_val.py`. This is referenced in some notebooks/python files. 

Most of our notebooks and results are pretty standalone (completely so for LoRa and LiRa). See bullet points below for other information. 

Directories / files:
- common_code.py has useful functions for computing loss of training data, plotting stuff, etc.
- MoPe: perturb_weights_attack.ipynb and .py implement MoPe
- cross_entropy_threshold_attack is just the loss attack
- The command_line_ versions allow you to input things via the command line
- LoRa/LiRa are just notebooks
