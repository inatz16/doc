continuousphp documentation
===========================

This is the official documentation of the continuousphp platform.

## How to install?

1. Install Ruby 2.0.0
2. Install Bundler ``` gem install bundler ```
3. Install dependencies ``` bundle install ```
4. Run Jekyll ``` jekyll serve ```

### Using docker

```bash
docker run -i -t -v $PWD:/srv/jekyll -p 4000:4000 jekyll/jekyll:pages jekyll serve --watch
```

## Comments

In order to have a better experience, the stylesheets from the webapp is loaded.
However, as the javascript is not loaded, all features are not available (i.e. menu styles are not available).
Thank you for your comprehension.

## API documentation

The API is documented using [API Blueprint](https://apiblueprint.org/) description language.
If you want to contribute, just edit the [description file](apiary.apib)
and propose a Pull Request.