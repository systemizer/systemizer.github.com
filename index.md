---
layout: page
title: systemizer
tagline: Explore. Discover. Reinvent. Post.
---
{% include JB/setup %}

<div class="row">
<div class="span7">
  <h3>Recent Posts</h3>
  <hr />
  <ul class="nostyle align-right">	
    {% for post in site.posts %}
      <li>
	  <h2><a href="{{ post.url }}">{{ post.title }}</a>
	  <br>
	  <small>{{ post.date | date_to_string }}</small>
	  </h2>	  
	  {{ post.content | strip_html | truncatewords:75 }}
      </li>	
    {% endfor %}
  </ul>
</div>
<div class="span4 sidenav">
     <h3 class="align-left">Other Relevant Links</h3>
     <ul class="nostyle align-left">
       <li><a href="http://systemizer.me">Personal Website</a></li>
       <li><a href="http://soundcloud.com/systemizer">My Music</a></li>
       <li><a href="http://github.com/systemizer">My Code</a></li>
     </ul>
     <h3 class="align-right">About Me</h3>
     <ul class="nostyle align-right">
     	 <li>Developer @ MoPub</li>
	 <li>Marathon Runner</li>
	 <li>Bread Baker</li>
	 <li>EDM Fan</li>
	 <li>MIT '12</li>
     </ul>
     <h3 class="align-left">Contact Me</h3>
     <ul class="nostyle">
       <li><p>I love giving advice and helping others complete their own side projects.</p></li>
       <li><p>Send me a message at <a href="mailto:rob@systemizer.me">rob@systemizer.me</a> or tweet <a href="https://twitter.com/systemizer">@systemizer</a></p></li>
     </ul>
</div>
</div>
