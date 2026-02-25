# Welcome

A blog about stuff!

---

Hi! My name is Xander Crawford. I am a 20-something-year-old living in Philadelphia, Pennsylvania. As I leave my early 20-somethings and move forward to my late 20-somethings, I find myself looking to ramble.

As a person who was adamantly anti-social media throughout my teen years and a "lurker" in my early 20's, the want to publish my interests and thoughts online is an unexpected change of heart.

Anyway - welcome to the things I think are worth talking about!

---

Feel free to contact me if you find anything of interest at [jxandercrawford@gmail.com](mailto:jxandercrawford@gmail.com).

---

<div class="home">
  <h1>Latest Posts</h1>
  {% for post in site.posts %}
    <article class="post-card">
      <h2><a href="{{ post.url | relative_url }}">{{ post.title }}</a></h2>
      <p class="post-meta">
        Posted on {{ post.date | date: "%B %-d, %Y" }}
      </p>
      <div class="post-excerpt">
        {{ post.excerpt }}
      </div>
      <a href="{{ post.url | relative_url }}" class="read-more">Read more →</a>
    </article>
  {% endfor %}
</div>