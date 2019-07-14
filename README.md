# SiameseChange

Siamese change detection code for pair-wise medical image comparison (a manuscript detailing this approach is submitted)

**Requirements**: 
- Python 3.6.7
- PyTorch 1.1.0
- CUDA 10.0
- GPU support

**How to Run**:

The working directory should contain the following Python scripts:

- main.py (training and validation script)
- eval.py (testing evaluation script)
- partition.py (script for partitioning the data set)

Run the scripts in an interactive shell, like IPython.

The working directory should also contain a 'data/' subdirectory, which contains:

1. processed input images 
2. csv files containing annotations for the input images

**Citation**

If you use this code in your work, you can cite... manuscript in submission.

**Acknowledgments**

The Center for Clinical Data Science at Massachusetts General Hospital and the Brigham and Woman's Hospital provided technical and hardware supportm including access to graphics processing units. The basis of the siamese network implementation in PyTorch is also indebted to code shared on GitHub by Harshvardhan Gupta (https://github.com/harveyslash/Facial-Similarity-with-Siamese-Networks-in-Pytorch).

Questions? Contact Matt at mdli@mgh.harvard.edu.



