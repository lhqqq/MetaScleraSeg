# MetaScleraSeg: An Effective Meta-Learning Framework for Generalized Sclera Segmentation
This repository contains the official PyTorch implementation of:

**MetaScleraSeg: An Effective Meta-Learning Framework for Generalized Sclera Segmentation**   

![](image/flow.png)

## Prerequisites

- Python 3.8
-  NVIDIA GPU + CUDA CuDNN
-  \>= PyTorch 1.8.0

## Paper data and models
- We build a Cross-Domain Sclera Segmentation (CDSS) dataset with diverse ethnicity and quality as domain labels to supplement the
existing dataset. You can download the dataset as follows: [[Baidu Drive]](https://pan.baidu.com/s/1JvPfyNUxPFIBbYHvfkZW7A?pwd=k1hu 
)

- The trained models can be downloaded via: [[Baidu Drive]]
- The code structure is based on [MTL-template](https://github.com/yaoyao-liu/meta-transfer-learning) and [Pytorch-Segmentation](https://github.com/yassouali/pytorch_segmentation). 

## How to run the code?

```
python test.py 
```

## Questions
Please contact haiqing_li@stu.bucea.edu.cn

### Citation
If you find our work useful in your research, please consider citing:

   @article{wang2023metascleraseg,
    title={MetaScleraSeg: an effective meta-learning framework for generalized sclera segmentation},
    author={Wang, Caiyong and Li, Haiqing and Ma, Wenhui and Zhao, Guangzhe and He, Zhaofeng},
    journal={Neural Computing and Applications},
    volume={35},
    number={29},
    pages={21797--21826},
    year={2023},
    publisher={Springer}

