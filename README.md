# STOCO
Code release for ``Stochastic Consensus: Enhancing Semi-Supervised Learning with Consistency of Stochastic Classifiers'' accepted by ECCV 2022.

## Requirements
- python 3.6.4
- pytorch 1.4.0
- torchvision 0.5.0

## Data preparation
The references of the used datasets are included in the paper.

## Model training
1. Install necessary python packages.
2. Replace root and dataset in run.sh with those in one's own system. 
3. Run command `sh run.sh`.

The results are saved in the folder `./results/`.

## Paper citation
```
@InProceedings{STOCO,
author={Tang, Hui
and Sun, Lin
and Jia, Kui},
title={Stochastic Consensus: Enhancing Semi-Supervised Learning with Consistency of Stochastic Classifiers},
booktitle={Computer Vision -- ECCV 2022},
year={2022},
pages={330-346},
}
```
