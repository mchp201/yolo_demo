# yolo_demo
YOLO Practice Exercises

一、环境的安装：

1. 通过conda安装Python虚拟环境：
``` bash
conda create -n yolo python==3.12
```
2. 切换环境
``` bash
conda activate yolo
```
3. 将环境中的numpy降级至"1.x.x"的版本
``` bash
pip install "numpy<2"
```
4. 安装pytorch、ultralytics包
``` bash
pip3 install torch torchvision ultralytics
```
