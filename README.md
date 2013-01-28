Heroku buildpack: Ruby with PhatomJS
======================


heroku config:add PATH="bin:vendor/bundle/ruby/1.9.1/bin:/usr/local/bin:/usr/bin:/bin:/app/vendor/phantomjs/bin"
heroku config:add LD_LIBRARY_PATH="/usr/local/lib:/usr/lib:/lib:/app/vendor/phantomjs/lib"