# COARV-raytracing

A C++ raytracing engine project for the COARV subject at École Centrale de Nantes

## Introduction

This project is the result of the tutorial "Create your own FPS in WebGL" available on GitHub proposed as of the COARV subject. 
At the end, the last image took me half a day, so I spent some time researching about multithreading in C++ and decided to experiment with the std::future, after some modifications on the core loop I got it to render in less than an hour and a half.

## Getting started

### Installation

There are no dependencies for this project, so you can just do:

1. Clone the repo:
```sh
git clone https://github.com/iagocaran/COARV-raytracing.git
```
2. Build with cmake
```sh
cmake .
make
```

## Usage

The project will output an image to cout and the progress to cerr, so you can just run like this to get the output:
```sh
raytracing > image.ppm
```

Note: The final render is a quite big image with lots of samples, so this takes quite a while to render (half a day on a 4600H).

## Contact

* [iagocaran](https://github.com/iagocaran)

## Credits

* Peter Shirley for his [Ray Tracing in One Weekend book](https://raytracing.github.io/books/RayTracingInOneWeekend.html).
