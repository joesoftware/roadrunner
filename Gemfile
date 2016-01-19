source 'https://rubygems.org'
ruby "2.1.2"

#gem "va_common", "~> 0.2.5"
gem "va_common", github: 'department-of-veterans-affairs/va_common', branch: 'static-header'
#gem "va_common", path: "/Users/awong/src/va/va_common"
gem 'bcrypt'
gem 'jbuilder', '~> 2.0'
gem 'jquery-rails'
gem 'pg'
gem 'puma'
gem 'rails', '4.2.4'
gem 'sass-rails', '~> 5.0'
gem 'sdoc', '~> 0.4.0', group: :doc
gem 'uglifier', '>= 1.3.0'

# For Heroku asset compilation.
group :production do
  gem 'rails_serve_static_assets'
  gem 'rails_12factor'
end

group :development do
  gem 'better_errors'
  gem 'binding_of_caller'
  gem 'guard-bundler', require: false
  gem 'pry'
end

group :test, :darwin do
  gem 'rb-fsevent'
end

group :development, :test do
  gem 'byebug'
  gem 'capybara-webkit'
  gem 'coveralls', require: false
  gem 'web-console', '~> 2.0'
  gem 'rspec-rails'
  gem 'spring'
end
