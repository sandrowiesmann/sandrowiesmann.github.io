---
permalink: /
title: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

{% include base_path %}

I am a cognitive psychologist and vision scientist at Goethe University, Frankfurt. I obtained my PhD in psychology under the supervision of [Melissa Võ](https://www.mcn.uni-muenchen.de/members/regular/vo/index.html) in the [Scene Grammar Lab](https://www.scenegrammarlab.com/). As a postdoc at Goethe University Frankfurt, I represent the research unit for Allgemeine Psychologie I (i.e., cognitive psychology).  
  
My [research](/research) focusses on our remarkable ability to perceive and make sense of our environment within fractions of a second. I use psychophysics, eye tracking, and modelling to better understand which types of information and cognitive processes enable this feat. Besides visual perception, I am generally interested in the many ways our cognitive system "can be wrong", including phenomena such as illusions, memory distortions, and cognitive biases.  
  
I am passionate about [teaching](/teaching) and sharing my enthusiasm for cognitive psychology with students at different levels. I value the exchange with undergraduate and graduate students I supervise and collaborate with.  
  
As an employee of a state-funded university, I am committed to democratic principles, and I am active in several academic committees. In my work, I strive for open, transparent, and reproducible research in the spirit of open science.  


{% assign latest_post = site.posts.first %}

{% if latest_post %}
## Latest News

**[{{ latest_post.title }}]({{ latest_post.url | relative_url }})**

<small>{{ latest_post.date | date: "%B %d, %Y" }}</small>

{{ latest_post.excerpt | markdownify }}

[Read more →]({{ latest_post.url | relative_url }})

[See all news →]({{ '/news/' | relative_url }})
{% endif %}
