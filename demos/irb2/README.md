This project runs a mruby interpreter in a browser. It depends on [webruby](https://github.com/xxuejie/webruby).

## [Live Demo](http://joshnuss.github.io/mruby-web-irb)

# Building webruby.js

1. Build [webruby](https://github.com/xxuejie/webruby) using any gem configuration. But remember to use loading mode 2.

	**NOTE**: If you do not know what is loading mode, feel free to ignore this since loading mode 2 is the default. However, a detailed description on loading mode is at [here](https://github.com/xxuejie/webruby/blob/master/rakelib/functions.rb#L3).

2. Copy the generated `webruby.js` file to current folder(and override existing file).

3. Now you are good to go!

# Generating the stylesheets

First, you'll need compass:

  > bundle install

Then you can monitor the stylesheets for changes with:

  > compass watch
