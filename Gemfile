source 'https://rubygems.org'

#don't upgrade
gem 'rails', '3.2.21'

ruby '2.1.5'

# Bundle edge Rails instead:
# gem 'rails', :git => 'git://github.com/rails/rails.git'

gem 'pg'
gem 'foreman'
gem 'crack', '0.3.1'

# Pry for Rails, not in dev group in case running via prod/staging @ a training
gem 'pry-rails'

group :development, :mysql do
  gem 'brakeman'
  gem 'bundler-audit'
  gem 'guard-brakeman'
  gem 'guard-livereload'
  gem 'guard-rspec'
  gem 'guard-shell'
  gem 'pry'
  gem 'rack-livereload'
  gem 'rb-fsevent'
  gem 'travis-lint'
  gem 'better_errors'
  gem 'binding_of_caller'
end

gem 'gauntlt'

gem 'simplecov', :require => false, :group => :test

group :development, :test, :mysql do
  gem 'launchy'
  gem 'capybara'
  gem 'database_cleaner'
  gem 'poltergeist'
  gem 'rspec-rails', '2.14.2'
end

group :mysql do
  gem 'pg'
end

# Gems used only for assets and not required
# in production environments by default.
group :assets do
  gem 'sass-rails'
  gem 'coffee-rails'
  gem 'jquery-fileupload-rails'
  # See https://github.com/sstephenson/execjs#readme for more supported runtimes
  # gem 'therubyracer', :platforms => :ruby

  gem 'uglifier'
end

gem 'jquery-rails'

# To use ActiveModel has_secure_password
 gem 'bcrypt'

# To use Jbuilder templates for JSON
# gem 'jbuilder'

# Use unicorn as the app server
 gem 'unicorn'

# Pow related gem
gem 'powder'

gem 'aruba'
#gem 'minitest', '~> 4.0', :require=> "minitest/autorun"

#gem 'minitest'

# Deploy with Capistrano
# gem 'capistrano'

# To use debugger
# gem 'debugger'

gem 'execjs'
gem 'therubyracer'

# Add SMTP server support using MailCatcher
gem 'mailcatcher'
