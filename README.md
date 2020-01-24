# ICF portal website sources

## develop
setup
reference: https://help.github.com/en/articles/setting-up-your-github-pages-site-locally-with-jekyll

- Install ruby 2.1.0 or higher and bundler
```
$ ruby --version
> ruby 2.X.X
$ gem install bundler
```

- Clone repository and build them by jekyll
```
$ git clone https://github.com/icf-shamrock/icf-shamrock.github.io.git
$ cd icf-shamrock.github.io
$ bundle install --path vendor/bundle
$ bundle exec jekyll serve
```

- Check if you can see the website on `http://127.0.0.1:4000/`
