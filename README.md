<div align="left">
        <img width="25%" src="images/deeplearninginside2.png" alt="About screen" title="About screen"</img>
</div>

## DeepLearningMaster Repository

This repository contains notebooks used in DEEP LEARNING COURSE of the [MASTER IN FUNDAMENTAL PRINCIPLES OF DATA SCIENCE](http://www.ub.edu/datascience/master/) of the Universitat de Barcelona.

## Course Description

Deep learning is one of the fastest growing areas of machine learning and a hot topic in both academia and industry. This course will cover the basics of deep learning by using a hands-on approach.

## Course Instructor

[Jordi Vitrià](http://www.ub.edu/cvub/jordivitria/)

## Class Time and Location

+ 2ond Semester (February - May, 2019)
+ Lecture: Tuesday 15:00h-17:00h
+ Location: Aula B1, Facultat de Matemàtiques i Informàtica, Universitat de Barcelona. [Map](https://www.google.es/maps/place/Gran+Via+de+les+Corts+Catalanes,+585,+08007+Barcelona/@41.3865736,2.1619408,17z/data=!3m1!4b1!4m5!3m4!1s0x12a4a28cbeee3689:0x4b4a8ba716765923!8m2!3d41.3865736!4d2.1641295?hl=ca).

## Prerequisites

+ Proficiency in Python (3.6): All class assignments will be in Python (using ``tensorflow`` and ``keras``). 
+ Calculus, Linear Algebra, Optimization: You should be comfortable taking derivatives and understanding matrix vector operations and notation.
+ Basic Probability and Statistics.
+ Machine Learning.

If you are not used to Git, you can complete this free online git [course](https://try.github.io/levels/1/challenges/1)

## Grading

+ Assignment #1: 30%. Submission deadline (UB Campus Virtual): **April Xth, 2019.**
+ Assignment #2: 30%. Submission deadline (UB Campus Virtual): **May Xth, 2019.**
+ Assignment #3: 40%. Submission deadline (UB Campus Virtual): **June Xth, 2019**

Study groups are allowed but we expect students to understand and complete their own assignments and to hand in one assignment per student.

## Course Agenda
<ol type="1">
<li>  Introduction to Deep Learning and its applications. Using the Jupyter notebook & Docker. Software stack. 
<li>  Basic concepts: learning from data.
<li>  Automated differentiation & Backpropagation, Training a Neural Network from Scratch.                     
<li>  Tensorflow programming model. Dense Neural Networks.                                                     
<li>  Keras.                                                           
<li>  Recurrent Neural Netwoks I.                                                                              
<li>  Recurrent Neural Netwoks II.                                                                             
<li>  Embeddings.                                                                                              
<li>  Convolutional Neural Networks I.                                                                         
<li>  Convolutional Neural Networks for Large Scale Learning.                                                  
<li>  Unsupervised Learning I.                                                                                 
<li>  Unsupervised Learning II.                                                                                  
<li>  Deep Reinforcement Learning.                                                                                     
</ol>

## Course Software Installation 

You can develop deep learning applications with Google Colaboratory (Colab) -on the free Tesla K80 GPU- using Keras and Tensorflow. Colab is a Google internal research tool for data science. They have released the tool sometime earlier to the general public with a goal of dissemination of machine learning education and research. 

You can find more information in this blogs: 
+ https://medium.com/deep-learning-turkey/google-colab-free-gpu-tutorial-e113627b9f5d
+ https://medium.com/tensorflow/colab-an-easy-way-to-learn-and-use-tensorflow-d74d1686e309

## Course Software Installation

You can run the course software using a **Docker container**. 

> A gentle introduction to docker: [How Docker Can Help You Become A More Effective Data Scientist](https://towardsdatascience.com/how-docker-can-help-you-become-a-more-effective-data-scientist-7fc048ef91d5)

There’s full documentation on installing Docker at ``docker.com``, but in a few words, the steps are:

+ Go to ``docs.docker.com`` in your browser.
+ Step one of the instructions sends you to download Docker.
+ Run that downloaded file to install Docker.
+ At the end of the install process a whale in the top status bar indicates that Docker is running, and accessible from a terminal.
+ Click the whale to get ``Preferences``, and other options.
+ Open a command-line terminal, and run some Docker commands to verify that Docker is working as expected.
Some good commands to try are ``docker version`` to check that you have the latest release installed, and ``docker ps`` and ``docker run hello-world`` to verify that Docker is running. 
+ By default, Docker is set to use 2 processors. You can increase processing power for the app by setting this to a higher number in ``Preferences``, or lower it to use fewer computing resources.
+ Memory - By default, Docker is set to use 2 GB runtime memory, allocated from the total available memory on your computer. You can increase the RAM on the app to get faster performance by setting this number higher (for example to 3) or lower (to 1) if you want Docker to use less memory.

Once Docker is installed, you can download the **image of this course** and download this git repository:

+ In a terminal, go to your course folder and run (This operation requires a good internet connection; it will take some minutes):  ``docker pull datascienceub/deepub``    
+ MacOS & Linux: Run the ``deepub`` image on your system: ``docker run -it -p 8888:8888 -p 6006:6006 -v /$(pwd):/notebooks datascienceub/deepub``
+ Windows: Run the ``deepub`` image on your system: ``docker run -it -p 8888:8888 -p 6006:6006 -v C:/your_course_folder_path:/notebooks datascienceub/deepub``
+ Once these steps have been done, you can check the installation by starting your web browser and introducing the referred URL.
+ Finally, to have the contents of this repository in your computer, open terminal from your browser and execute this instruction: ``git clone https://github.com/DataScienceUB/DeepLearningMaster2019``.

To run this image:

+ Windows: In a terminal, go to your course folder and run the ``deepub`` image on your system: ``docker run -it -p 8888:8888 -p 6006:6006 -v C:/your_course_folder_path:/notebooks datascienceub/deepub``.
+ MacOS & Linux: In a terminal, go to your course folder and run the ``deepub`` image on your system: ``docker run -it -p 8888:8888 -p 6006:6006 -v /$(pwd):/notebooks datascienceub/deepub``
+ Start your web browser and introduce the corresponding URL.

Next times, if there are new contents in the repository, you can bring your local copy of the repository up to date:

+ Open a new Jupyter notebook and execute this instruction in a code cell: 
``!git pull https://github.com/DataScienceUB/DeepLearningMaster2019``

