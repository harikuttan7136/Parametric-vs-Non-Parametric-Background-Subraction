# Parametric-vs-Non-Parametric-Background-Subraction

Non parametric Kernel density based background subraction was compared with the Stauffer Grimson Gaussian mixture model

Parametric model uses Stauffer grimson model in the paper http://www.ai.mit.edu/projects/vsam/Publications/stauffer_cvpr98_track.pdf but the weights of the previous frames are kept constant. For decaying weights mentioned in the paper you will have to introduce decaying parameter and change the mean and variance updation formula in the code.

Non Parametric kernel density based model uses Normal distribution and suppression of false detection is also handled
