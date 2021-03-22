# ML-perovskites
This repository contains code (Jupyter notebooks) and data for the publication "A Machine Learning Roadmap for Perovskite Photovoltaics."

Citation:
*INSERT CITATION HERE ONCE PUBLISHED*

## Table of Contents
- Installation
- Data Access
- Jupyter notebook reference information

## Installation
Follow the instructions below to prepare to run the code on your computer. All code in this repository is in the form of Jupyter notebooks, a web-based computation environment that uses Python.

1. Clone this repository to your computer. [Tutorial](https://docs.github.com/en/github/creating-cloning-and-archiving-repositories/cloning-a-repository)
2. Install Anaconda. [Tutorial](https://conda.io/projects/conda/en/latest/user-guide/install/index.html)
3. Create and activate a new environment using the Anaconda prompt. [Tutorial](https://conda.io/projects/conda/en/latest/user-guide/tasks/manage-environments.html#creating-an-environment-with-commands)
4. Install python 3.7.6 using conda. [Tutorial](https://conda.io/projects/conda/en/latest/user-guide/tasks/manage-python.html)
5. Install the necessary packages listed in the requirements.txt file using the command `pip install -r/path to/requirements.txt`, filling in the "path to" section with the specific file path on your computer. Double check that the requirements have been installed correctly using the `conda list` command.
6. From the Anaconda prompt, run the command `jupyter notebook`. This will open a page in your web browser running Jupyter Notebook.

## Data Access
This repository (and the publication) contains proof-of-concept examples which apply Machine Learning (ML) to various problems within the field of perovskite photovoltaics. These examples have not been optimized to their furthest extent, and are intended as a starting point for future research. Importantly, our examples rely upon data-sharing between members of the perovskite community. Below is a list of publications/locations to obtain the data needed to run our notebooks.

### Example 1: Echo State Network for Triple-Cation PL Output
This is the only example that uses data collected internally (from our lab group). The data files are available in the TripleCationData folder.

### Example 2: Long Short-Term Memory for MAPI Devices
Data available upon request to the authors of:

Holzhey, P., Yadav, P., Turren-Cruz, S.-H., Ummadisingu, A., Grätzel, M., Hagfeldt, A. & Saliba, M. A chain is as strong as its weakest link – Stability study of MAPbI3 under light and temperature. Materials Today 29, 10-19, doi:10.1016/j.mattod.2018.10.017 (2019).

### Example 3: Convolutional Neural Network for HTL Conductance
Data available at https://github.com/berlinguette/ada. 

Citation:
MacLeod, B. P., Parlane, F. G. L., Morrissey, T. D., Hase, F., Roch, L. M., Dettelbach, K. E., Moreira, R., Yunker, L. P. E., Rooney, M. B., Deeth, J. R., Lai, V., Ng, G. J., Situ, H., Zhang, R. H., Elliot, M. S., Haley, T. H., Dvorak, D. J., Aspuru-Guzik, A., Hein, J. E. & Berlinguette, C. P. Self-driving laboratory for accelerated discovery of thin-film materials. Sci Adv 6 (2020).

### Example 4: Echo State Network for MAPI Devices (Not included in the paper)
Data available in the Supplementary Information of:

Tress, W., Domanski, K., Carlsen, B., Agarwalla, A., Alharbi, E. A., Graetzel, M. & Hagfeldt, A. Performance of perovskite solar cells under simulated temperature-illumination real-world operating conditions. Nature Energy 4, 568-574, doi:10.1038/s41560-019-0400-8 (2019).

## Jupyter notebook reference information
See the documentation [here](https://jupyter-notebook.readthedocs.io/en/stable/notebook.html) for a useful overview. 

Brief tips for beginners:
- Use `Shift-Enter` to run the current cell and proceed to the next
- Use `Ctrl-Enter` to run the current cell
- The menu at the top has buttons to stop the kernel, restart the kernel, and restart the kernel then run all cells
