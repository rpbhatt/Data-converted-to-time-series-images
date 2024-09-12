This repository contains 678 images named "image_001.png" to "image_678.png". Each image contains 991 rows and 7 columns of pixels.
Network data containing 671898 rows of data was split into 678 equal parts. Each part represented data for 991 cells for the same timestamp.
Each 678 equal part was converted into images to obtain these png files. Therefore, each image represents one timestamp and contains data for 991 cells.
The timestamps are in increasing order, and therefore, image_001.png can be considered as first frame of a video, image_678.png can be considered as 678th frame of a video.
This data-set can be considered as an example to show-case that any big data-set, when converted into images, can be used as frame of a video and video prediction algorithms
can be used to predict one or more frames. In this data-set, each column represents one data-point. If there are 100 data points, it would lead to 100 columns of the matrix, 
and hence, 100 columns of pixels in such images.
Video prediction algorithms can be applied on this data-set considering these images as frames of a video.
