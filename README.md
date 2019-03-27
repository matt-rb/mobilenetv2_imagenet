# PyTorch Implemention of MobileNet V2

# Requirements

## Dataset
Download the ImageNet dataset and move validation images to labeled subfolders.
To do this, you can use the following script: https://raw.githubusercontent.com/soumith/imagenetloader.torch/master/valprep.sh
## Libraries
```
NumPy         1.15.0
matplotlib    2.2.3
PyTorch       0.4.1
torchvision   0.2.1
tensorbord    1.9.0
tensorboardX  1.2
```


# Training model
Training a model can be easily done by following command
```bash

python imagenet.py -d path/to/dataset 

```



# Citations
The following is a [BibTeX](www.bibtex.org) entry for the MobileNet V2 paper that you should cite if you use this model.
```
@InProceedings{Sandler_2018_CVPR,
author = {Sandler, Mark and Howard, Andrew and Zhu, Menglong and Zhmoginov, Andrey and Chen, Liang-Chieh},
title = {MobileNetV2: Inverted Residuals and Linear Bottlenecks},
booktitle = {The IEEE Conference on Computer Vision and Pattern Recognition (CVPR)},
month = {June},
year = {2018}
}
```

