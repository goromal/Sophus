# Sophus

## Overview

This is a c++ implementation of Lie groups commonly used for 2d and 3d geometric problems (i.e. for Computer Vision or Robotics applications). Among others, this package includes the special orthogonal groups SO(2) and SO(3) to present rotations in 2d and 3d as well as the special Euclidean group SE(2) and SE(3) to represent rigid body transformations (i.e. rotations and translations) in 2d and 3d.

[API documentation](https://strasdat.github.io/Sophus/genindex.html)

## Installation (Linux)

```bash
./install.sh
```

For access to Python library, add to .bashrc:

```bash
export PYTHONPATH="$PYTHONPATH:/path/to/Sophus/py"
```

## Usage

In your CMakeLists.txt file, add:

```cmake
find_package(Sophus 1.0)

...

target_link_libraries(myprogram PRIVATE Sophus::Sophus)
```

For use in python:

```python
import sophus
```
