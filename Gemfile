source 'https://rubygems.org'

# Specific version of Ruby and Rails for the application
ruby '2.3.0'
gem 'rails', '4.2.5'

# Rails defaults
# ----------------------------------------------
gem 'sass-rails', '~> 5.0'
gem 'uglifier', '>= 1.3.0'
gem 'coffee-rails', '~> 4.1.0'
# See https://github.com/rails/execjs#readme for more supported runtimes
# gem 'therubyracer', platforms: :ruby
gem 'jquery-rails'
gem 'turbolinks'
gem 'jbuilder', '~> 2.0'
# bundle exec rake doc:rails generates the API under doc/api.
#gem 'sdoc', '~> 0.4.0', group: :doc
group :development, :test do
  gem 'byebug'
  gem 'web-console', '~> 2.0'
  gem 'spring'
end
# learn rails gems
#------------------------------------------------
# for foundation front-framework
gem 'foundation-rails', '~> 5.5'
# for MailChimp API
gem 'gibbon'
# for static pages like "about"
gem 'high_voltage'
# forms made easy
gem 'simple_form'
group :development do
  gem 'better_errors' # helps when things go wrong
  gem 'quiet_assets'  # suppresses distractin messages in the log
  gem 'rails_layout'  # generates files for an application layout
  gem 'sqlite3'
end
group :production do
  gem 'pg'
  gem 'rails_12factor'
end
gem 'puma'