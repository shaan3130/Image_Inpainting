# Image_Inpainting
Image inpainting aims to automatically fill in the holes of image that are to be removed for artistically or confidential considerations. The idea was to create a Dictionary using
the source region of the image and generate a sparse represnetation of image pixels by training a model using lasso regression. Then use this repesentation to generate target patch.
The references were taken from three papers on sparse representation of signal [1], [2] and [3]. The algorithm is implementation of the [3] paper.

[1] Signal Recovery From Random Measurements Via Orthogonal Matching Pursuit 
[2] K-SVD: An Algorithm for Designing Overcomplete Dictionaries for Sparse Representation
[3] IMAGE INPAINTING VIA SPARSE REPRESENTATION
