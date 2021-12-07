---
title: "title inside quotation marks" #title - As you can see I have put advice for each section below in the preamble (what is called the YAML) after a #, feel free to leave these bits in
author: yournameinlowercase #your author name is your first and last name together in lower case with no spaces
header:
  overlay_image: {{ site.baseurl }}/assets/images/name of banner photo.jpeg/.png #put the name of your header photo here with the file type extension - e.g. .JPEG or .jpg. This is case sensitive, only change the bit after "images/", not before.
  caption: "caption for banner / header in quotation marks"
  actions:
    - label: "Read Below" #ignore this
      url: "URL to first heading" #ignore this
  teaser: {{ site.baseurl }}/assets/images/name of teaser photo.jpeg / .png #usually the same as the header
excerpt: > #the sneak preview of your blog piece that is shown on twitter shares and previews (1 sentence)
  This is the sneak preview that will be one sentence and describe the post
categories:
  - Public_History #leave this
tags: #give your post three tags (no spaces)
  - NSW
  - ACT
  - PHA
classes: wide # leave this
---
_small summary of topic to catch readers attention (mini abstract) goes here inside these underscores_

# Heading 1 looks like this

Text looks like this (normal)

- Dot points;
- look like;
- this (hyphens)

URL links look like this <www.google.com> (with angle brackets on either side)

## Subheading 1 looks like this

**Bold looks like this (two asterisks)**

## Subheading 2 looks like this

_Italics looks like this (two underscores)_

### Sub-subheading 1 looks like this

Images look like this:
<figure>
  <img src="{{ site.baseurl }}/assets/images/Yourimagename.jpg/png" alt="your alt text">
  <figcaption>The caption for your photo the includes the license for the image</figcaption>
</figure>

# Bibliograhy

Your bibliography goes here:
- Bob, S. (2021) _The Big Book_, Big Book Publishers: Sydney.
- Rob, D. (2021) _The Bigger Book_, Bigger Book Publishers: Melbourne.
