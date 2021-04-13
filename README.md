# ASP parser and solver in Python

## dependencies

this is to install required software by means of conda:
```
conda install -c potassco clingo
conda install -c conda-forge antlr-python-runtime
``` 

Otherwise: 

**clingo** (the ASP solver)
- download the sources from [https://github.com/potassco/clingo]
- compile the python library following the instructions
- add the library to the project dependencies 

To work on the grammars, you need to download the ANTLR complete JAR file and the necessary Python module.
The easiest way is using pip.

> pip install antlr4-python2-runtime


