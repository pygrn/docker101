# Docker 101 LAB

[HTML Slides](http://htmlpreview.github.io/?https://github.com/pygrn/docker101/blob/master/Docker101.slides.html)

## How to use view it?

Just open the slides in your preferred format:
- [HTML](Docker101_lab.slides.html) *//recommended*


## How to play with it?

1) Install requirements

```
$ pip install -r requirements.txt
```

2) Start the notebook server

```
$ jupyter notebook Docker101_lab.ipynb
```
, and a new browser pointing to the notebook will be raised


### Render slides in html format

```
$ jupyter nbconvert --to slides Docker101_lab.ipynb --post serve
```

### Slides mode inside the notebook

To see the slides inside the notebook, just activate RISE extension
```
$ jupyter-nbextension install rise --py --sys-prefix
$ jupyter-nbextension enable rise --py --sys-prefix
```
, and press "Alt + R"

