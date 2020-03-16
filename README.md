# Pie Not Pie

![](./images/pienpi.png)

A project for Pi Day 2020 @ AWS. Running machine learning inference on an edge device, a Raspberry Pi in this case.

## What it is
* A CNN (ResNet) based image classification built on SageMaker
* Optimized & complied with SageMaker Neo
* Running inference on the edge - Raspberry Pi

## How it works

* Use the data pre processing part in the notebook to generate synthetic data from the raw images
* Use the notebook to build a image classifier and compile it for Raspberry Pi
* Setup Raspberry Pi with the DL runtime to run inference via this blog post https://aws.amazon.com/blogs/aws/amazon-sagemaker-neo-train-your-machine-learning-models-once-run-them-anywhere/

