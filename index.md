---
layout: default
title: Mr. Allatta's Learning Blog
---

<div class="blurb">
<h1>Welcome to Mr. Allatta's Learning Blog!</h1>
<p>This will be my home base for sharing learning reflections with my students through out the year. </p>

<p>In the 2018-2019 school year my students are 9th and 10th graders at the Academy for Software Engineering. They are the "Lower Academy" of a comprehensive public high school in NYC, which is also the first comprehensive high school in the city with a core computer science sequence. The two year lower academy sequence is required of all students and culminates in the AP Computer Science Principles exam.</p>

<p>I teach 9th and 10th grade computer science at the Academy for Software Engineering. <a href="/about">Read more about my life...</a></p>

</div><!-- /.blurb -->

<h1>Learning Reflections</h1>

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>
