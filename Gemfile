source 'https://rubygems.org'

gem 'rails', '3.2.12'

# Gems used only for assets and not required
# in production environments by default.
group :assets do
  gem 'sass-rails',   '~> 3.2.3'
  gem 'coffee-rails', '~> 3.2.1'
  gem 'uglifier', '>= 1.0.3'
end

gem 'jquery-rails'

group :development do
	gem 'rspec-rails'
	gem 'sqlite3'
	gem 'guard-rspec'
	gem 'guard'
	gem 'terminal-notifier-guard'
	gem 'rb-fsevent'
	gem 'guard-spork'
	gem 'spork'
end

group :test do
	gem 'capybara', '= 1.1.2'
	gem 'guard'
	gem 'terminal-notifier-guard'
	gem 'rb-fsevent'
end

group :production do
	gem 'pg'
end