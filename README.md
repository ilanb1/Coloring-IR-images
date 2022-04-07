Coloring Infrared (IR) images

Applying the Pix2pix algorithm for coloring IR images. 

The implementation is according to the TensorFlow tutorial for pix2pix: https://www.tensorflow.org/tutorials/generative/pix2pix?hl=en with slight modifications to match the depth of our input (IR image: single-channel) and output (The "ab" channels of the LAB color space).

The Dataset is taken from: https://ivrlwww.epfl.ch/supplementary_material/cvpr11/index.html
