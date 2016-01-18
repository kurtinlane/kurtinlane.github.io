---
layout:     post
title:      "First time using Jekyll"
date:       2016-01-18 11:37:00
author:     "Colton Shields"
header-img: "img/post-bg-02.jpg"
---

<p>Today I set up my blog and started using Jekyll and Github pages to do so. First I want to say how much I love not using wordpress or its terrible wizzywig editors. Which brings me to my second reason why I'm excited to use Jekyll I love writing my posts in markdown. </p>


I have had a personal website coltonshields.com for a couple of years and have done several things with it. Wordpress blog, a personal resume, a collection of projects I worked on. And now I'm back to a blog!

<a href="#">
    <img src="{{ site.baseurl }}/img/what-i-hate-about-wordpress.jpg" alt="Wordpress sucks">
</a>
<span class="caption text-muted">Seriously though it was a good start but it's time to move on.</span>

I broke away from wordpress (best decision this year) and looked at some other options and decided to use Jekyll. I chose Jekyll cuz you can write your posts in markdown and it plays nicely with Github, meaning I have a backup of everything, and I get to use Github :)

Setting it up was super easy. I found a template I liked, clone the repo, made a few changes so it would work on my local machine. I then created a repo in github called USERNAME.github.io. I pushed my blog to that repo and batta bing it was live at USERNAME.github.io. I then added a CNAME file that pointed to blog.coltonshields.com and configured my coltonshields.com domain to go to Github anytime blog.coltonshields.com was hit. So now blog.coltonshields.com shows my blog!!!

The best part of this is I make changes on my laptop and then git push them to my repository and bam! the changes show up on blog.coltonshields.com. Super easy, super quick and I have working copy (laptop) and production copy (Master branch on Github). I could also use branches to release new posts, but no one reads my blog so I am not concerned about spelling errors or pushing directly to master branch because the world will not stop spinning if my blog goes down for a few minutes.


Anywho, anyone who is going to start a personal blog and wants to set it up yourself I highly suggest using Github pages and Jekyll. It's free and easy to set up. 
