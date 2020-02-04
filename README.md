# python-tutorial

## Installation
To run the examples and code we need Python and some additional libraries

Create a virtual environment
```
pip install virtualenv virtualenvwrapper
mkvirtualenv python-intro --python=python3
(python-intro) pip install -r requirements.txt

(python-intro) python -m ipykernel install --user --name=python-intro
```

## Slide presentation
Interactive slides can be generated with https://github.com/damianavila/RISE
```
pip install RISE
```
The slides can be served non-interactively via
```
jupyter nbconvert 01_python_introduction.ipynb --to slides --ServePostProcessor.port=8910 --post serve
```
