# VALIDHTML

## Introduction

validhtml is a simple script that allows you to check your html files validity, using the W3C API. It also open the files in XHTML format in your default browser.

## Quick Tutorial

Syntax : 

```
validhtml [FILE 1] [FILE N]
```
```
validhtml [FOLDER]
```
```
validhtml *.html
```

Examples :

```
validhtml ./your_folder/index.html
```
```
validhtml ./your_folder/*.html
```

## Contribution

This bash script is not perfect, so feel free to suggest any improvement. 

W3C API : https://github.com/validator/validator/wiki/Service-%C2%BB-Input-%C2%BB-POST-body

NOTE : you can use *out=text* to get the response in String format (as used in the script). An improvement may come to specify the url of the page you want to check.

## Issues

The script uses the browser specified in the $BROWSER environment variable. You can change this value by editing your .profile file. Just add for example :

```
export BROWSER=/usr/bin/firefox
```
