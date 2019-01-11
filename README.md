## Personalized-Saliency
Beyond Universal Saliency: Personalized Saliency Prediction with Multi-task CNN

This project hosts the code for our **IJCAI 2017** paper.

 - Yanyu, Xu, Nianyi Li, Junru Wu, Jinyi Yu, and Shenghua Gao. *Beyond Universal Saliency*: Personalized Saliency Prediction with Multi-task CNN. In *IJCAI*, 2017. (**Spotlight**) [[IJCAI]](https://www.ijcai.org/proceedings/2017/0543.pdf)
 
Saliency detection is a long standing problem in computer vision. Tremendous efforts have been focused on exploring a universal saliency model across users despite their differences in gender, race, age, etc. Yet recent psychology studies suggest that saliency is highly specific than universal: individuals exhibit heterogeneous gaze patterns when viewing an identical scene containing multiple salient objects. 

In this paper, we first show that such heterogeneity is common and critical for reliable saliency prediction. Our study also produces the first database of personalized saliency maps (PSMs). We model PSM based on universal saliency map (USM) shared by different participants and adopt a multi-task CNN framework to estimate the discrepancy between PSM and USM. Comprehensive experiments demonstrate that our new PSM model and prediction scheme are effective and reliable.

## Reference
  
 +If you use this code or dataset as part of any published research, please refer the following paper.
  
 ```
  @inproceedings{ijcai2017-543,
  author    = {Yanyu Xu, Nianyi Li, Junru Wu, Jingyi Yu, Shenghua Gao},
  title     = {Beyond Universal Saliency: Personalized Saliency Prediction with Multi-task CNN},
  booktitle = {Proceedings of the Twenty-Sixth International Joint Conference on
               Artificial Intelligence, {IJCAI-17}},
  pages     = {3887--3893},
  year      = {2017},
  doi       = {10.24963/ijcai.2017/543},
  url       = {https://doi.org/10.24963/ijcai.2017/543},
}
```

## Personalized Saliency Dataset
Download our *Personalized Saliency* dataset [[Google Drive]](https://drive.google.com/open?id=0B29_sOsoKIkVa3VfRWN3MEc2MUU), [[Baidu Pan (code: 4es6)]](https://pan.baidu.com/s/1F6Vg1L11F_QMe1exP25Ehg). This dataset contains all 30 subjects.  
