This is a Keras based implementation of the algorithm detailed in the paper [A Neural Algorithm of Artistic Style](https://arxiv.org/abs/1508.06576) by Gatys et al.

Inspiration came from an exercise in the [Convolutional Neural Networks](https://www.coursera.org/learn/convolutional-neural-networks/home/welcome) course from Coursera.

The idea behind the algorithm is to take the essence of a Style image (**S**), apply it on the Content image (**C**) and create the Generated image (**G**).

**G** is basically **C** recreated in the style of **S**.
