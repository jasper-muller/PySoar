# PySoar

A tool for analyzing glider competitions: taking IGC files as input and delivering an Excel sheet
as output. The programm can be run on windows, mac and linux.

## Stand alone versions
Stand alone versions can be found under [releases](https://github.com/GliderGeek/PySoar/releases)

## Installation and Setup of source code
1. Install python requirements

```
pip install -r requirements.txt
```

## Limitations
The following assumptions are made

- turnpoints are always circles
- no AAT
- no ENL logging
- no restart after 1st turnpoint
- start with glide over start line
- maximum of 9 legs