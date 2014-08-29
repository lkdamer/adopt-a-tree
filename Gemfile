source 'https://rubygems.org'
ruby '2.1.2'

gem 'rails', '~> 4.1.0'

gem 'active_model_serializers'
gem 'activerecord-postgis-adapter'
gem 'arel'
gem 'devise'
gem 'geocoder'
gem 'geokit'
gem 'haml'
gem 'http_accept_language'
gem 'nokogiri'
gem 'pg'
gem 'rails_12factor'
gem 'rails_admin'
gem 'validates_formatting_of'

platforms :ruby_18 do
  gem 'fastercsv'
end

group :assets do
  gem 'sass-rails', '>= 4.0.3'
  gem 'uglifier'
end

group :development do
  gem 'spring'
end

group :development, :test do
  gem 'pry-rails'
end

group :production do
  gem 'puma'
end

group :test do
  gem 'coveralls', require: false
  gem 'rubocop'
  gem 'simplecov', require: false
  gem 'sqlite3'
  gem 'webmock'
end
