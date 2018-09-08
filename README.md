# staborb
Use synthetically integrated planetary systems to feed into a convolutional nerual network to predict orbital stability of planetary systems.
The idea is to use Genga (a fully paralelized GPU C++ code) to integrate a great number of planetary systems for a long enough orbital period. In this way, we will use this large dataset to train a deep convolutional neral network to predict orbital stability for other non-integrated planetary systems, only by passing it's initial state to the trained CNN model.
