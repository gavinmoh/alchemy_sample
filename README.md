# How to setup alchemy
* rails new alchemy-sample
* cd alchemy-sample
* bundle add devise
* Add alchemy_cms to Gemfile and run bundle update
* rails g devise:install
* rails g devise User
* rake alchemy:install
* in routes.rb, make sure you mount alchemy engine last
