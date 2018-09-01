BootStrap: docker
From: nvidia/cuda:9.0-cudnn7-devel-ubuntu16.04

%post
    # Set up some required environment defaults

    apt-get -y update && apt-get -y install git \
                                            python3 \
                                            python3-pip
    pip3 install numpy
    pip3 install https://storage.googleapis.com/tensorflow/linux/gpu/tensorflow_gpu-1.10.1-cp35-cp35m-linux_x86_64.whl

    apt-get clean
