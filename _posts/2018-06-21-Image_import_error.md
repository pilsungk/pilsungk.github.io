---
title: Image module import error (mglearn)
categories: python conda anaconda import error image
layout: post
---

[Jupyter Lab](https://www.youtube.com/watch?v=w7jq4XgwLJQ)을 설치한 후 [Intro to machine learning python](https://github.com/amueller/introduction_to_ml_with_python)의 코드에서 Image 모듈 import error가 발생하여
이리 저리 찾아 보다가 결국 conda update -all을 실행하였다.

처음엔 conda uninstall pillow 다음에 pip로 pillow를 설치하여 정상 동작 확인하였으나, 
conda와 pip를 함께 사용하면 나중에 또 문제가 생길까 찜찜하여 그냥 conda update -all 수행함.

<https://github.com/conda-forge/pillow-feedstock/issues/45>
