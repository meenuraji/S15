# S15

Tried to make a deep neural network which can predict depth map and mask for foreground object

100 foreground and 100 background images are used and 4,00,000 images are created

few things I"ve learnt

it was tough to run the code because of heavy input and parameters. to overcome this issue transforms was used. and tried using the gray scale images

the code was trained for less number of epochs initially. this is done to check if the results are meeting the requirements.

As I understood that Mask can be predicted with less receptive field, I reduced depth of mask decoder

Used dialated convolutions in one of the convolution layer of downsampling block to reduce number of parameters

Foreground images

![Image](https://github.com/meenuraji/S15/blob/master/fgimg.png)

Background image

![Image](https://github.com/meenuraji/S15/blob/master/bgimg.png)

Depth images

![Image](https://github.com/meenuraji/S15/blob/master/depth.png)

Mask images

![Image]()

