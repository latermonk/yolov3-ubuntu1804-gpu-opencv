# yolov3-ubuntu1804-gpu-opencv 





#   Opencv

## Opencv 3.4.0   

```
apt update && apt install -y pkg-config cmake git php-cli php-dev && \
git clone https://github.com/opencv/opencv_contrib.git && \
git clone https://github.com/opencv/opencv.git && \
cd opencv_contrib && git checkout 3.4 && cd ../opencv && git checkout 3.4 && \
cd .. && mkdir build && cd build && \
cmake -D CMAKE_BUILD_TYPE=RELEASE -D CMAKE_INSTALL_PREFIX=/usr/local -D OPENCV_EXTRA_MODULES_PATH=../opencv_contrib/modules ../opencv && \
make -j6 && make install && \
ldconfig

``

https://github.com/php-opencv/php-opencv-examples/wiki/Installation-on-ubuntu      

https://yinguobing.com/install-ippcv-manually/     
https://www.cnblogs.com/yongy1030/p/10293178.html    
https://blog.csdn.net/orDream/article/details/84311697


https://www.learnopencv.com/install-opencv-3-4-4-on-ubuntu-18-04/





##  Opencv 4.1.1    
https://github.com/milq/milq/blob/master/scripts/bash/install-opencv.sh       
https://raw.githubusercontent.com/milq/milq/master/scripts/bash/install-opencv.sh


https://pjreddie.com/darknet/yolo/   
https://pjreddie.com/darknet/install/#cuda   
