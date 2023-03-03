# put-jetson
Nvidia Jetson Nano setup guide

## Official guide to start with
[Nvidia Guide](https://developer.nvidia.com/embedded/learn/get-started-jetson-nano-devkit#write)

## Download image
Download from official [repo](https://developer.nvidia.com/jetson-nano-sd-card-image)

## Setup

```sh
export PATH=/usr/local/cuda/bin${PATH:+:${PATH}}
export LD_LIBRARY_PATH=/usr/local/cuda/lib64\${LD_LIBRARY_PATH:+:${LD_LIBRARY_PATH}}
```
