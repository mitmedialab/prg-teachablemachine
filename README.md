
## NEW:

Want to bring Teachable Machine into your own web creations?

We’re working on a library called _teachablemachine.js_ which will let you do just that. Here’s the first remixable demo you can play with to get a sneak peek at what’s possible:

[Hello Wizard](http://glitch.com/edit/#!/tm-wizard?path=README.md%3A1%3A0) - This demo shows how you can drop a machine learning “training wizard” on top of your website with just a few lines of code.

# Teachable Machine Community

![Teachable Machine](./teachablemachine.gif)

### What is Teachable Machine?

[Teachable Machine](https://teachablemachine.withgoogle.com/) is a web-based tool that makes creating machine learning models fast, easy, and accessible for everyone. [You can try it here](https://teachablemachine.withgoogle.com/).

### Who is it for?
Educators, artists, students, innovators, makers of all kinds – really, anyone who has an idea they want to explore. No prerequisite machine learning knowledge required.

### How does it work?
You train a computer to recognize your images, sounds, and poses without writing any machine learning code. Then, use your model in your own projects, sites, apps, and more.

### What is this repository for?

This repository contains two components of [Teachable Machine](https://teachablemachine.withgoogle.com/):

1. **A [libraries](/libraries) section** that contains all of the machine learning code used in Teachable Machine. Under the hood we use [Tensorflow.js](https://www.tensorflow.org/js), a library for machine learning in Javascript, to train and run the models you make in your web browser. The `libraries` section also contains the API for [image](/libraries/image), [audio](/libraries/audio), and [pose](/libraries/pose) helper libraries that make it easier to use the models exported by Teachable Machine in your own projects.

2. **A [snippets](/snippets) section** that contains markdown snippets that are being displayed inside the export panel in [Teachable Machine](https://teachablemachine.withgoogle.com/). These snippets contain code and instructions on how to use the exported models from Teachable Machine in languages like Javascript, Java and Python.

### How can I send feedback or get in contact with you?

You have a few options:

* [Use this form](https://forms.gle/uthe2C4tZNPA11GX7).  
* Share your projects using [#teachablemachine](https://twitter.com/hashtag/teachablemachine) on Twitter or on the [Experiments with Google](https://experiments.withgoogle.com/submit) page.
* Open an issue in this repository.

## Community Contributions and Projects

* [Teachable Machine Node Library for image models](https://github.com/tr7zw/teachablemachine-node-example)
* [Teachable Machine Mobile for image models](https://github.com/mstale007/Teachable_Machine_Mobile/tree/master)


## Disclaimer

This is an experiment, not an official Google product. We’ll do our best to support and maintain this experiment but your mileage may vary.

We encourage open sourcing projects as a way of learning from each other. Please respect our and other creators’ rights, including copyright and trademark rights when present, when sharing these works and creating derivative work. If you want more info on Google's policy, you can find that [here](https://www.google.com/permissions/).
# Teachable Machine Libraries

This section contains support libraries for the new version of Teachable Machine. For more info go to: [Teachable Machine](https://teachablemachine.withgoogle.com/io19).

## Model Libraries

| Library | Based on model  | Details                                                 | Install | CDN | 
|---------|-----------------|---------------------------------------------------------|---------|-----|
| [Image](./image/) | [MobileNet](https://github.com/tensorflow/tfjs-models/tree/master/mobilenet)       | Use a model trained to classify your own images         | `npm i @teachablemachine/image` | [![](https://data.jsdelivr.com/v1/package/npm/@teachablemachine/image/badge)](https://www.jsdelivr.com/package/npm/@teachablemachine/image) |
| [Audio](./audio/)   | [Speech Commands](https://github.com/tensorflow/tfjs-models/tree/master/speech-commands) | Use a model trained to classify your own audio snippets | npm i @tensorflow-models/speech-commands     | [![](https://data.jsdelivr.com/v1/package/npm/@tensorflow-models/speech-commands/badge)](https://github.com/tensorflow/tfjs-models/tree/master/speech-commands) | 
| [Pose](./pose/)   | [PoseNet](https://github.com/tensorflow/tfjs-models/tree/master/posenet) | Use a model trained to classify body poses | `npm i @teachablemachine/pose`     | [![](https://data.jsdelivr.com/v1/package/npm/@teachablemachine/pose/badge)](https://www.jsdelivr.com/package/npm/@teachablemachine/pose) |

## Development

You must use a node version > 12.


