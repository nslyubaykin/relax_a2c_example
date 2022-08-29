# Example A2C implementation with [ReLAx](https://github.com/nslyubaykin/relax)

This repository contains an [implementation](https://github.com/nslyubaykin/relax_a2c_example/blob/master/a2c_example.ipynb) of advantage actor critic (A2C) with ReLAx.

A2C actor was trained on LunarLander-v2 Gym environment for 4m env-steps. 

The graph of average return vs training step is shown below (`batch_size=40000`):

![a2c_training](https://github.com/nslyubaykin/relax_a2c_example/blob/master/a2c_training.png)

__Resulting Policy__:

https://user-images.githubusercontent.com/67604207/187156439-379b4336-e388-4e41-8166-112b76dcb869.mp4
