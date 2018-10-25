source 'http://rubygems.org'
ruby '2.4.5'

gem 'rails', '~> 5.1.6'

# Gems used only for assets and not required
# in production environments by default.
group :assets do
  gem 'mini_racer'
  gem 'sass-rails', '>= 3.2'
  gem 'uglifier', '>= 1.0.3'

  # Upload assets to AWS S3
  gem 'asset_sync'
  gem 'fog-aws'
end

gem 'bootstrap-sass', '~> 3.3.6'
gem 'bootstrap-social-rails'
gem 'bootstrap_form'
gem 'jquery-rails'

gem 'http_accept_language'

# Mongo
gem 'mongoid', '~> 6.4.2'

# Omniauth
gem 'omniauth'
gem 'omniauth-github'
gem 'omniauth-twitter'

# Puma
gem 'puma'

# New Relic
gem 'newrelic_rpm'

# Memcached
gem 'dalli'
gem 'memcachier'

# Pagination
gem 'kaminari', '~> 1.0'
gem 'kaminari-mongoid', '~> 1.0'

# Notify exceptions
gem 'exception_notification'

# Static pages
gem 'high_voltage'
gem 'rdiscount'

# Async tasks
gem 'sucker_punch', '~> 2.0'

gem 'octokit'
gem 'twitter'

gem 'bootsnap', require: false

# Asset pipeline
gem 'sprockets', '>= 3.7.2'

group :production do
  gem 'rails_12factor'
end

group :test do
  gem 'coveralls', require: false
  gem 'minitest-reporters'
  gem 'mocha', require: false
  gem 'simplecov', require: false
end

group :development do
  gem 'better_errors'
  gem 'binding_of_caller'
end

group :development, :test do
  gem 'byebug'
  gem 'pry'
  gem 'rubocop', '~> 0.51', require: false
  gem 'test-unit', '~> 3.0'
end
