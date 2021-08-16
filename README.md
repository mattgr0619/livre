# Music Classification with Convolution

It is without a doubt that the AI revolution is upon us. From Google’s AlphaFold uncovering the human genome to optimized recommendation systems that improve companies such as Airbnb and Amazon, we certainly are not going to be hearing about it anytime soon.

Perhaps one of the biggest areas where AI is taking over (or maybe better characterized as ML -- see differences here), is deep learning. What is deep learning?

Deep learning, simply stated, is an advanced type of data analysis that originated in the 1940’s and is attributed to Alan Turing and Walter Pitts, among many other burgeoning mathematicians and engineers. This type of analysis allows you to take an array of data (oftentimes an image), and reduce its dimensionality to a classification (the classic example is classifying images as either cats or dogs). These algorithms are exciting, as they can solve complex issues, like serving as the “eyes” of a self-driving car (think image classification as either “drive that way” or ”dont drive that way”). Aso exciting, although such AI capabilities are being scaled at the mass department/lab/company-wide level, the great thing is that it can be scaled and tinkered with at the individual level -- and for free!

One thing I recently found out is that the algorithms are also being used to categorize sound and music. By converting a sound into a spectrogram, or essentially a three dimensional frequency (y) and amplitude (color) over time (x) graph (look below too for an example), these algorithms are able to approach sound the way they approach sight -- as an array! 

Here is an example of a spectrogram:
![1_V2mgZ7y0ngd3q4DZ01xkEQ](https://user-images.githubusercontent.com/52679590/129635984-ca19474e-ee03-45f2-84aa-70ad4e92b9e4.png)


It represents frequency (Hz) over time (s), and also includes a representation of amplitude (volume), showing louder sounds/frquencies as brighter. Clips such as these are fed into a binary classifier to distinguish the prominent distiguishing features of one class vs. another.

For more resources on this, check here:
<li>https://towardsdatascience.com/musical-genre-classification-with-convolutional-neural-networks-ff04f9601a74
<li>https://towardsdatascience.com/neural-networks-for-music-generation-97c983b50204

<br>
<br>

The current project:
<br>
<li>Aim: to create my own music classifier that can distinguish between music I like and music I don’t (binary classifier).
<br<
<li>Secondary aim: to attain high classification accuracy without the need for large training data samples.
<br>
<li>Data: 
<br>
A “train” sample of seven songs I like, all of which have the commonality of being Rap/RnB music from the late 90’s/early 2000’s:
<br>
<li>Dice of Life by Andre Nickatina 
<li>Roc Da Mic by Beanie Sigel feat Freeway
<li>Gangsta Lean by Clipse
<li>Señorita by Justin Timberlake
<li>Big Head by Ms. Jade
<li>Get By by Talib Kweli  
<li>Overnight Celebrity by Twista




