source 'https://rubygems.org'

gem 'rails', '3.2.13'
gem 'jquery-rails'


# heroku doesn't like sqllite, set production to 'pg' datbase for heroku, and sqllite for local
group :production do
	gem 'pg'
end
group :development, :test do
	gem 'sqlite3'
end

group :assets do
	gem 'sass-rails',   '~> 3.2.3'
	gem 'coffee-rails', '~> 3.2.1'
	gem 'uglifier', '>= 1.0.3'
end