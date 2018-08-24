Clone of COCO API - http://cocodataset.org/
===========================================

# Original README:

COCO is a large image dataset designed for object detection, segmentation, person keypoints detection, stuff segmentation, and caption generation. This package provides Matlab, Python, and Lua APIs that assists in loading, parsing, and visualizing the annotations in COCO. Please visit http://cocodataset.org/ for more information on COCO, including for the data, paper, and tutorials. The exact format of the annotations is also described on the COCO website. The Matlab and Python APIs are complete, the Lua API provides only basic functionality.

In addition to this API, please download both the COCO images and annotations in order to run the demos and use the API. Both are available on the project website.

Please download, unzip, and place the images in: coco/images/

Please download and place the annotations in: coco/annotations/

For substantially more details on the API please see http://cocodataset.org/#download.

# This clone's README:

To support Windows x64 build with [Microsoft Visual C++ 9.0 standalone: Visual C++ Compiler for Python 2.7 and python2.7](https://www.microsoft.com/en-us/download/details.aspx?id=44266) I had to make [changes](https://github.com/cocodataset/cocoapi/) to:

- `common/maskApi.h`
- `common/maskApi.c`
- `PythonApi/setup.py`

To install this package:

```
git clone https://github.com/neoglez/cocoapi
cd PythonApi
python setup.py build_ext install
```
