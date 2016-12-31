---
layout: default
---

<!-- Section -->
<section>
	<header class="major">
		<h2>Latest Post</h2>
	</header>
	<!-- <div class="features">
		<article>
			<span class="icon fa-diamond"></span>
			<div class="content">
				<h3>Portitor ullamcorper</h3>
				<p>Aenean ornare velit lacus, ac varius enim lorem ullamcorper dolore. Proin aliquam facilisis ante interdum. Sed nulla amet lorem feugiat tempus aliquam.</p>
			</div>
		</article>
		<article>
			<span class="icon fa-paper-plane"></span>
			<div class="content">
				<h3>Sapien veroeros</h3>
				<p>Aenean ornare velit lacus, ac varius enim lorem ullamcorper dolore. Proin aliquam facilisis ante interdum. Sed nulla amet lorem feugiat tempus aliquam.</p>
			</div>
		</article>
		<article>
			<span class="icon fa-rocket"></span>
			<div class="content">
				<h3>Quam lorem ipsum</h3>
				<p>Aenean ornare velit lacus, ac varius enim lorem ullamcorper dolore. Proin aliquam facilisis ante interdum. Sed nulla amet lorem feugiat tempus aliquam.</p>
			</div>
		</article>
		<article>
			<span class="icon fa-signal"></span>
			<div class="content">
				<h3>Sed magna finibus</h3>
				<p>Aenean ornare velit lacus, ac varius enim lorem ullamcorper dolore. Proin aliquam facilisis ante interdum. Sed nulla amet lorem feugiat tempus aliquam.</p>
			</div>
		</article>
	</div> -->
	{% for post in site.posts limit:1 %}
		<article>
			<a href="#" class="image"><img src="assets/images/pic01.jpg" alt="" /></a>
				<h3>{{ post.title }}</h3>
				<p>{{ post.excerpt }}</p>
				<ul class="actions">
					<li><a href="{{ post.url }}" class="button">More</a></li>
				</ul>
		</article>
	{% endfor %}
</section>

<!-- Section -->
<section>
	<header class="major">
		<h2>Recent Posts</h2>
	</header>
	<div class="posts">

    {% for post in site.posts offset:1 limit:4 %}
	    <article>
	    	<a href="#" class="image"><img src="assets/images/pic01.jpg" alt="" /></a>
	    	<h3>{{ post.title }}</h3>
	    	<p>{{ post.excerpt }}</p>
	    	<ul class="actions">
	    		<li><a href="{{ post.url }}" class="button">More</a></li>
	    	</ul>
	    </article>
		{% endfor %}

    	<!-- <article>
    		<a href="#" class="image"><img src="assets/images/pic01.jpg" alt="" /></a>
    		<h3>Interdum aenean</h3>
    		<p>Aenean ornare velit lacus, ac varius enim lorem ullamcorper dolore. Proin aliquam facilisis ante interdum. Sed nulla amet lorem feugiat tempus aliquam.</p>
    		<ul class="actions">
    			<li><a href="#" class="button">More</a></li>
    		</ul>
    	</article>
    	<article>
    		<a href="#" class="image"><img src="assets/images/pic02.jpg" alt="" /></a>
    		<h3>Nulla amet dolore</h3>
    		<p>Aenean ornare velit lacus, ac varius enim lorem ullamcorper dolore. Proin aliquam facilisis ante interdum. Sed nulla amet lorem feugiat tempus aliquam.</p>
    		<ul class="actions">
    			<li><a href="#" class="button">More</a></li>
    		</ul>
    	</article>
    	<article>
    		<a href="#" class="image"><img src="assets/images/pic03.jpg" alt="" /></a>
    		<h3>Tempus ullamcorper</h3>
    		<p>Aenean ornare velit lacus, ac varius enim lorem ullamcorper dolore. Proin aliquam facilisis ante interdum. Sed nulla amet lorem feugiat tempus aliquam.</p>
    		<ul class="actions">
    			<li><a href="#" class="button">More</a></li>
    		</ul>
    	</article>
    	<article>
    		<a href="#" class="image"><img src="assets/images/pic04.jpg" alt="" /></a>
    		<h3>Sed etiam facilis</h3>
    		<p>Aenean ornare velit lacus, ac varius enim lorem ullamcorper dolore. Proin aliquam facilisis ante interdum. Sed nulla amet lorem feugiat tempus aliquam.</p>
    		<ul class="actions">
    			<li><a href="#" class="button">More</a></li>
    		</ul>
    	</article>
    	<article>
    		<a href="#" class="image"><img src="assets/images/pic05.jpg" alt="" /></a>
    		<h3>Feugiat lorem aenean</h3>
    		<p>Aenean ornare velit lacus, ac varius enim lorem ullamcorper dolore. Proin aliquam facilisis ante interdum. Sed nulla amet lorem feugiat tempus aliquam.</p>
    		<ul class="actions">
    			<li><a href="#" class="button">More</a></li>
    		</ul>
    	</article>
    	<article>
    		<a href="#" class="image"><img src="assets/images/pic06.jpg" alt="" /></a>
    		<h3>Amet varius aliquam</h3>
    		<p>Aenean ornare velit lacus, ac varius enim lorem ullamcorper dolore. Proin aliquam facilisis ante interdum. Sed nulla amet lorem feugiat tempus aliquam.</p>
    		<ul class="actions">
    			<li><a href="#" class="button">More</a></li>
    		</ul>
    	</article> -->
    </div>

</section>
