---
layout: post
title:  "Dance Montage"
subtitle: ""
date:   2019-04-03 12:00:00
preview: west-side-story-mapped-cropped.gif
---

![West Side Story mapped with openpose](west-side-story-mapped.gif)

## Proposed Process

### Recipe

1. Create archive of film.
2. Run a pose detection algorithm on all of it, outputing joint data of the detected poses. (Dataset A)
3. Film some fresh choreography. 
4. Run the pose detection algorithm on this. Again, outputting joint data. (Dataset B)
5. Run an algorithm that, for each frame, of B finds the pose from the archive (A), that is most similar.
6. Place the most similar frames in order and export as a film.

### Things we need

Pose detection algorithm. Can use openpose - **tick**.

Fresh choreography. I can put on some trousers and then I'll be right with you - **tick**.

Algorithm that can find the most similar pose . Need some time to develop an optimal one of these, but won't be too hard.

## Mood board

Mario Klingemann is doing cool things GANs.

<blockquote class="twitter-tweet" data-conversation="none" data-lang="en"><p lang="en" dir="ltr">Here&#39;s a comparison of the two models. Observation: very few people have their mouth open in classical portraits. <a href="https://t.co/SPuUFUnW88">pic.twitter.com/SPuUFUnW88</a></p>&mdash; Mario Klingemann (@quasimondo) <a href="https://twitter.com/quasimondo/status/826558103768461317?ref_src=twsrc%5Etfw">January 31, 2017</a></blockquote>
<script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script>

Something like this, but with frames from dance videos instead of drawings at each point. And 24 frames per second instead of this slow.
<iframe src="https://player.vimeo.com/video/272053388?color=ff9933&byline=0" width="640" height="320" frameborder="0" allow="autoplay; fullscreen" allowfullscreen></iframe>
<p><a href="https://vimeo.com/272053388">349</a> from <a href="https://vimeo.com/k10rls">Kristen Lauth Shaeffer</a> on <a href="https://vimeo.com">Vimeo</a>.</p>

I suspect it may look a bit like 'Loving Vincent' in which every frame is an oil painting. There is something disjointed about the animation but there is enough for a coherent and moving pattern to emerge.
<iframe width="560" height="315" src="https://www.youtube.com/embed/47h6pQ6StCk" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>