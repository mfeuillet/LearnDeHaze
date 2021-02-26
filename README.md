# LearnDeHaze

# Table of Contents
* [Team Members](#team-members)
* [Synopsis](#Synopsis)
* [Note](#note)
* [Motivation](#motivation)
* [Installation](#installation)
* [Example](#example)

## <a name="team-members"></a>Team Members
* "Maximilian FEUILLET" <maximilian.feuillet@ensta-bretagne.org>


## <a name="Synopsis"></a>Synopsis

An engineering school project to make a general underwater dehazing network using autoencoders. 
This code implements a novel dehazing algorithm comprised of several autoencoders. It was made to dehaze real underwater images.

## <a name="note"></a> Note
This project is ongoing, and the results are therefore not yet very adequate for a real-life use.

## <a name="motivation"></a> Motivation

There is an increasing need in developing generalistic and performing underwater dehazing algorithms, whether it be for military, research or industrial applications.
The emergence of Deep Learning in  the 1990s accelerated the development of new techniques in this growing field.


## <a name="installation"></a>Installation

**For training:**

* Download the *training* notebook available in the repository, as well as the Zip file containing the images ( **IMPORTANT : keep the same names for the Images folder**) and the two .py files .
* Make sure you have *Keras* installed and updated, as well as *Glob* , *opencv* and *tensorflow* on Python. CUDA must be installed and functional. 
* **If you do not have tensorflow-gpu already configured, we advise you to use the CPU version** . For that, uncomment the parts with *with tf.device("/CPU:0):*

* **Versions used:** tensorflow 2.4.0     cv2 4.4.0       keras 2.4.3     numpy 1.19.4

* Place the *training* notebook in a same folder as the *Images* folder and the two .py files. They contain some additional functions for the FLIP indicator.

* You can now launch the *training* notebook. Make sure to have a powerful enough GPU, or switch to CPU.
* 
**For usage:**

* Download the *usage* notebook available in the repository, as well as the Zip file containing the images ( **IMPORTANT : keep the same names for the Images folder**) and the two .py files. You also need the weights file.
* Make sure you have *Keras* installed and updated, as well as *Glob* , *opencv* and *tensorflow* on Python. CUDA must be installed and functional.
* **If you do not have tensorflow-gpu already configured, we advise you to use the CPU version** . For that, uncomment the parts with *with tf.device("/CPU:0):*

* **Versions used:** tensorflow 2.4.0     cv2 4.4.0       keras 2.4.3     numpy 1.19.4

* Place the *usage* notebook in a same folder as the *Images* folder, the weights file and the two .py files. They contain some additional functions for the FLIP indicator.

* You can now launch the *usage* notebook, it will select some images from each subset and convert them.



## <a name="example"></a> Example

![example1](https://your-copied-image-address)
![example2](https://your-copied-image-address)


## License
All rights reserved.
