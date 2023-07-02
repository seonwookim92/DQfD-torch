# DQfD - Deep Q-learning from Demonstrations

## What is this?

This repository contains the code for the paper [DQfD: Deep Q-learning from Demonstrations](https://arxiv.org/abs/1704.03732) by DeepMind.

## Installation
    
1. Install directly from the repository:
You can install it as a package from the repository directly using pip. (Recommended)
    ```bash
    pip install 'git+https://github.com/seonwookim92/DQfD-torch.git'
    ```

2. Install from the source code:
You can also install it after downloading the source codes.
    ```bash
    git clone https://github.com/seonwookim92/DQfD-torch.git
    cd dqfd-torch
    pip install -e .
    ```

3. Use without installation:
You can also use the source codes without installing it.
    ```bash
    git clone https://github.com/seonwookim92/DQfD-torch.git
    cd dqfd-torch
    ```
    ```python
    from dqfd import *
    ```

## Dependencies
It relies on the following packages:
- torch
- numpy
- matplotlib
