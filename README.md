# Simple-AVSAD

### Instructions: How to run the code? -- please finish

The code is based on simple-avsd model.

### Required Environment

1, python 3
2, pytorch 1.1
3, numpy
4, six
5, coco-evaluation tools for python 3

### How to run the code?

1, Download all codes and dataset from https://github.com/idansc/simple-avsd
2, Replace all python files in "code" and "utils" folders with files provided in this repository
3, Please use command 
      bash run.sh
  to run the code.
  
The run.sh script has 4 stages

stage 1 - preparation of dependent packages
stage 2 - training
stage 3 - generation of sentences on test-set
stage 4 - evaluation of generated sentences

### TODOs

1. Feature analysis: how different features contribute to the task? 

2. Feature fusion: how to integrate features from different modalities?
