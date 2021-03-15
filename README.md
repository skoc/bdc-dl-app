# bdc-dl-app

## Purpose
This repo houses the initial scripts for building a deep learning app on BioData Catalyst powered by Seven Bridges. These scripts will be used to test training scalability, among other issues.

## Main script
`train_copdgene_vgg.py` creates a Keras VGG-16 model for single-channel image classification.
### Input arguments:
| Arg | Description | Type | Values |
| --- | ----------- | ---- | ------ |
| --insp_exp | Specify INSP(iration) or EXP(iration). Default is both | string | 'INSP', 'EXP', '' (Default) |
| --std_sharp | Specify STD or SHARP images. Default is both | string | 'STD', 'SHARP', '' (Default) |
| --num_files | Number of files to include in training | int | 100 (Default) |
| --epochs | Number of training epochs | int | 15 (Default) |
| --batch_size | Training batch size | int | 8 (Default) |
| --output | Specify file name for output | string | 'model' (Default) |
	
