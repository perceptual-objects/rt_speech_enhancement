---
layout: page
title: Demos
description:
importance: 1
category: front
---

#### Realtime front speech enhancement with interfering voice suppression

This is the initial demo of our deep-learning based speech
enhancement system that suppresses both environmental noise and interfering voices so the
user can focus on the front voices in their vicinity. The system is designed
to run in realtime at the edge.

The audio examples below correspond to recordings of soundscapes simulating
cafe or office environments using 5 loudspeakers playing back different noise
sources, including interfering voices, with an additional loudspeaker located at
1 meter in front of the user to simulate the target voices, as shown in the figure below.

<div class="row" style="width: 60%; margin-left: auto; margin-right: auto;">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/front_speech_enhancement.png" title="Recording setup" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Setup corresponding to the audio examples below
</div>

Use headphones to listen to the sound examples.[^1] In these examples, the target
speaker's identity is continuously changing to show how the system behaves with different
voices. Click on the "Toggle enhancer" button at any time to switch between
the original recording and the denoised one.[^2]

<iframe width="100%" height="350" src="https://perceptual-objects.github.io/rt_speech_enhancement/assets/vx-f4-b-01_demo/" frameborder="0"></iframe>

##### Denoising system features

- Microphone array:  4-microphones, 2 around each ear
- Complexity: ~36.5 MFLOPS (and improving...)
- Latency: ~20ms

This is just the beginning... Visit back soon for more impressive demos!

###### Notes

[^1]: <span style="font-size:0.8em">The material presented on this page is licenced under [CC BY-NC-ND 4.0](https://creativecommons.org/licenses/by-nc-nd/4.0/).</span>
[^2]: <span style="font-size:0.8em">Player based on a modified version of [binarymind/multitrackHTMLPlayer](https://github.com/binarymind/multitrackHTMLPlayer).</span>
