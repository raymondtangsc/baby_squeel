source 'https://rubygems.org'

# Specify your gem's dependencies in baby_squeel.gemspec
gemspec

if ar_version = ENV['AR']
  gem 'activerecord', ar_version
else
  gem 'activerecord'
end

gem 'bump'

group :test do
  gem 'pry'
  gem 'coveralls'
  gem 'simplecov'
  gem 'filewatcher'
end
