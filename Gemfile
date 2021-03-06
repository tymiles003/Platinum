source 'https://rubygems.org'

gem 'rails', '3.2.17'

# Backend
# gem 'airbrake'
# gem 'newrelic_rpm'
gem 'figaro', '~> 1.0.0.rc1'
gem 'json'
gem 'multi_json'
gem 'mongoid'
gem 'declarative_authorization'
gem 'mongoid-paperclip', require: 'mongoid_paperclip'
gem 'foreman'
gem 'strong_parameters'
gem 'newrelic_rpm'
gem 'ruby_parser'
gem 'smarter_csv'
gem 'actionmailer'
gem 'bcrypt-ruby', '~> 3.0.0'
gem 'dalli'
gem 'premailer-rails'
gem 'nokogiri'
gem 'braintree'

# Job Processing
gem 'sidekiq'
gem 'kiqstand', '~> 1.1.0'
gem 'sinatra', require: false
gem 'slim'

# Frontend
gem 'active_link_to'
gem 'bootstrap-sass'
gem 'bootstrap-will_paginate'
gem 'bootstrap_form'
gem 'haml'
gem 'jquery-rails'
gem 'will_paginate'
gem "font-awesome-rails", '~> 3.2.1.0'


# Gems used only for assets and not required
# in production environments by default.
group :assets do
  gem 'sass-rails',   '~> 3.2.3'
  gem 'coffee-rails', '~> 3.2.1'
  gem 'uglifier', '>= 1.0.3'
  gem 'therubyracer'
end

group :development, :test do
  gem 'faker'
  gem 'guard-rspec'
  gem 'guard-spork'
  gem 'rspec-rails'
  gem 'mailcatcher'
  gem 'better_errors'
  gem "binding_of_caller"
end

group :development do
  gem 'annotate'
  gem 'haml-rails'
  gem 'rb-inotify', require: false
  gem 'rb-fsevent', require: false
  gem 'rb-fchange', require: false
  gem 'terminal-notifier-guard'
  gem 'capistrano-rvm'
  gem 'capistrano-rails'
  gem 'capistrano-bundler'
  gem 'capistrano3-unicorn'
  gem 'capistrano-sidekiq'
  gem 'thin'
end

group :test do
  gem 'capybara'
  gem 'cucumber-rails', require: false
  gem 'database_cleaner'
  gem 'factory_girl_rails'
  gem 'spork'
end

group :ops do
  gem 'pry'
  gem 'unicorn'
end

# To use ActiveModel has_secure_password


# To use Jbuilder templates for JSON
# gem 'jbuilder'
