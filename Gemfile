source 'https://rubygems.org'

git_source(:github) do |repo_name|
  repo_name = "#{repo_name}/#{repo_name}" unless repo_name.include?("/")
  "https://github.com/#{repo_name}.git"
end

gem 'rails',      '5.1.4'
gem 'i18n',       '~> 0.7'
gem 'pg',         '0.21.0'
gem 'puma',       '3.11.0'
gem 'sass-rails', '5.0.7'
gem 'uglifier',   '4.0.2'

gem 'coffee-rails',      '4.2.2'
gem 'jquery-rails',      '4.3.1'
gem 'turbolinks',        '5.0.1'
gem 'jquery-turbolinks', '2.1.0'
gem 'jbuilder',          '2.7.0'

gem 'aasm', '4.12.3'

gem 'lodash-rails', '4.17.4'
gem 'local_time',   '2.0.0'
gem 'redis',        '4.0.1'

gem 'devise',           '4.3.0'
gem 'devise_invitable', '1.7.2'
gem 'rolify',           '5.1.0'
gem 'cancancan',        '2.1.2'

gem 'paper_trail',  '8.1.1'
gem 'ranked-model', '0.4.0'

gem 'bootstrap',          '4.0.0.beta2.1'
gem "font-awesome-rails", '4.7.0.2'

gem 'friendly_id', '5.2.3'

gem 'sidekiq'
gem 'sinatra', github: 'sinatra/sinatra', require: nil
gem 'sidekiq-statistic', '1.2.0'

gem 'gravatar_image_tag', '1.2.0'
gem 'country_select',     '3.1.1'
gem 'kaminari',           '1.1.1'

gem 'paperclip', '5.1.0'
gem 'aws-sdk',   '3.0.1'

gem 'money-rails', '1.9.0'

gem 'ransack', '1.8.4'

gem 'slack-notifier', '2.3.1'

gem 'premailer-rails',  '1.10.1'
gem 'griddler',         '1.4.0'
gem 'griddler-mailgun', '1.0.3'

gem 'rollbar', '2.15.5'

gem 'factory_bot_rails', '4.8.2'

gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]

gem 'rack-cors', '1.0.2', require: 'rack/cors'

group :development, :test do
  gem 'byebug',      '9.1.0', platform: :mri
  gem 'rspec-rails', '3.7.2'
end

group :development do
  gem 'letter_opener',         '1.4.1'
  gem 'web-console',           '3.5.1'
  gem 'listen',                '3.1.5'
  gem 'spring',                '2.0.2'
  gem 'spring-watcher-listen', '2.0.1'
  gem 'capybara',              '2.16.1'
end

group :test do
  gem 'simplecov', '0.15.1', require: false
end
