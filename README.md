# static-site-template
## Using Jekyll

> Jekyll is a static site generator. It takes text written in your favorite markup language and uses layouts to create a static website. You can tweak the site’s look and feel, URLs, the data displayed on the page, and more.

https://jekyllrb.com/

## Recommended Docker:

This run command will launch the jekyll dev server with livereload
```shell
docker run --rm --volume="./:/srv/jekyll:Z" -p 4000:4000 -it jekyll/jekyll:3.8 jekyll serve --livereload
```
visit the site at [localhost:4000](http://localhost:4000/)
## Installing Ruby
Jekyll is built using Ruby.

### Mac

Use rbenv [install with brew](https://github.com/rbenv/rbenv?tab=readme-ov-file#homebrew)

### Windows

[Use the windows installer](https://www.ruby-lang.org/en/documentation/installation/#rubyinstaller)
