# Grepman
Simple bash script that aim to save time on security code and config review for web technologies.

## Prerequisites

- gem
- pip
- grep

## Install

```bash
$ git clone https://github.com/mathis2001/Grepman.git
$ cd Grepman
$ chmod +x grepman
```

## Usage

```bash
$ ./grepman /path/to/project [--php] [--py] [--ruby] [--java] [--js] [-s] [--wl <wordlist>]
```

## Options

```bash
    -h       Show this help message
    -s       Check for secrets
    --php    Run checks on PHP code
    --py     Run checks on Python code
    --ruby   Run checks on Ruby code
    --java   Run checks on Java code
    --js     Run checks on JavaScript code
    --wl     Run checks with a custom regex wordlist
```
