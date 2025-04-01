source "https://rubygems.org"
ruby "3.3.7"
gem "rails", "~> 8.0.2"
gem "propshaft"
gem "pg", "~> 1.1"
gem "puma", ">= 5.0"
gem "importmap-rails"
gem "turbo-rails"
gem "stimulus-rails"
gem "jbuilder"
gem "solid_cache"
gem "solid_queue"
gem "solid_cable"
gem "bootsnap", require: false
gem "devise"
gem "autoprefixer-rails"
gem "simple_form", github: "heartcombo/simple_form"

group :development, :test do
  gem "dotenv-rails"
  gem "debug", platforms: %i[ mri windows ], require: "debug/prelude"
end

group :development do
  gem "web-console"
end

group :test do
  gem "capybara"
  gem "selenium-webdriver"
end
