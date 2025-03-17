# DmseNet
## Installation
- Clone this repository: tested on Python 3.8
- Install [PyTorch](http://pytorch.org/): tested on v2.1

## Datasets
We support [MVTec AD dataset](https://www.mvtec.com/de/unternehmen/forschung/datasets/mvtec-ad/) for anomaly localization in factory setting.
Unzip the file to `./dataset/`.
```
|--data
    |-- mvtec_anomaly_detection
        |-- bottle
        |-- cable
        |-- ....
```
## Training and testing Models
- Run code by selecting dataset, category.
```
python train.py --dataset mvtec2d --class-name bottle.
```
