---
layout: blog
title: Background
permalink: /posts
---
<!-- Write the Post page here -->
<div class="main">
<div class="post-wrap archive">
    <!-- Write the table markdown here -->

| University/School Name                     | Degree                                                        | Year                                                        |
| -------------------------------------- | ------------------------------------------------------------ | ------------------------------------------------------------ |
| Brainware University                      | Bachelor of Computer Applications                                  | 2017-2020 |
| Bholananda National Vidyalaya   | XII (CBSE)                  | 2015-2017 |
| Modern English Academy | X (ICSE)                                              | 2011-2015 |
| Douglas Memorial Higher Secondary School               | Elementary School | 2005-2011 |
    {% for post in site.posts %}
    <article class="archive-item"><a class="archive-item-link" href="{{ post.url }}">{{ post.title }}</a>

    
</article>
    {% endfor %}
</div>
</div>





 