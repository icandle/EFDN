## <div align="center"> Edge-enhanced Feature Distillation Network for Efficient Super-Resolution </div>

<div align="center"> 

[Yan Wang](https://scholar.google.com/citations?user=SXIehvoAAAAJ&hl=en)
</div>

<p align="center"> Nankai University </p>

<p align="center">
<a href="https://openaccess.thecvf.com/content/CVPR2022W/NTIRE/html/Wang_Edge-Enhanced_Feature_Distillation_Network_for_Efficient_Super-Resolution_CVPRW_2022_paper.html" alt="CvF">
    <img src="https://img.shields.io/badge/CVF-NTIRE 2022-367DBD" /></a> 
<a href="https://arxiv.org/abs/2204.08759" alt="arXiv">
    <img src="https://img.shields.io/badge/arXiv-2204.08759-b31b1b.svg?style=flat" /></a>
<a href="https://github.com/icandle/EFDN/blob/main/LICENSE" alt="license">
    <img src="https://img.shields.io/badge/license-Apache--2.0-%23B7A800" /></a> 
<a href="https://data.vision.ee.ethz.ch/cvl/ntire22/posters/Wang_Edge_074-poster-Edge-enhanced%20Feature%20Distillation%20Network%20for%20Efficient%20Super-Resolution.pdf" alt="Poster">
    <img src="https://img.shields.io/badge/poster-NTIRE 2022-brightgreen" /></a> 
</p>



**Overview:** We conclude block devising, architecture searching, and loss design to obtain a more efficient SR structure. In this paper, we proposed an edge-enhanced feature distillation network, named ***EFDN***, to preserve high-frequency information under constrained resources. 

This repository contains [PyTorch](https://pytorch.org/) implementation for ***EFDN*** (CVPRW 2022).

---

Run test_demo.py to reproduce results in ESR Challenge on [NTIRE 2022 Workshop and Challenge](https://data.vision.ee.ethz.ch/cvl/ntire22/).

The code of EDBB is based on [ECBSR](https://github.com/xindongzhang/ECBSR) and [DBB](https://github.com/DingXiaoH/DiverseBranchBlock),
and [PAN](https://github.com/zhaohengyuan1/PAN) Framework is utilized to train our EFDN. Thanks for their excellent work!

If you find our work useful in your research or publication, please cite our work:

```
@InProceedings{Wang_2022_CVPR,
    author    = {Wang, Yan},
    title     = {Edge-Enhanced Feature Distillation Network for Efficient Super-Resolution},
    booktitle = {Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR) Workshops},
    month     = {June},
    year      = {2022},
    pages     = {777-785}
}
```
