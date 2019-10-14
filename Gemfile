source 'https://rubygems.org'

gem 'rails', '3.2.17'

# Bundle edge Rails instead:
# gem 'rails', :git => 'git://github.com/rails/rails.git'

#group :development, :test do
gem 'sqlite3'
#end
#START:mysql
group :production do
#	gem 'activerecord-mysql-adapter'
#	gem 'mysql'
  gem 'mysql2'
end
#END:mysql


# Gems used only for assets and not required
# in production environments by default.
group :assets do
  gem 'sass-rails',    '~> 3.2.3'
  gem 'coffee-rails',  '~> 3.2.1'

  # See https://github.com/sstephenson/execjs#readme for more supported runtimes
  # gem 'therubyracer'

  gem 'uglifier', '>= 1.0.3'
end

gem 'jquery-rails'

# To use ActiveModel has_secure_password
gem 'bcrypt-ruby', '~> 3.0.0'

# To use Jbuilder templates for JSON
# gem 'jbuilder'

# Use unicorn as the web server
# gem 'unicorn'

# Deploy with Capistrano
#START_HIGHLIGHT
gem 'capistrano'
#END_HIGHLIGHT

# Pretty printsd test output
group :test do
	gem 'turn', :require => false
end

# To use debugger
# gem 'ruby-debug19', :require => 'ruby-debug'

gem 'will_paginate', '~> 3.0'
