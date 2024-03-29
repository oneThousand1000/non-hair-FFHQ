# non-hair-FFHQ
The non-hair-FFHQ dataset  is a high-quality image dataset that contains 6,000 non-hair FFHQ portraits, based on [ stylegan2-ada](https://github.com/NVlabs/stylegan2-ada-pytorch) and [ffhq-dataset](https://github.com/NVlabs/ffhq-dataset).

![non-hair-FFHQ](./imgs/non-hair-FFHQ.png)

The dataset is built by our HairMapper method.

> **HairMapper: Removing Hair from Portraits Using GANs**<br>
> [Yiqian Wu](https://onethousandwu.com/), [Yongliang Yang](http://www.yongliangyang.net/), [Xiaogang Jin](http://www.cad.zju.edu.cn/home/jin)*.<br>2022 IEEE/CVF Conference on Computer Vision and Pattern Recognition.

<div align="center">

[![Project](https://img.shields.io/badge/HairMapper-1?label=Project&color=8B93FF)](https://onethousandwu.com/HairMapper.github.io/)
[![Paper](https://img.shields.io/badge/Main%20Paper-1?color=58A399)](https://openaccess.thecvf.com/content/CVPR2022/html/Wu_HairMapper_Removing_Hair_From_Portraits_Using_GANs_CVPR_2022_paper.html)
[![Suppl](https://img.shields.io/badge/Supplementary-1?color=378CE7)](http://www.cad.zju.edu.cn/home/jin/cvpr2022/Supplementary_Materials.pdf)
[![Video](https://img.shields.io/badge/Video-1?color=FDA403)](https://youtu.be/UNtgpphVR2w)
[![Dataset](https://img.shields.io/badge/Dataset-1?color=FC819E)](https://github.com/oneThousand1000/non-hair-FFHQ)
[![Github](https://img.shields.io/github/stars/oneThousand1000/HairMapper)](https://github.com/oneThousand1000/HairMapper)

</div>


We apply our method on FFHQ images (all images have licenses that allow **free use, redistribution, and adaptation for non-commercial purposes**) and present a [non-hair-FFHQ](https://github.com/oneThousand1000/non-hair-FFHQ) dataset that contains 6,000 non-hair portraits to inspire and facilitate more works in the future.

## Overview

Google drive link of the dataset : https://drive.google.com/drive/folders/1CbyFYDTUqWRneyuDlVznY4XG-8pLhoAS?usp=sharing.

| dir                                                          | information                     |
| ------------------------------------------------------------ | ------------------------------- |
| ├ [hair](https://drive.google.com/drive/folders/1ItALK5S9vYY6pwG_hN3sV1rrA7puivuM?usp=sharing) | original images, `{img_id}.png` |
| └ [non-hair](https://drive.google.com/drive/folders/1hOp-ulk11_FismlQ8nr57HdJfJTxen_D?usp=sharing) | results images , `{img_id}.png` |

## Code

https://github.com/oneThousand1000/HairMapper

## Agreement

The non-hair-FFHQ dataset is available for **non-commercial research purposes** only.



## Related Works

> **A Style-Based Generator Architecture for Generative Adversarial Networks**
> Tero Karras (NVIDIA), Samuli Laine (NVIDIA), Timo Aila (NVIDIA)
> https://arxiv.org/abs/1812.04948

> **Training Generative Adversarial Networks with Limited Data**
> Tero Karras, Miika Aittala, Janne Hellsten, Samuli Laine, Jaakko Lehtinen, Timo Aila
> https://arxiv.org/abs/2006.06676



## Citation

```
@InProceedings{Wu_2022_CVPR,
    author    = {Wu, Yiqian and Yang, Yong-Liang and Jin, Xiaogang},
    title     = {HairMapper: Removing Hair From Portraits Using GANs},
    booktitle = {Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR)},
    month     = {June},
    year      = {2022},
    pages     = {4227-4236}
}
```


## Contact

[jin@cad.zju.edu.cn](mailto:jin@cad.zju.edu.cn)

onethousand@zju.edu.cn

onethousand1250@gmail.com

