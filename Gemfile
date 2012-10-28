source 'http://rubygems.org'

gem 'rails', '3.1.0'

# Bundle edge Rails instead:
# gem 'rails',     :git => 'git://github.com/rails/rails.git'

# for Heroku deployment - as described in Ap. A of ELLS book
group :development, :test do
  gem 'sqlite3'
  gem 'ruby-debug19', :require => 'ruby-debug'
end
group :production do
  gem 'pg'
  #gem 'mysql2'
  #gem 'sqlite3'
end

# Gems used only for assets and not required
# in production environments by default.
group :assets do
  gem 'therubyracer'              
  gem 'sass-rails', "  ~> 3.1.0"
  gem 'coffee-rails', "~> 3.1.0"
  gem 'uglifier'
end

gem 'jquery-rails'

# Use unicorn as the web server
# gem 'unicorn'

# Deploy with Capistrano
# gem 'capistrano'

# To use debugger
gem 'haml'

group :development, :test do
	# Solution from http://stackoverflow.com/questions/9642489/rvm-ruby-1-9-3-rails-3-1-3-cant-start-rails-server-due-to-ruby-debug
	gem 'linecache19', :git => 'git://github.com/mark-moseley/linecache'
	gem 'ruby-debug-base19x', '~> 0.11.30.pre4'
	gem 'ruby-debug19'
end