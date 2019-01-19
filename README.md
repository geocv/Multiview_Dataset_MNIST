MNIST Multiview Datasets
========================

MNIST is a publicly available dataset consisting of 70, 000 images of handwritten digits distributed over
ten classes. We generated 2 four-view datasets where each view is a vector of R<sup>14 x 14</sup>:

* MNIST<sub>1</sub>:  It is generated by considering 4 quarters of image as 4 views. 
* MNIST<sub>2</sub>:  It is generated by we considering 4 overlapping views around the centre of images: this dataset brings redundancy between the views.


Related Papers:
```
Multiview Boosting by Controlling the Diversity and the Accuracy of View-specific Voters.
Anil Goyal, Emilie Morvant, Pascal Germain and Massih-Reza Amini.
https://arxiv.org/abs/1808.05784
```

```
Multiview Learning of Weighted Majority Vote by Bregman Divergence Minimization.
Anil Goyal, Emilie Morvant and Massih-Reza Amini
Intelligent Data Analysis, 2018 (https://arxiv.org/abs/1805.10212)
```

## Contents
This repository consists of 2 folders (MNIST_1 and MNIST_2). Each folder has 4 files corresponding to 4 views of the dataset. 



