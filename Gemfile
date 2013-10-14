source 'https://rubygems.org'

gem 'rails', '3.2.14'

gem 'jquery-rails'

# Puma web server
gem 'puma', '2.6.0'

# Devise for authentication
gem 'devise'

# Simple Form
gem 'simple_form'

# paperclip
gem "paperclip", "~> 3.5.1"

# Assets group
group :assets do
  gem 'sass-rails',   '~> 3.2.3'
  gem 'coffee-rails', '~> 3.2.1'
  gem 'uglifier', '>= 1.0.3'
  gem 'bootstrap-sass', '~> 2.3.2.2'
end

# Sqlite Db in dev and test env
group :development,:test do
	gem 'sqlite3'	
end
# Postgress db in production
group :production do
	gem 'pg'
end
