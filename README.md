# SCENE TEXT REMOVAL

  A synthetic benchmark database for scene text removal is now released by Deep Learning and Vision Computing Lab of South China University of Technology. The database can be downloaded through the following links:
* Yunpan : (link: https://pan.baidu.com/s/1wwBwgm-n2A7iykoD0i37iQ PASSWORD: vk8f) (Size = 6.3G).
* Google Driver: (link: https://drive.google.com/open?id=1l_yJm1vWV7TF7vDcaVa7FqZLfW7ASYeo) (Size = 6.3G).
  On the other hand, we collected 1000 images from the ICDAR 2017 MLT subdataset which only contains English text to enlarge real data, and the background image(label) is generated by manually erasing the text. The database can be downloaded through the following links:
 * Yunpan : (link: https://pan.baidu.com/s/1WBvB1kS1BcmgrDi9c1Me9Q PASSWORD: knr7).
 * Google Driver : (link: https://drive.google.com/file/d/1G0d6yQwYEDhJdZH-S8mYWTXltJRG3Mg1/view?usp=sharing).
  Note: The real scene text removal dataset can only be used for non-commercial research purpose. For scholars or organization who wants to use the database, please first fill in this [Application Form](https://github.com/HCIILAB/Scene-Text-Removal/tree/master/Application_Form/Application_Form_for_Using_Scene_Text_Removal.doc) and send it via email to us (lianwen.jin@gmail.com). We will give you the decompression password after your letter has been received and approved. 
## 1 Description

The training set of synthetic database consists of a total of 8000 images and the test set contains 800 images; all the training and test samples are resized to 512 × 512. The code for generating synthetic dataset and more synthetic text images as described in “ Synthetic Data for Text localisation in Natural Images"（CVPR2016）can be found in (https://github.com/ankush-me/SynthText).
Besides, all the real scene text images are also resized to 512 × 512.
For more details, please refer to our [arxiv paper](http://arxiv.org/abs/1812.00723).

## 2 Paper

Please consider to cite our paper when you use our database:
```
@article{zhang2019EnsNet,
  title     = {EnsNet: Ensconce Text in the Wild},
  author    = {Shuaitao Zhang∗, Yuliang Liu∗, Lianwen Jin†, Yaoxiong Huang, Songxuan Lai
  joural    = {AAAI}
  year      = {2019}
}
```
## 3 Feedback

Suggestions and opinions of dataset of this dataset (both positive and negative) are greatly welcome. Please contact the authors by sending email to eestzhang@mail.scut.edu.cn.
## 4 Copyright

The synthetic database can be only used for non-commercial research purpose. 

For commercial purpose usage. Please  Dr. Lianwen Jin: lianwen.jin@gmail.com.

Copyright 2018, Deep Learning and Vision Computing Lab, South China University of Teacnology.http://www.dlvc-lab.net
