# frozen_string_literal: true

source 'https://rubygems.org'

git_source(:github) do |repo_name|
  repo_name = "#{repo_name}/#{repo_name}" unless repo_name.include?('/')
  "https://github.com/#{repo_name}.git"
end

gem 'bootsnap', require: false
gem 'bootstrap', '~> 4.0'
gem 'coveralls', require: false
gem 'devise'
gem 'devise-guests', '~> 0.6'
gem 'jbuilder', '~> 2.5'
gem 'jquery-rails'
gem 'puma', '~> 3.7'
gem 'rails', '~> 5.2'
gem 'rsolr', '>= 1.0'
gem 'webpacker', '>= 4.0.x'

gem 'blacklight', '>= 7.0.0.rc2', github: 'projectblacklight/blacklight'
gem 'blacklight-marc', '>= 7.0.0.rc1', github: 'projectblacklight/blacklight-marc'

group :development do
  gem 'foreman', '~> 0.63.0'
  gem 'listen', '>= 3.0.5', '< 3.2'
  gem 'spring'
  gem 'spring-watcher-listen', '~> 2.0.0'
  gem 'web-console', '>= 3.3.0'
end

group :development, :test do
  gem 'byebug', platforms: [:mri, :mingw, :x64_mingw]
  gem 'capybara'
  gem 'niftany'
  gem 'rspec-rails'
  gem 'rubocop'
  gem 'sqlite3'
  gem 'traject', '~> 3.0'
end

group :production, :test do
  gem 'mysql2', '>= 0.4.4', '< 0.6.0'
end
