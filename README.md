SimpleRender
=========

A generic commandline templating system.

Currently only supports the mustache templating system (using pystache)

Installation
---
`pip install SimpleRender`

Usage
---
```
$ python render.py -h
usage: render.py [-h] [-o [OUT]] config template

Merge config and template files with the mustache templating engine.

positional arguments:
  config                The config file (JSON format)
  template              The template file

optional arguments:
  -h, --help            show this help message and exit
  -o [OUT], --out [OUT]
                        The output file
```
