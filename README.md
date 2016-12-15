#coaster_racer_bot

##Overview:
This is an attempt at Sirajology's openai Universe coding [challenge](https://www.youtube.com/watch?v=mGYU5t8MO7s&t=11s).
It is a Q-Deep Learning model that learns the flash game CoasterRacer based on only the pixels and the score as read by Universe.

##A Video of it in action
Keep in mind that epsilon is still .67 at this point: [YouTube](https://youtu.be/k1iWUnPV_og)

##Dependancies

* tensorflow
* cv2
* numpy
* random
* collections
* gym
* universe

##Usage:

Either run train.py to train the model or demo.py to see it in action. Demo.py requires the TensorFlow session to be fetched from: [Google Drive](https://drive.google.com/drive/folders/0BxBNZu1wzSbkdzFpREFtcW40NVU?usp=sharing).
Note that train.py doesn't render anything and as such needs to be VNCd into to see whats happening.
Demo.py is broken at point of upload will be fixed in the future. (I don't kniow how to correctly restore TF variables)

##Credits

I got this code from ||Source|| here on github who "merely wrapped, updated and documented it" from [malreddysid](https://github.com/malreddysid) I jus poorly used this for my universe implementation