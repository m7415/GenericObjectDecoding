# Generic Object Decoding

This repository contains the data and demo codes for replicating results in our paper: Horikawa, Kamitani "Generic decoding of seen and imagined objects using hierarchical visual features".
The generic object decoding approach enabled decoding of arbitrary object categories including those not used in model training. For more technical details, please refer to the paper: <https://arxiv.org/abs/1510.06479>.

## Data (fMRI data and visual features)
The fMRI data for five subjects (training, test_perception, and test_imagery) and visual features (CNN1-8, HMAX1-3, GIST, and SIFT) are avairable from  <http://brainliner.jp/data/brainliner/Generic_Object_Decoding>. The fMRI data were saved according to the BrainDecoderToolbox2 format <https://github.com/KamitaniLab/BrainDecoderToolbox2>.

## Visual images
For copyright reasons, we do not make the visual images used in our experiments publicly available on our server. You can directly download the images from URLs listed in the imageURL_training.txt and imageURL_test.txt. 
While most of the images can be donwloaded from the URL, some of the images have been deleted from the original URLs. In that case, you can find the visual images from the ImageNet database (2011, fall release; <http://image-net.org/download-imageurls>) using the synset ID and image ID listed in imageID_training.csv and imageID_test.csv files. The image ID is formatted as nxxxx_yyyy, where xxxx represents the WordNet ID (wnid) and yyyy represents the image ID. We will provide a script to automatically download images from the ImageNet in future.

## Demo codes
Currently, the codes used in the present study are available from the authors upon request. We will make the codes openly available soon.