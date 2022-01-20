# Image_inpainting
In signals and images processing to describe our data, we need a model that is important
when implementing algorithms. The sparse land model is a powerful model for describing
signals based on their sparseness and redundancy. According to this model, the signals and
images can be depicted on non-orthogonal basis of a defined vector space, so that the
obtained coefficients are sparse, i.e., the number of nonzero coefficients is few. The sparse
representation is the same in terms of obtaining the corresponding coefficients of the signal
based on specific bases with the conventional transforms such as Fourier transform, but
unlike other transforms, the bases of sparse coding are not necessarily perpendicular to
each other, and also the number of bases is not equal to the number of signal samples, in
other words the defined vector space, known as the dictionary, has redundancy leading to
sparse representation. There are various solving methods and algorithms such as matching
pursuit and basis pursuit to obtain sparse representation of data that we will discuss in the
following chapters. Also choosing appropriate dictionary is very important because sparse
representation results from dictionary’s redundancy. Different types of dictionaries and
algorithms for learning it such as K-SVD are also discussed in the following chapters.

 sparse coding is used in image processing such as denoising, compression, image
resizing and inpainting. Image inpainting refers to filling-in missing pixels in known
locations in the image. The relationship between this issue and the sparse representation is
that due to the redundancy in image information, the distorted parts can be reconstructed
by obtaining sparse representation of existing pixels in the image. In these problems we
can estimate the missing values with respect to other image information and reconstruct
the image. In this project, we concentrate on image inpainting and its implementation using
sparse coding.
