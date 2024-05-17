# Random Walk Simulation

This project simulates a random walk for multiple agents and plots the probability density of finding an agent at different positions over various time steps.

## Description

The code performs a 1D random walk for a specified number of agents over different time steps. It uses PyTorch (GPU) for the simulation and Seaborn for plotting the Kernel Density Estimation (KDE) of the final positions of the agents. The probability density function is then visualized for various time steps.


https://github.com/mushrafi88/Random_walk/assets/39360543/4c119e33-bce7-4cb4-89f0-c21fee58f04d


## Requirements

- Python 3.9 or higher
- NumPy
- Matplotlib
- Seaborn
- Pillow
- PyTorch
- Scikit-Learn

To directly run on cloud click this link. [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/mushrafi88/Random_walk/blob/main/random_walk.ipynb)

for local installation follow the below instructions

## Installation

1. Create a virtual environment:

    ```bash
    python -m venv random_walk
    ```

2. Activate the virtual environment:

    - On Windows:
      ```bash
      random_walk\Scripts\activate
      ```
    - On macOS and Linux:
      ```bash
      source random_walk/bin/activate
      ```

3. Install the required packages:

    ```bash
    pip install numpy matplotlib seaborn pillow
    ```

4. Clone the repository:

    ```bash
    git clone https://github.com/mushrafi88/Random_walk.git
    cd Random_walk
    ```
5. Install PyTorch with CUDA enabled by following the instructions [here](https://pytorch.org/get-started/locally/).

## Nix package 
For nix users just run the below command to setup a working environment with PyTorch And CUDA
In nix environment 
```bash
nix develop --impure
```

    - If you prefer not to use PyTorch with CUDA, you can replace instances of `torch` with `numpy` in the code.

