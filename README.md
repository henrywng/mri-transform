Included in this repository is a jupyter notebook and pdf of my code from my MRI image reconstruction project. 
At the heart of the project is the idea of K-space (frequency domain) and the spatial domain.

MRI scan data comes as data in the frequency domain, and it must be converted into the spatial domain using the Inverse Fast Fourier Algorithm.
There is a function in NumPy that deals with the Fast Fourier Transform.

The project starts with using the Fast Fourier Transform in one dimensions (on a Gaussian).
It then moves onto two-dimensional Gaussians, documenting the process of converting the Gaussian into the frequency domain and back into the spatial domain.
Finally, the Fast Fourier Algorithm is used on raw MRI kspace data of a knee (from https://github.com/birogeri/kspace-explorer) to generate the MRI scan images.
