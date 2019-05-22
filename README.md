###### Note: This repository is for the OUI JavaScript runtime. For the C++ library go here: [Engine](https://github.com/nik-m2/OUI-engine)

# OUI

<p align="center">
    OUI is a cross-platform UI engine written from the ground up in C++. It allows you to easily build programs with rich UIs that can be built for <a href="#supported-platforms">many operating systems</a>. The functionality for your program can be written in C++ or JavaScript (coming soon).
    <br><br>
    Simple Demo App
    <br>
    <img src="https://user-images.githubusercontent.com/20328954/55766682-bb1c1800-5a43-11e9-9a90-2d085f60d916.gif"/>
<p align="center">
    
## Setup

<section>
<summary>Windows</summary>
Download NodeJS if not already installed - https://nodejs.org/en/download/

</section>

Download python3 if not already installed https://www.python.org/
    - Note: `node-gyp` uses python2, which will be installed automatically

With administrator permissions:
```
npm install --global --production windows-build-tools
```

then:
```
npm install --global node-gyp
python3 scripts/setup.py
```

```
node-gyp configure
node-gyp build
```
