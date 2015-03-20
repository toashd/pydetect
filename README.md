# pydetect

Some fun with Python, OpenCV, and barcoded images.

### Usage

```
$ python detect_barcode.py --image images/barcode_01.jpg
```

### Installation
The easiest way to install [OpenCV](http://opencv.org/) on a Mac is to use pip and brew. OpenCV needs [numpy](http://www.numpy.org/) to be installed, so make sure it is properly installed.

```
$ pip install numpy
```

```
$ brew tap homebrew/science
$ brew info opencv
$ brew install opencv
```

There can be problems with libpng, that can be solved by unlinking and linking again. Also it could be helpful to update and upgrade brew before installation.

```
$ brew update && brew upgrade`
$ brew unlink libpng && brew link libpng
```
