source 'https://rubygems.org'
ruby '2.7.2'

gem 'bootsnap', '>= 1.4.2', require: false
gem 'rails', '~> 6.1.4'

# WebServer
gem 'puma', '~> 5.6'
gem 'rack', '~> 2.2.3'
gem 'rack-attack', '~> 6.6.0'
gem 'rack-cors', '~> 1.1.1'

# Database
gem 'pg', '~> 1.3.3'
gem 'strong_migrations', '~> 0.8.0'

# Environment variables
gem 'dotenv-rails', '~> 2.7.6'

# Async worker
gem 'sidekiq', '~> 6.4.1'

# Nullify blank strings before saving to db
gem 'nilify_blanks', '~> 1.4'

# Backoffice
gem 'activeadmin', '~> 2.10.0'
gem 'activeadmin_addons', '~> 1.9.0'
gem 'active_admin_theme', '~> 1.1'
gem 'chartkick', '~> 4.1.3'
gem 'groupdate', '~> 6.0.1'
gem 'ransack', '~> 2.5.0'

# Authentication
gem 'devise', '~> 4.8.1'
gem 'devise_token_auth', '~> 1.2.0'

# Serializing json views
gem 'jb', '~> 0.8.0'

# Pagination
gem 'pagy', '~> 5.10'

# Monitoring errors
gem 'sentry-rails'
gem 'sentry-ruby'
gem 'sentry-sidekiq'

group :development, :test do
  gem 'bullet', '~> 7.0.1'
  gem 'byebug', '>= 11.0.1', platforms: %i[mri mingw x64_mingw]
  gem 'factory_bot_rails', '~> 6.2.0'
  gem 'faker', '~> 2.19.0'
  gem 'rspec-rails', '~> 5.1.0'
end

group :development do
  gem 'annotate', '~> 3.2.0'
  gem 'letter_opener', '~> 1.7.0'
  gem 'listen', '>= 3.0.5', '< 3.8'
  gem 'reek', '~> 6.1.0', require: false
  gem 'rubocop', '~> 1.25.1', require: false
  gem 'rubocop-rails', '~> 2.13.2', require: false
  gem 'rubocop-rspec', '~> 2.8.0', require: false
  gem 'spring', '~> 2.1.1'
  gem 'spring-watcher-listen', '~> 2.0.0'
end

group :test do
  gem 'rspec-json_expectations', '~> 2.2.0'
  gem 'shoulda-matchers', '~> 5.1.0'
  gem 'simplecov', '~> 0.21.2'
  gem 'webmock', '~> 3.14.0'
end

gem 'tzinfo-data', platforms: %i[mingw mswin x64_mingw jruby]
