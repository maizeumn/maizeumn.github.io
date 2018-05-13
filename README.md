# Springer Lab research

## 
This website was built using the [bedford.io website](http://bedford.io) as a template, which is open-source and available on [Github](https://github.com/blab/blotter).

## Technologies this website uses:
* Jekyll  
* Github Pages
* Bootstrap 4.1
* Font Awesome 5.0.13


## Build site

To build the website locally, clone the repo with:

```
git clone https://github.com/maizeumn/maizeumn.github.io.git
```

Then install necessary Ruby dependencies by running `bundle install` from within the `maizeumn.github.io` directory.  After this, the site can be be built with:

```
bundle exec jekyll build
```

To view the site, run `bundle exec jekyll serve` and point a browser to `http://127.0.0.1:4000/`.  More information on Jekyll can be found [here](http://jekyllrb.com/).

## Contribute

News posts just require YAML top matter that looks something like:

```
---
layout: post
title: New website running
author: Peng Zhou
link: http://maizeumn.github.io
image: /images/news/new_website.png
---
```

The `layout`, `title` and `author` tags are required, while `link` and `image` are optional.  Just save a Markdown file with this top matter as something like `news/_posts/2018-05-13-new-website.md`, where `2018-05-13` is the date of the post and `new-website` is the short title.  This short title is used in the URL of the post, so this becomes `news/new-website/`, so the short title should be long enough and unique enough not to cause conflicts with other posts.

## For more information

* Look over the [metadata format guide](http://maizeumn.github.io/guide/format/)
* Look over the [Markdown style guide](http://maizeumn.github.io/guide/style/)

## License

All source code in this repository, consisting of files with extensions `.html`, `.css`, `.less`, `.rb` or `.js`, is freely available under an MIT license, unless otherwise noted within a file. You're welcome to borrow / repurpose code to build your own site, but We would very much appreciate attribution and a link back to [Springer Lab research](http://maizeumn.github.io) from your `about` page.

