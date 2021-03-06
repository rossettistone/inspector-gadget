source 'https://rubygems.org'
ruby '2.3.0'

gem 'rails', '4.2.7'
gem 'newrelic_rpm'
gem 'bugsnag'

gem 'puma'

gem 'pg'
gem 'activerecord-postgis-adapter'

gem 'sass-rails', '~> 5.0'
gem 'foundation-rails'

gem 'haml-rails'

gem 'uglifier', '>= 1.3.0'
gem 'therubyracer', platforms: :ruby

gem 'jquery-rails'
gem 'jquery-ui-sass-rails'
gem 'lodash-rails'

gem 'compass-rails' # chosen-rails 1.5.1 seems to have this as an undeclared dependency
gem 'chosen-rails', '1.5.1'

gem 'groupdate'
gem 'chartkick'

gem 'business_time'
gem 'holidays'
gem 'phony_rails'

gem 'rubyzip'

gem 'geocoder'
gem 'rgeo-geojson'
gem 'rgeo-shapefile'

gem 'devise'
gem 'activeadmin', git: 'https://github.com/activeadmin/activeadmin'

group :production do
  gem 'rails_12factor'
end

group :development, :test do
  gem 'byebug'
end

group :development do
  gem 'better_errors'
  gem 'binding_of_caller'
end

group :test do
  gem 'rspec'
  gem 'rspec-rails'
  gem 'database_cleaner'
  gem 'capybara'
  gem 'capybara-webkit'
  gem 'factory_girl_rails'
  gem 'faker'
  gem 'timecop'
  gem 'codeclimate-test-reporter', require: false
end
