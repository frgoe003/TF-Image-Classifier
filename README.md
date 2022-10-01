<a name="readme-top"></a>

<!-- PROJECT SHIELDS -->
<!--
*** I'm using markdown "reference style" links for readability.
*** Reference links are enclosed in brackets [ ] instead of parentheses ( ).
*** See the bottom of this document for the declaration of the reference variables
*** for contributors-url, forks-url, etc. This is an optional, concise syntax you may use.
*** https://www.markdownguide.org/basic-syntax/#reference-style-links
-->

<!-- PROJECT LOGO -->
<br />

<h3 align="center">Identifying Flowers: An Image Classifier built with Tensorflow</h3>

  <p align="center">
    Deep Learning Project of [Udacity Nanodegree]: Intro to Machine Learning with Tensorflow
    <br />
    <a href="https://github.com/frgoe003/TF-Image-Classifier"><strong>Explore the docs »</strong></a>
    <br />
  </p>
</div>



<!-- ABOUT THE PROJECT -->
## About The Project

This project uses the **Oxford Flowers 102 dataset** provided by the [Visual Geometry Group of University of Oxford]((http://www.robots.ox.ac.uk/~vgg/data/flowers/102).

The dataset consists of 102 different flowers commonly found in the United Kingdom. For each flower class approx. 40 to 258 images are provided.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

### Built With

This project was built in Python 3.x and the following Jupyter Notebook IDE. The following libraries were used:

* Numpy, pandas
* Tensorflow (version 2.1.0)
* Tensorflow datasets(tfds)

Additonally, a GPU-enabled workplace was used, which significantly improved processing and training time.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

### Usage

The project files include a `predict.py` file that uses a pre-trained network to predict the class for an input image. 

`predict.py` reads an image and a saved Keras model and then prints the most likely image class and it's associated probability.

<!-- LICENSE -->
## License

Distributed under the MIT License.

<p align="right">(<a href="#readme-top">back to top</a>)</p>


<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[Udacity Nanodegree]: (https://www.udacity.com/course/intro-to-machine-learning-with-tensorflow-nanodegree--nd230)
