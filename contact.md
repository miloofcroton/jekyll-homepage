---
title: contact
layout: secondary
---

<form action="https://formspree.io/{{ site.email }}" method="POST">
	<div class="field half first">
		<label for="name">Name</label>
		<input type="text" name="name" id="name" />
	</div>
	<div class="field half">
		<label for="email">Email</label>
		<input type="text" name="_replyto" id="email" />
	</div>
	<div class="field">
		<label for="message">Message</label>
		<textarea name="message" id="message" rows="4"></textarea>
	</div>
	<ul class="actions">
		<li><input type="submit" value="Send Message" class="special" /></li>
		<li><input type="reset" value="Reset" /></li>
	</ul>
</form>

<ul class="icons">
	<li><a href="mailto:{{ site.email }}" class="icon fa-envelope" target="_blank"><span class="label">Email</span></a></li>
	<li><a href="{{ site.github_url }}" class="icon fa-github" target="_blank"><span class="label">GitHub</span></a></li>
	<li><a href="{{ site.pgp_key }}" class="icon fa-key" target="_blank"><span class="label">Public Key</span></a></li>
</ul>
