---
layout: base
---

### You have found an otter!

# I'm {{ site.author.name }} 🦦

Well..._technically speaking_ I'm not **exactly** an otter...

But no matter! This is the start of my tiny corner of the internet. I have had primotter.space (joke intended) for quite a while now.
However I haven't done anything other than use it as a glorified redirect to my bsky.

---

Today is the day that it changes! And it's all thanks to Astra!

[Go see Astra's corner of the internet.](https://astrabun.com)

> No seriously, thank you Astra, this start up template is exactly what I needed to push myself to learn eleventy and to create a blog.

## Recent posts

{% assign recent = collections.posts | newestFirst | limit: 5 %}
{% include "post-list.liquid", posts: recent %}

[All posts &rarr;](/posts/)
