CUDA 12.2


```
NVIDIA-SMI
```

https://code.visualstudio.com/docs/cpp/config-wsl
https://learn.microsoft.com/en-us/windows/wsl/install
666666
https://learn.microsoft.com/en-us/windows/wsl/install#upgrade-version-from-wsl-1-to-wsl-2

```
sudo apt-get update
sudo apt-get install build-essential gdb
sudo apt install nvidia-cuda-toolkit
```
https://docs.nvidia.com/cuda/cuda-installation-guide-linux/
https://docs.nvidia.com/cuda/cuda-installation-guide-linux/#network-repo-installation-for-wsl

export CUDA_HOME=/usr/local/cuda

wsl --set-version Ubuntu 2

gcc --version
sudo wget https://developer.download.nvidia.com/compute/cuda/repos/wsl-ubuntu/x86_64/cuda-keyring_1.1-1_all.deb
sudo dpkg -i cuda-keyring_1.1-1_all.deb


/sbin/ldconfig.real: Can't link /usr/lib/wsl/lib/libnvoptix_loader.so.1 to libnvoptix.so.1
/sbin/ldconfig.real: /usr/lib/wsl/lib/libcuda.so.1 is not a symbolic link


Success!