## Domain specific bahasa to english translation in the finance domain.
This repository contains the training script for finetuning marianMT model. For this project, the dataset is created by a custom pdf extractor. The trained model have been shared on huggingface hub to contribute to the community and a demo of the the performace of the trained model is host on huggingface spaces. After finetuning, we achieve a bleu score of 49.58

## Demo app
https://huggingface.co/spaces/wolfrage89/finance_domain_translation_marianMT
<p align="center">
<img src="assets\domain_translation_hf_spaces.JPG" height="370px" width="370px">
</p>


## Colab Training script
https://colab.research.google.com/drive/1wxbOB0feYq5o3IckszZ6P5B-aVjejna9?usp=sharing

## Custom sentence pair extractor output
Click on picture to get higher resolution images
<p align="left">
<img src="assets\sample_1.jpg" height="270px" width="270px">
<img src="assets\sample_2.jpg" height="270px" width="270px">
<img src="assets\sample_3.jpg" height="270px" width="270px">
</p>

### Original extractor repository
https://github.com/tzz89/bahasa_en_pdf_extraction

### Weights and bias 
Training loss and validation bleu score
https://wandb.ai/zuozhe/marianMT_finance_translation/reports/Domain-Specific-Translation--VmlldzoxMzQ0NzM3?accessToken=k710xrdqjnrzeo0hhx1vups0nwfxry23fpfvk3ubi1tvr9mulvmxad2s15kts5g8




