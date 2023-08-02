<!-- [![CS440 Banner](https://rgl.s3.eu-central-1.amazonaws.com/media/uploads/wjakob/2017/02/16/cs440-logo_web.jpg)](https://rgl.s3.eu-central-1.amazonaws.com/media/uploads/wjakob/2017/02/20/cs440-rgl.jpg) -->

![CS440 Banner](https://wjakob.github.io/nori/images/logo-beveled.png)

## Personal developments on Nori 2
![Build status](https://github.com/https://github.com/olivier-2018/nori_ray_tracer/workflows/Build/badge.svg)

### Acknowledgements
[Nori project website](https://wjakob.github.io/nori)   
[Nori Github repository](https://github.com/wjakob/nori)  
[Realistic Graphics Lab at EPFL](http://rgl.epfl.ch/)   

Nori is a simple ray tracer written in C++ used at the Realistic Graphics Lab to teach Advanced Computer Graphics to computer science Master students at EPFL.   

The publicly available source code therefore does not contain any rendering code but is meant for the students to develop their own full-fledged physically-based renderer as part of their assignments.   

The current repository contains my personal implementation of the rendering assignments. The results folder remains however private and not available for public download. See results sections below for illustrations.

Thanks for making the Nori source code (mostly) available.  
:oD

### Getting started
- fork the [Nori SOURCE repository](https://github.com/wjakob/nori) in Gihub
- clone the forked repository locally: 
```sh
git clone git@github.com:olivier-2018/nori_ray_tracer.git
cd nori_ray_tracer
```
- Create a git remote for the nori SOURCE repository
```sh
git remote add upstream git@github.com:wjakob/nori.git
git remote -v
```
- Pull the Nori source repo (in case a commit was made on the source repo since forking it): 
```sh
git pull upstream master
```
- Initialize submodules dependencies: 
```sh
git submodule update --init --recursive
```
- Commit locally and push to remote:
```sh
git push -u origin master
```


### Results
work in rogress
