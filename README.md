# Computational Photography Lab Exercises

This repository contains *ungraded* lab exercises for Computational Photography.  These projects are not submitted, but the topics may appear on the final exam.


## Notebooks

### [Image Processing & Analysis](/image_processing)

Introduce key parts of the numpy and OpenCV APIs with an emphasis on applications in computational photography.


### [Image Frequency Spectra](/frequency_spectra)

Explore image processing in the frequency domain.


### [Features, Keypoints, & Applications](/feature_keypoints)

Implement image keypoint descriptors and experiment with [OpenSfM](https://github.com/mapillary/OpenSfM), a powerful open source tool for computing [structure from motion](https://en.wikipedia.org/wiki/Structure_from_motion).


## Setup

In order to run the lab notebooks, install [anaconda](https://www.continuum.io/downloads) for python 2.7 (**DO NOT USE THE COURSE VM**), then clone this repository and create a copy of the Computational Photography conda environment by running `conda env create -f CompPhoto.yml` from the project folder. Anaconda will automatically install the required dependencies, then you can activate the environment with `source activate CompPhoto`. With that active you can run the notebook by executing `jupyter notebook` from the terminal. The terminal will display a URL that you can copy to reach the notebook explorer which can be used to navigate to one of the notebook files (i.e., a file ending in ".ipynb"). (If you have problems accessing the CompPhoto kernel in the notebook, run `conda install nb_conda` before running the notebook server; this should automatically add all available conda environments to the jupyter notebook browser.)

You can edit code in any cell of the notebook, and execute each cell by clicking the "play" icon on the menu bar, or using the "shift + enter" keyboard shortcut. The output of each cell will appear inline in the notebook immediately after each cell.
