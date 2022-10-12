# Convert_Keras_to_Pytorch
```
(Sungduk Yu: Wed Oct 12 19:18:39 EDT 2022)

This python program converts a Keras model to a Pytorch model (in two versinos: serialized model and traced model).

Usage: python convert_keras_to_pytorch.py <arg1> <arg2> <arg3>
       <arg1>: File name of a keras model to be converted
       <arg2>: (optional) File name of a converted pytorch model.
               If it's not supplied, arg2=arg1+'.converted.pt'
       <arg2>: (optional) File name of a converted pytorch model (traced).
               If it's not supplied, arg3=arg1+'.converted.traced.pt' (or arg3=arg2+'.traced.pt', if arg2 is supplied)

Currently it supports the following layers only:
dense, relu, leakyrelu, sigmoid, batchnormalization, dropout
```
