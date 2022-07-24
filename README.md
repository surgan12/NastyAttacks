# Distilling the Undistillable: Learning from a Nasty Teacher
---
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](https://opensource.org/licenses/MIT)

Official code release for
"Distilling the Undistillable: Learning from a Nasty Teacher"
Surgan Jandial, Yash Khasbage, Arghya Pal, Vineeth N Balasubramanian, and Balaji Krishnamurthy.
In ECCV 2022

## Overview
---
* Recent work Nasty Teacher proposed to develop teachers which can not be distilled or imitated by models attacking it. 
* We attempt to bypass its defense and steal (or extract) information in its presence successfully. Specifically, we analyze Nasty Teacher from two different directions and subsequently leverage them carefully to develop simple yet efficient methodologies, named as HTC and SCM, which increase the learning from Nasty Teacher by upto 68.63% on standard datasets. 
* Additionally, we also explore an improvised defense method based on our insights of stealing. 

## Prerequisite
---
We use latest Pytorch, and CUDA. You can install them with  
~~~
conda install pytorch torchvision cudatoolkit -c pytorch
~~~   

Then install other packages by
~~~
pip install -r requirements.txt
~~~

## Usage 
---

## Citation
---
```text
@inproceedings{
}
```
Arxiv link:
ECCV paper link: 

## Acknowledgement
---
* [Nasty Teacher](https://openreview.net/forum?id=0zvfm-nZqQs)
* [Analyzing the Confidentiality of Undistillable Teachers in Knowledge Distillation](https://papers.nips.cc/paper/2021/file/4ca82782c5372a547c104929f03fe7a9-Paper.pdf)
