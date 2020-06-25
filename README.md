
# Object Detection & Segmentation

This repository is for testing and comparing different approaches to object detection and segmentation.

## Requirements

Clone repository with submodules (`git clone --recurse-submodules ...`).

Install the submodules in editable mode
```bash
pip install -e yolact 
pip install -e git+https://github.com/CharlesShang/DCNv2@master#egg=dcnv2
```

## Usage

### yolact

Use `infer_segmentation(model, img)` from `infer.py` to extract a segmentation array and a mask image from and RGB image. 