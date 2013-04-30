source 'https://rubygems.org'
gem 'rails', '3.2.13'


group :assets do
  gem 'sass-rails',   '~> 3.2.3'
  gem 'coffee-rails', '~> 3.2.1'
  gem 'uglifier', '>= 1.0.3'
end

group :production do
	gem 'pg'
	gem "thin", ">= 1.5.0"
end

group :test do
	gem "database_cleaner", ">= 1.0.0.RC1"
	gem "email_spec", ">= 1.4.0"
	gem "cucumber-rails", ">= 1.3.1", :require => false
	gem "launchy", ">= 2.2.0"
	gem "capybara", ">= 2.0.3"
end

gem 'sqlite3', :group => [:development, :test]
gem "rspec-rails", ">= 2.12.2", :group => [:development, :test]
gem "factory_girl_rails", ">= 4.2.0", :group => [:development, :test]

gem 'jquery-rails'
gem "bootstrap-sass", ">= 2.3.0.0"
gem "devise", ">= 2.2.3"
gem "cancan", ">= 1.6.9"
gem "rolify", ">= 3.2.0"
gem "simple_form", ">= 2.1.0"
gem "gibbon", ">= 0.4.2"
gem "figaro", ">= 0.6.3"

group :development do
	gem "quiet_assets", ">= 1.0.2"
	gem "better_errors", ">= 0.7.2"
	gem "binding_of_caller", ">= 0.7.1", :platforms => [:mri_19, :rbx]
end