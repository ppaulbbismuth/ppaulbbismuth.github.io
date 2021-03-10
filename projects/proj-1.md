---
layout: post
title: 'Fast Autonomous Drone Landing Master Thesis'
---
There is an increasing demand for fast drone deliveries for both consumer’s necessities and medical emergencies. All aircraft are subject to landing difficulties because of near-ground aerodynamic effects and complications with moving from air to land. In addition to improving delivery, there have been many developments within space research aiming to reduce global cost. Reusable rockets are regarded as the future of space travel, however, numerous accidents have been observed during landing, making these rockets an unreliable resource for experimentation. The standard approach for both drone delivery and reusable rockets requires speed reduction before landing, as explained by the lack of precision of the embedded sensors combined with the fragility of the frame. The landing shock thus needs to be attenuated to deform irremediably the frame structure. Therefore there is a need for improvement of landing approach for more reliability. The main research contents of this thesis cover different areas forthe development of a newly designed electric thrust vectored rocket that aims to incorporate afast landing approach using this new benchmark system.

#### Drone Perception

The research proposes a way to generate accurate photorealistic dataset for a given landing pad. It is then possible to use it for supervised learning.

{% include image-static.html image="projects/proj-1/camera-vision.jpg" %}

The proposed dataset generator gives a way to feed the neural networks. It has then the ability to accurately estimate its position with a wide range of vision. Thanks to an appropriate landing pad shape, even seeing only part of the landing area permits the drone to descend.

#### Guidance and Control

For visual servoing, a multi-scale control is proposed where control sensitivity depends on drone altitude. Using the neural network in a simulated environment, the processing rate has been multiplied by three.

{% include image-static.html image="projects/proj-1/drone-land.gif" %}

#### Mechanical Landing Gear

For fast landing situations, the vertical speed is higher than standard descent. The research proposes a landing gears that absorbs more than ten times the kinetic energy of standard landing leg. A patent filing currently protects the concept.

{% include image-static.html image="projects/proj-1/landing-gear.jpg" %}