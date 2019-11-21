---
layout: default
title: Home
---

# This is my web page.

There's not much here right now, but maybe there will be soon.  
_Who knows_...

Cheers,  

Daan    

_Would you like to send me a message?_
[Tweet](https://twitter.com/daandenhoed/) or [Email](mailto:daandenhoed@gmail.com?subject=daanwebmail:) me!

{% include whitespace.html %}

{% include lasttweet.html %}

{% if site.blog-active == true %}
  {% include whitespace.html %}

  {% include postindex.html %}
{% endif %}
