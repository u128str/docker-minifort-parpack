# docker-minifort-parpack
Dockerfile to build: Ubuntu 16.03 with gfortran openMPI MKL parpack

To build it on your local machine type:

```
$ docker build --no-cache -t lr-mctdhb .
```
__ prerequisites:__ 

. installed docker
. internet connection 

Why?, instead, not to use the already existing docker image with ```$ docker pull mctdhb/minifort-parpack```

Answer: __it is 4.3BG__ !!! So it is simpler to rebuild locally
