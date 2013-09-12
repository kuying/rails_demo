source 'http://ruby.taobao.org'

# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem 'rails', '4.0.0'

group :assets do
  # Use SCSS for stylesheets
  gem 'sass-rails', '~> 4.0.0'

  # Use Uglifier as compressor for JavaScript assets
  gem 'uglifier', '>= 1.3.0'

  # Use CoffeeScript for .js.coffee assets and views
  gem 'coffee-rails', '~> 4.0.0'
end

# See https://github.com/sstephenson/execjs#readme for more supported runtimes
# gem 'therubyracer', platforms: :ruby

# Use jquery as the JavaScript library
gem 'jquery-rails'

# Turbolinks makes following links in your web application faster. Read more: https://github.com/rails/turbolinks
gem 'turbolinks'

# Build JSON APIs with ease. Read more: https://github.com/rails/jbuilder
gem 'jbuilder', '~> 1.2'

# don't use rdoc API
# group :doc do
#  # bundle exec rake doc:rails generates the API under doc/api.
#  gem 'sdoc', require: false
#end

# Use ActiveModel has_secure_password
# gem 'bcrypt-ruby', '~> 3.0.0'

# Use unicorn as the app server
# gem 'unicorn'

# Use Capistrano for deployment
# gem 'capistrano', group: :development

# Use debugger
# gem 'debugger', group: [:development, :test]

# extended gems
# ODM for MongoDB
gem "mongoid", github: 'mongoid/mongoid', ref: '7087ec96de927f347f754e1907ca64527df6b4ea'
# forms made easy
gem 'simple_form', github: 'plataformatec/simple_form', ref: 'f0b95cb9805ebc895947cafaf33a07b67eeb8c71'

# authentication and user management
gem 'devise'

# configuration framework
gem 'figaro'

group :development do
  # helps when things go wrong.
  gem 'better_errors'
  
  # suppresses distracting messages in the log
  gem 'quiet_assets'
end

group :development, :test do
  # integration between factory_girl and rails
  gem 'factory_girl_rails'
  
  # rspec test
  gem 'rspec-rails'
end

group :test do
  # integration testing tool for rack
  gem 'capybara'
  
  # generate and runtime
  gem 'cucumber-rails', :require=>false
  
  # clean state for testing
  gem 'database_cleaner'
  
  gem 'mongoid-rspec'
  
  gem 'email_spec'
  gem 'launchy'
end
