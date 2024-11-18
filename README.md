# Anxiety Disorders Analysis
This repository contains a Jupyter Notebook that visualizes functional MRI data to identify regions of the brain associated with anxiety disorders. However, this code can be used for the visualization of any Neurosynth psychological concept since the file selection and figure titles are dependent on user input. The two figures included in the notebook show 1) regions with strong associations when functional data is laid on top of anatomical scans and 2) a histogram of voxel intensities.

## Table of Contents
1. [Data Used](#data-used)
2. [Files in This Repository](#files-in-this-repository)
3. [Python Packages Used](#python-packages-used)

### Data Used
Data was downloaded from the website Neurosynth.org, which provided a meta-analysis of 95 studies for the concept of anxiety disorders. Structural MRI data and functional data were used.
The data was provided in `.nii.gz` format.

### Files in This Repository
- **`assignment.ipynb`**: This is the Jupyter Notebook containing all code and figures.

### Python Packages Used
The following Python packages were used in the project:
- `nilearn`
- `nibabel`
- `matplotlib`
