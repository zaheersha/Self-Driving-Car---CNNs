# Self-Driving-Car---CNNs
Self-driving cars, also known as autonomous vehicles, have the potential to  revolutionize transportation by increasing safety and efficiency on the roads.
. One 
approach to developing self-driving cars is to use machine learning (ML), specifically 
a convolutional neural network (CNN), to map raw pixels from a single front-facing 
camera directly to steering commands. This end-to-end approach is effective 
because it allows the system to learn to drive in various traffic conditions, such as 
on local roads with or without lane markings, on highways, and in parking lots and 
unpaved roads, without explicit training in detecting specific features such as road 
outlines.
Using an end-to-end approach has several advantages over decomposing the 
problem into separate steps, such as lane marking detection, path planning, and 
control. First, it allows the system to optimize all processing steps simultaneously, 
leading to better overall performance. This is because the internal components 
self-optimize to maximize overall system performance, rather than optimizing 
intermediate criteria that may not necessarily result in the best performance. 
Second, it allows for the creation of smaller systems, as the system learns to solve 
the problem with the minimal number of processing steps.
Self-driving cars have the potential to impact a wide range of industries and 
applications, including transportation, ridesharing, delivery services, and even 
military and emergency response. Some potential advantages of self-driving cars 
include increased safety, increased efficiency, increased accessibility, increased 
convenience, reduced traffic congestion, and increased mobility. However, there 
are also challenges and potential drawbacks to consider, such as the potential for 
job loss in the transportation industry and the need for infrastructure and 
regulatory changes to support the deployment of autonomous vehicles. The selfdriving car system described in this abstract was trained using an NVIDIA DevBox 
2
and Torch 7 and operated using an NVIDIA DRIVETM PX self-driving car computer, 
both running Torch 7. The system operated at a frame rate of 30 frames per second 
(FPS), allowing it to make driving decisions in real-time.

How to Use
Download the dataset: https://github.com/SullyChen/driving-datasets  and extract into the repository folder

Use python train.py to train the model

Use python run.py to run the model on a live webcam feed

Use python run_dataset.py to run the model on the dataset

To visualize training using Tensorboard use tensorboard --logdir=./logs, then open http://0.0.0.0:6006/ into your web browser.
