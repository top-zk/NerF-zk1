---
license: Apache License 2.0
tags:
  - Dynamic NeRF
  - 三维重建
---
### 数据集描述
本数据集为D-NeRF: Neural Radiance Fields for Dynamic Scenes三维快速重建数据集，

- data包括八个场景，分别是bouncingballs、hellwarrior、hook、jumpingjacks、lego、mutant、standup、trex
- 每个场景包含若干张张训练集、验证集和测试集，及对应的位姿转换矩阵，图像分辨率为800x800

### 数据集格式
解压下载下来的数据集元数据之后，每个数据集的格式如下所示：
```
├── data  
│   ├── mutant   
│   │     ├── train                                    
│   │     ├── val      
│   │     ├──test      
│   │     ├──transforms_train.json      
│   │     ├──transforms_val.json     
│   │     ├──transforms_test.json  
│   ├── standup    
│   ├── ..
 ```

### 数据来源
```BibTeX
@article{pumarola2020d,    
    title={D-NeRF: Neural Radiance Fields for Dynamic Scenes},    
    author={Pumarola, Albert and Corona, Enric and Pons-Moll, Gerard and Moreno-Noguer, Francesc},    
    journal={arXiv preprint arXiv:2011.13961},    
  year={2020}    
}
```
### Download with link
```bash
https://www.dropbox.com/s/0bf6fl0ye2vz3vr/data.zip?dl=0
```

```bash
git clone https://www.modelscope.cn/datasets/Damo_XR_Lab/D_NeRF_Dataset.git
```