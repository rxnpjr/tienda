source 'https://rubygems.org'


# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem 'rails', '4.2.0'
# Use sqlite3 as the database for Active Record
group :development do 
  gem 'sqlite3'
end
#Instalar bootstrap
gem 'bootstrap-sass', '~> 3.3.3'
# Use SCSS for stylesheets
gem 'sass-rails', '~> 5.0'
# Use Uglifier as compressor for JavaScript assets
gem 'uglifier', '>= 1.3.0'
# Use CoffeeScript for .coffee assets and views
gem 'coffee-rails', '~> 4.1.0'
# See https://github.com/sstephenson/execjs#readme for more supported runtimes
# gem 'therubyracer', platforms: :ruby
gem 'dotenv-rails', :groups => [:development, :test]
# Use jquery as the JavaScript library
gem 'jquery-rails'
# Turbolinks makes following links in your web application faster. Read more: https://github.com/rails/turbolinks
gem 'turbolinks'
# Build JSON APIs with ease. Read more: https://github.com/rails/jbuilder
gem 'jbuilder', '~> 2.0'
# bundle exec rake doc:rails generates the API under doc/api.
gem 'sdoc', '~> 0.4.0', group: :doc

# Use ActiveModel has_secure_password
# gem 'bcrypt', '~> 3.1.7'

# Use Unicorn as the app server
# gem 'unicorn'

# Use Capistrano for deployment
# gem 'capistrano-rails', group: :development

gem 'devise'

gem 'omniauth-twitter'

#Before install imagemagick
# for mac => brew install imagemagick
# for linux => sudo apt-get install imagemagick
#installing the gem
#rails g migration add_avatar_to_users avatar:string
gem 'carrierwave'
gem 'rmagick'
gem 'mini_magick'

group :development, :test do
  # Call 'byebug' anywhere in the code to stop execution and get a debugger console
  gem 'byebug'

  # Access an IRB console on exception pages or by using <%= console %> in views
  gem 'web-console', '~> 2.0'

  # Spring speeds up development by keeping your application running in the background. Read more: https://github.com/rails/spring
  gem 'spring'

  gem "daemons"
  gem 'delayed_job_active_record'

  gem 'whenever'

  #rspec
  gem 'rspec-collection_matchers'
  gem 'rspec-rails', '~> 3.0'

end

group :production do 
  gem 'pg', '0.15.1'
  gem 'rails_12factor', '0.0.2'
end





