source "https://rubygems.org"

gem "sinatra"
gem "json"
gem "redis"
gem "capistrano"
gem "httparty"
gem "whenever"
gem "aws-sdk", "~> 2"
gem "dotenv"
gem "cityhash"

group :development do
	gem 'foreman'
end

group :production do
  gem 'unicorn', :platforms => :ruby
  gem 'capistrano-rbenv'
  gem 'capistrano3-unicorn', :require => false
  gem 'capistrano-bundler'
end
