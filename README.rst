MTCNN
#####

.. image:: https://badge.fury.io/py/mtcnn.svg
    :target: https://badge.fury.io/py/mtcnn
.. image:: https://travis-ci.org/ipazc/mtcnn.svg?branch=master
    :target: https://travis-ci.org/ipazc/mtcnn


Implementation of the MTCNN face detector. It is written from scratch, using as a reference the implementation of
MTCNN from David Sandberg (`FaceNet's MTCNN <https://github.com/davidsandberg/facenet/tree/master/src/align>`_) in Facenet. It is based on the paper *Zhang, K et al. (2016)* [ZHANG2016]_.

 .. image:: https://github.com/vaibhavhariaramani/-FaceDetectionMTCNN/blob/master/combine.jpeg


INSTALLATION
############

Currently it is only supported Python3.4 onwards. It can be installed through pip:

.. code:: bash

    $ pip install mtcnn

This implementation requires OpenCV>=4.1 and Keras>=2.0.0 (any Tensorflow supported by Keras will be supported by this MTCNN package).
If this is the first time you use tensorflow, you will probably need to install it in your system:

.. code:: bash

    $ pip install tensorflow

or with `conda`

.. code:: bash

    $ conda install tensorflow

Note that `tensorflow-gpu` version can be used instead if a GPU device is available on the system, which will speedup the results.

