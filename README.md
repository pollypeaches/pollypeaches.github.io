# This is the personal website of wezling wieselberger

# How to use (simple):
## New Blog Post
* go to the `./_posts` folder, and copy one of the existing posts
* your new file name should be the date followed by some text: `2020-01-25-description.md`
* the contents should look like this:
* > ---
title: Boris is Dead!
subtitle: Dead Pony
number: 1
img: https://asdfasdf -- see below for how to get a photo url from google photos
description: Boris died. He was a goode horss.
---
* thats it!

## New Photo
Choose your photo! 
* go to google photos bucket, pick a nice pic
* click 'share'
* click 'create link'
* click 'create link' again and copy it
* paste the link into this website: `https://www.labnol.org/embed/google/photos/`
* then get the new link, and use it to create a new blog post

# How to use (advanced):

* posts are in `./_posts`. They must have the form 'NNNN-NN-NN-XXXX.markdown'
* post grid layout is in `./_includes/portfolio_grid.html`
* post layout is in `./_includes/modals.html`
* website structure is in `./_layouts`
