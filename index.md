---
layout: page

---
{% include JB/setup %}


I'm **Keshav Rao**, a High School **Developer** and **Entrepreneur**.  

I enjoy _writing_, playing sports, thinking of new ideas, and building things.  

Currently working on [PeerEditr](www.peereditr.com). 

Check out my [projects](projects.html) and [blog](archive.html)!




<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>




