# Sample Blog Site with PyJan26

A simple example blog site built using PyJan26

## Setup

1. Install requirements
```python
pip install pyjan26 pyjan26-repeat pyjan26-sitemap pyjan26-scss
```

2. Build
```python
python -m pyjan26.main g
```

3. Serve the site locally
```python
python -m http.server 8080 --directory public/
```

## Adding a New Blog Post

1. Create a new Markdown file in "_content/posts/" (ex. my-new-post.md).

2. Add frontmatter to the file.
```yaml
---
title: "My new blog post"
date: "2024-12-01"
tags: ["example"]
layout: base.html
---
your post content goes here.

3. Rebuild the site
```python
python -m pyjan26.main g
```



