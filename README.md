# Arabic Multi Fonts Dataset
A multi-word multi-font Arabic word-image dataset. 

AMDS is a dataset of Arabic word images.
The dataset was generated using the TextImagesToolkit
https://github.com/msfasha/TextImagesToolkit.

The database of comprised of a number of binary files and text files.
The binary files stores all the image files in binary format.\
The text file include information about the image word and the location of that image in the binary file.
The binary file format is suitable for transferring images to the cloud, in addition to faster loading process which is suitable for large number of images.

This dataset was used to train Deep Learning Arabic OCR model (https://github.com/msfasha/Arabic-Deep-Learning-OCR).

A sample code for loading images from the dataset can be found at :(https://github.com/msfasha/Arabic-Deep-Learning-OCR/blob/master/src/DataGenerator_BinaryFile.py). This module has functions that splits the binary file into trainivalidation and testing datasets according to predefined ratios. The module also includes functions to load and iterate batches from each of the created splits/datasets which can be easily consumed by Tensor
flow models as presented in (https://github.com/msfasha/Arabic-Deep-Learning-OCR).

Sample datasets can be downloaded from :
https://drive.google.com/drive/folders/1mRefmN4Yzy60Uh7z3B6cllyyOXaxQrgg
