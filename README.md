# [Philip's Blog](http://pcjordan.github.io)

A personal blog built on [Jekyll](https://jekyllrb.com/) using a [clone](https://github.com/easiestpage/jekyll-twentynineteen) of [Wordpress's Twenty Nineteen](https://wordpress.org/themes/twentynineteen/) theme.

## Local Installation

First, install Jekyll by

```bash
$ gem install bundler jekyll
```

then, build the project via

```bash
$ bundle exec jekyll serve
```

and the website should be accessible under http://localhost:4000.

## Hosting via GitHub Pages

In order to publish this blog via GitHub Pages, just rename this repository to `your_username.github.io` and push it onto your GitHub.

## As soon as posts are available

Add the following to `index.html`:

```ruby
{% for post in site.posts %}
    {% include post.html %}
{% endfor %}
```
