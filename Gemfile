source 'http://rubygems.org'

gem 'rails', '3.1.0'

# Bundle edge Rails instead:
# gem 'rails',     :git => 'git://github.com/rails/rails.git'

# Gems used only for assets and not required
# in production environments by default.
group :assets do
  gem 'sass-rails', "  ~> 3.1.0"
  gem 'coffee-rails', "~> 3.1.0"
  gem 'uglifier'
  gem 'therubyracer'
  gem 'therubyracer'
end

gem 'jquery-rails'

# Use unicorn as the web server
# gem 'unicorn'

# Deploy with Capistrano
# gem 'capistrano'

# To use debugger
# gem 'ruby-debug19', :require => 'ruby-debug'

group :test do
  # Necessary gems for cucumber
  gem "cucumber"
  gem "cucumber-rails-training-wheels"
  gem "database_cleaner"
  gem "launchy"
  gem "capybara"
end

group :test,:development do
  # Necessary gems for rspec
  gem "rspec-rails"
  gem "ZenTest"

  # Gem for inspecting emails using cucumber
  gem "email_spec"

  # Use sqlite3 in dev and test envi only. Heroku => postgres
  gem "sqlite3"

  gem "ruby-debug19"
  gem "simplecov"
end

group :production do
  gem "pg"
end

# Use haml for template views
gem "haml"
gem "haml-rails"

# For paginating index pages
gem "will_paginate"

# For uploading file
gem "paperclip"

# User authentication system
gem "devise"
gem "cancan"
