source "https://rubygems.org"

ruby "3.1.1"

# Bundle edge Rails instead: gem "rails", github: "rails/rails", branch: "main"
gem "rails", "~> 7.1.2"

# Use postgresql as the database for Active Record
gem "pg", "~> 1.5"

# Use the Puma web server [https://github.com/puma/puma]
gem "puma", "~> 6.4"

# Build JSON APIs with ease [https://github.com/rails/jbuilder]
gem "jbuilder", "~> 2.11"

# Use Redis adapter to run Action Cable in production
# gem "redis", ">= 4.0.1"

# Use Kredis to get higher-level data types in Redis [https://github.com/rails/kredis]
# gem "kredis"

# Use Active Model has_secure_password [https://guides.rubyonrails.org/active_model_basics.html#securepassword]
# gem "bcrypt", "~> 3.1.7"

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem "tzinfo-data", platforms: %i[windows jruby]

# Reduces boot times through caching; required in config/boot.rb
gem "bootsnap", require: false

# Use Active Storage variants [https://guides.rubyonrails.org/active_storage_overview.html#transforming-images]
# gem "image_processing", "~> 1.2"

# Use Rack CORS for handling Cross-Origin Resource Sharing (CORS), making cross-origin Ajax possible
# gem "rack-cors"

group :development, :test do
  # A static analysis tool which checks Ruby on Rails applications for security vulnerabilities.
  gem "brakeman", "~> 6.1.1"
  # See https://guides.rubyonrails.org/debugging_rails_applications.html#debugging-with-the-debug-gem
  gem "debug", platforms: %i[mri windows]
  # A Ruby gem to load environment variables from `.env`
  gem "dotenv-rails", "~> 2.1"
  # A library for setting up Ruby objects as test data
  gem "factory_bot_rails", "~> 6.4"
  # A library for generating fake data such as names, addresses, and phone numbers
  gem "faker", "~> 3.2"
  # Detecting non-atomic interactions within DB transactions.
  gem "isolator", "~> 1.0.1"
  # Ruby extension to parse, deparse and normalize SQL queries using the PostgreSQL query parser. Used by `prosopite`
  gem "pg_query", "~> 5.1"
  # Monitoring all SQL queries using the Active Support and looks for N+1 with zero false positives / false negatives
  gem "prosopite", "~> 1.4.2"
  # Examining Ruby classes, modules and methods and reports any Code Smells it
  gem "reek", "~> 6.2"
  # RSpec for Rails
  gem "rspec-rails", "~> 6.1"
  # Ruby static code analyzer (a.k.a. linter) and code formatter
  gem "rubocop", "~> 1.59", require: false
  gem "rubocop-performance", "~> 1.20"
  gem "rubocop-rails", "~> 2.23.1"
  gem "rubocop-rspec", "~> 2.26.1"
end

group :development do
  # Speed up commands on slow machines / big apps [https://github.com/rails/spring]
  gem "spring", "~> 4.1"

  gem "error_highlight", ">= 0.4.0", platforms: [:ruby]
end

group :test do
  # Simple one-liner tests for common Rails functionality
  gem "shoulda-matchers", "~> 6.0"
  # Code coverage analysis tool for Ruby
  gem "simplecov", "~> 0.22"
end
