---
layout: page
---

## About Me

Hi! I'm a statistician interested in the application of Bayesian methods in
scientific problems. I completed my PhD in Statistics at UC Santa Cruz under
Dr. Juhee Lee in 2021.  Prior to UCSC, I completed my BS/MS in Statistics at
Brigham Young University under Dr. David Dahl in 2015.

I play jazz and classical piano music in my spare time.

<hr>


### Posts
{% for post in site.posts %}
<div class="post-preview">
    <a href="{{ post.url | prepend: site.baseurl }}">
        &raquo; {{ post.title }}
        {% if post.subtitle %}
        &mdash;
        {{ post.subtitle }}
        {% endif %}
    </a>
    <p class="post-meta" style="font-size: 16px">
       Posted on {{ post.date | date: "%-d %b, %Y" }}
    </p>
</div>
{% endfor %}


[1]: https://help.github.com/articles/creating-project-pages-manually
