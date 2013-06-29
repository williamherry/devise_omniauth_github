#source 'http://ruby.taobao.org/'
source 'https://rubygems.org'

gem 'rails', '3.2.13'

# Bundle edge Rails instead:
# gem 'rails', :git => 'git://github.com/rails/rails.git'

gem "slim-rails"
gem 'omniauth-github'
gem 'devise'
gem 'pg', group: [:production]


# Gems used only for assets and not required
# in production environments by default.
group :assets do
  gem 'sass-rails',   '~> 3.2.3'
  gem 'coffee-rails', '~> 3.2.1'

  # See https://github.com/sstephenson/execjs#readme for more supported runtimes
  # gem 'therubyracer', :platforms => :ruby

  gem 'uglifier', '>= 1.0.3'
end

gem 'jquery-rails'

group :development, :test do
  gem 'sqlite3'
  gem 'rspec-rails'
  gem 'jasmine'
  gem 'factory_girl_rails'
  gem 'annotate', :git => 'git://github.com/ctran/annotate_models.git'
end

group :development do
  gem 'awesome_print'
  gem 'thin'
  gem 'pry-debugger'
  gem 'quiet_assets'
  gem 'better_errors'
  gem 'binding_of_caller'
  gem 'meta_request'
  gem 'capistrano'
end

# To use ActiveModel has_secure_password
gem 'bcrypt-ruby', '~> 3.0.0'

# To use Jbuilder templates for JSON
# gem 'jbuilder'

# Use unicorn as the app server
 gem 'unicorn'

# Deploy with Capistrano
# gem 'capistrano'

# To use debugger
# gem 'debugger'
