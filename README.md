# Awesome Computer Vision for Video

[![Awesome](https://awesome.re/badge-flat.svg)](https://awesome.re)

a curated list of awesome libraries/ packages/ tools for doing computer vision work on videos with :heart:

Other video related curated  lists:
* [awesome-video](https://github.com/sitkevij/awesome-video)
* [Video-Enhancement](https://github.com/yulunzhang/video-enhancement)

## Video Processing
* [ffmpeg cheatsheet](https://gist.github.com/ohjho/737c04037747a5eba9fa13429faea444): a gist of common video operations
* [VidGear](https://github.com/abhiTronix/vidgear): a high-performance cross-platform Video Processing framework
* [decord](https://github.com/dmlc/decord): faster video loading experience intended for loading training data for deep learning ([medium post](https://medium.com/@haydenfaulkner/extracting-frames-fast-from-a-video-using-opencv-and-python-73b9b7dc9661))
* [imageio](https://imageio.readthedocs.io/en/stable/examples.html#iterate-over-frames-in-a-movie): a lightweight package (requires only numpy and pillow) for loading video as an image generator
* [ffmpeg-python](https://github.com/kkroening/ffmpeg-python): one of the most popular ffmpeg python wrapper ([examples](https://github.com/kkroening/ffmpeg-python/blob/master/examples/README.md#generate-thumbnail-for-video))
* [PyNVVL](https://github.com/mitmul/pynvvl): a python wrapper of NVIDIA video loader (NVVL) with CuPy for fast video loading with Python

## Machine Learning
* [PySceneDetect](https://pyscenedetect.readthedocs.io/): OpenCV based scene cut/ transition detection library with support for both **content-based** and **luminance-based** detection
* [katna](https://github.com/keplerlab/katna): a color-based keyframes extractor using K-Means ([medium post](https://medium.com/@Aloksaan/video-key-frame-extraction-with-katna-11971ac45c76))
* [scikit-video](http://www.scikit-video.org/): a Python module for video processing built on top of scipy, numpy, and ffmpeg/libav.
* [Keyframe Extraction from Videos](https://github.com/sawankumar94/Key-Frame-Extraction-from-Videos): simple Jupyter Notebook using Color Histogram, SVD, and Dynamic Clustering method

## Video Understanding
* [VideoFlow](https://github.com/videoflow/videoflow): Python framework that facilitates the quick development of complex video analysis applications and other series-processing based applications in a multiprocessing environment ([object tracking sample application](https://docs.videoflow.dev/computer-vision-recipes/object-tracking-sample-application.html))
* [Video Captioning](https://github.com/scopeInfinity/Video2Description): combining audio, image captioning, and sentence generation sub-models for video captioning
* [Video Analyst](https://github.com/MegviiDetection/video_analyst): implementation of Single Object Tracking and Video Object Segmentation
* [Two-Stream Video Action Recognition Framework](https://github.com/bryanyzhu/two-stream-pytorch): PyTorch implementation of the paper ["Towards Good Practices for Very Deep Two-Stream ConvNets"](https://arxiv.org/abs/1507.02159)
* [Abnormal Event Detection](https://github.com/harshtikuu/Abnormal_Event_Detection): Keras implementation of ["Abnormal Event Detection in Videos using Spatiotemporal Autoencoder"](https://arxiv.org/abs/1701.01546)
* [ActionVLAD](https://github.com/rohitgirdhar/ActionVLAD): TensorFlow implementation of ["Learning spatio-temporal
aggregation for action classification "](https://rohitgirdhar.github.io/ActionVLAD/)
* [Terran Timeline](https://github.com/pento-group/streamlit-terran-timeline): a demo using Terran (face recog + pose estimation library) on video that created face timelines for any youtube video

## Video Enhancement
* [Video2x](https://github.com/k4yt3x/video2x): a video upscaler based on [waifu2x](https://github.com/nagadomi/waifu2x), a super-res for anime-style art using CNN ([youtube demo](https://www.youtube.com/watch?v=7Nr5YmCU0po&t=188s))
* [BasicSR](https://github.com/xinntao/BasicSR): image and video super-res toolbox based on PyTorch
* [Zooming-Slow-Mo](https://github.com/Mukosame/Zooming-Slow-Mo-CVPR-2020): a joint video frame interpolation (VFI) and video super-resolution (VSR) framework built on PyTorch

## Miscellaneous
* [video-to-ascii](https://github.com/joelibaceta/video-to-ascii): a python cli to play videos in the terminal using characters as pixels
* [pysub2](https://github.com/tkarabela/pysubs2): a python library for editing video subtitle files with support for _Advanced SubStation_ (`.ass`) files ([examples](https://pythonhosted.org/pysubs2/tutorial.html))
