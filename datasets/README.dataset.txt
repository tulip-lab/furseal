# Rongxin Xu > 2022-07-03 9:36pm
==============================
This dataset includes 96 images.
Face are annotated in YOLO v5 PyTorch format.

The following pre-processing was applied to each image:
* Auto-orientation of pixel data (with EXIF-orientation stripping)
* Resize to 416x416 (Stretch)

The following augmentation was applied to create 3 versions of each source image:
* Equal probability of one of the following 90-degree rotations: none, clockwise, counter-clockwise, upside-down

The following transformations were applied to the bounding boxes of each image:
* Random shear of between -15° to +15° horizontally and -15° to +15° vertically
* Random exposure adjustment of between -25 and +25 percent
* Random Gaussian blur of between 0 and 10 pixels
* Salt and pepper noise was applied to 5 percent of pixels

Provided by Rongxin Xu
License: MIT

Rongxin Xu (rxxu.mail@gmail.com)