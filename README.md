# About

This is the source code for my resume. It uses `LaTeX` and the `friggeri-cv` template, which was originally developed by Adrien Friggeri and improved by Zhen-Huan Hu.

# Build

You will need `xelatex` and `biber` to build this document from source. Once you have the required packages installed, you can use Make to build the documents. On the Mac, I installed MacTex first and that took care of all the dependencies.

If you want to make consetic changes is bibliography, please look at the types available in friggeri-cv.cls to use or modify.


To build the shorter, resume version:

```
$ make resume
```

To build the longer, curriculum vitae version:

```
$ make cv
```
