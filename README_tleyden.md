
## Installing Octopus


### Verify cuda compiler

```
git clone https://github.com/NVIDIA/cuda-samples.git
git checkout v11.6
make
```

I had to install a few more packages:

```
sudo apt-get install freeglut3-dev
sudo apt-get install libglfw3 libglfw3-dev
```

### Create conda env

```
conda create -n octopus python=3.9 -y
```

### Install DIRT

```

```