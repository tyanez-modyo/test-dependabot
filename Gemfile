# By placing all of Modyo's shared dependencies in this file and then loading
# it for each component's Gemfile, we can be sure that we're only testing just
# the one component of Modyo.
source 'https://rubygems.org'

group :development do
  gem 'listen', '~> 3.9'
  gem 'rubocop', '1.56.3'
  gem 'rubocop-performance'
  gem 'rubocop-rails'
  gem 'web-console', '>= 3.3.0'
  gem 'yard', '0.9.36'
end

group :development, :test do
  gem 'awesome_print'
  gem 'debug', '>= 1.0.0'
  gem 'factory_bot_rails', '6.4.3', require: false
  gem 'i18n-tasks'
  gem 'parallel_tests'
  gem 'rspec-rails'
  gem 'stackprof'
end

group :test do
  gem 'database_cleaner-active_record'
  gem 'rails-controller-testing'
  gem 'rspec-activemodel-mocks'
  gem 'shoulda-matchers', '6.2.0'
  gem 'simplecov', '~> 0.22.0', require: false
  gem 'webmock', '>= 3.6.0'
end

