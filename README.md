# Pre-trained Image Classifier to Identify Dog Breeds

There is a repository to store my project for my nanodegree studies. It's a classifier implementation written in Python that identify dog breeds.

### Samples Archs Scores
![Resnet](https://s3.amazonaws.com/in3d-site/portfolio/pre-trained-image-classifier-dog-breed/resnet.jpeg "Resnet")
![Alexnet](https://s3.amazonaws.com/in3d-site/portfolio/pre-trained-image-classifier-dog-breed/alexnet.jpeg "Alexnet")
![VGG](https://s3.amazonaws.com/in3d-site/portfolio/pre-trained-image-classifier-dog-breed/vgg.jpeg "VGG")

### Dependencies

Clone this repository.

```sh
$ git clone https://github.com/mmoraisa/pre-trained-image-classifier-dog-breed
```

Install the dependencies using PIP.

```sh
$ pip install -r requirements.txt
```
or

```sh
$ pip3 install -r requirements.txt
```

### How it works

You can use it:

```sh
$ python check_images.py --dir pet_images/ --arch resnet  --dogfile dognames.txt > resnet_pet-images.txt
```
#### Command Line Arguments:
  1. Image Folder as --dir with default value 'pet_images'
  2. CNN Model Architecture as --arch with default value 'vgg'
  3. Text File with Dog Names as --dogfile with default value 'dognames.txt'

License
----

MIT


**Free Software, Hell Yeah!**
