---
layout: default
title: Code Snippets
thumbnail: post-9.png
---

Whenever you need to post a code snippet, use the liquid tags `hilight` and `endhilight` like this:

{% highlight ruby %}
# some code goes here
puts "Hello World!"
{% endhighlight %}

Note that this only provides color-coding. For that you might need to use a front end colorization engine like Highlight.JS or something similar.
