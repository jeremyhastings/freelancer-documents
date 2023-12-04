# frozen_string_literal: true

source 'https://rubygems.org'
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby '3.0.2'

# Bundle edge Rails instead: gem "rails", github: "rails/rails", branch: "main"
gem 'rails', '~> 7.0.0.alpha2'

# Use postgresql as the database for Active Record
gem 'pg', '~> 1.1'

# Use the Puma web server [https://github.com/puma/puma]
gem 'puma', '~> 5.0'

# Build JSON APIs with ease [https://github.com/rails/jbuilder]
# gem "jbuilder", "~> 2.7"

# Use Redis adapter to run Action Cable in production
# gem "redis", "~> 4.0"

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem 'tzinfo-data', platforms: %i[mingw mswin x64_mingw jruby]

# Reduces boot times through caching; required in config/boot.rb
gem 'bootsnap', '>= 1.4.4', require: false

# Use Active Model has_secure_password [https://guides.rubyonrails.org/active_model_basics.html#securepassword]
# gem "bcrypt", "~> 3.1.7"

# Use Active Storage variants [https://guides.rubyonrails.org/active_storage_overview.html#transforming-images]
# gem "image_processing", "~> 1.2"

# Use Rack CORS for handling Cross-Origin Resource Sharing (CORS), making cross-origin AJAX possible
gem 'rack-cors'

group :development, :test do
  # Start debugger with binding.b [https://github.com/ruby/debug]
  gem 'byebug', platforms: %i[mri mingw x64_mingw]
  gem 'debug', '>= 1.0.0', platforms: %i[mri mingw x64_mingw]
  gem 'reek' # https://github.com/troessner/reek (Linter)
  gem 'rubocop', '~> 0.9', require: false # https://github.com/rubocop-hq/rubocop (Linter)
  gem 'rubocop-performance', require: false # https://github.com/rubocop/rubocop-performance
  gem 'rubocop-rails' # https://github.com/rubocop-hq/rubocop-rails (Linter)
  gem 'rubocop-rspec' # https://github.com/rubocop-hq/rubocop-rspec (Linter)
end

group :development do
  # Speed up commands on slow machines / big apps [https://github.com/rails/spring]
  # gem "spring"
end

group :test do
  gem 'capybara' # https://github.com/teamcapybara/capybara
  gem 'cuprite' # https://github.com/rubycdp/cuprite
  gem 'factory_bot_rails'
  gem 'faker'
  gem 'rspec_junit_formatter'
  gem 'rspec-rails', '~> 6.1.0'
  gem 'simplecov', require: false
  gem 'vcr', require: false # https://github.com/vcr/vcr
  gem 'webmock', require: false
end
