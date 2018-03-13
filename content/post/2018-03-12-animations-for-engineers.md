---
date: 2018-03-12T07:20:36Z
tags: 
    - animations 
title: Animations for Engineers
---

I've been doing web development for a long time, and am very
well versed in creating modern JS UI.  However, these UIs have
mostly been for business applications and generally not for
aestetic purposes.  For a long time I've wanted to learn how to
do proper web animations, and now that I'm giving my blog another
go, I've decided to make this my first new post.

Being a software engineer, it makes sense to me that I would use
a system based around coding rather than some WYSIWYG style
editor.  While I am completely bankrupt of any artistic skills
whatsoever, I do know enough about image editing software to
make something simple.  Simple is good.  Simple is easy.  Simple
is harder to mess up.

I've decided I'm going to make a simple into screen to my blog,
with my name, and maybe a one-liner TBD. I figure I'll make this as a
simple image, then I want to have it broken into triangles and have them
fly into the screen, materializing my intro page in monochrome,
then I will have a gradient wave come
through and colorize it with the color scheme of my blog.  This
probably made no sense to you, dear reader, and I wish I could make
an animation describing it to you, but I fear we've encountered
a chicken-egg type scenario if you know what I mean.

Nevertheless, we struggle forth...

It seems my options are:

- CSS - nuff said
- WebGL - Most performant, most powerful, but geared towards 3d.
    Doesn't integrate with DOM as easily as other solutions.
- SVG - Portable, integrates with DOM, great for 2D animations.

I know CSS enough, so that's not exciting for me. Part of me *really*
wanted to choose WebGL for this, but SVG seems to be a much
better choice, so the engineer in me won't let me do it.
Maybe I'll do another post using WebGL in the future.
