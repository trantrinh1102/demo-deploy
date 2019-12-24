source 'https://rubygems.org'

git_source(:github) do |repo_name|
  repo_name = "#{repo_name}/#{repo_name}" unless repo_name.include?("/")
  "https://github.com/#{repo_name}.git"
end

ruby '2.4.1'
gem 'rails', '~> 5.1.2'

# Rails defaults
gem 'puma'
gem 'sass-rails', '~> 5.0'
gem 'uglifier', '>= 1.3.0'
gem 'coffee-rails', '~> 4.2'
gem 'turbolinks', '~> 5'
gem 'jbuilder', '~> 2.5'
gem 'sqlite3'

group :development, :test do
  gem 'byebug', platforms: [:mri, :mingw, :x64_mingw]
  gem 'capybara', '~> 2.13'
  gem 'selenium-webdriver'
end
group :development do
  gem 'web-console', '>= 3.3.0'
  gem 'listen', '>= 3.0.5', '< 3.2'
  gem 'spring'
  gem 'spring-watcher-listen', '~> 2.0.0'
  gem 'capistrano', '~> 3.8', '>= 3.8.1'
  gem 'capistrano-rvm', '~> 0.1.2'
  gem 'capistrano-rails', '~> 1.2', '>= 1.2.3'
  gem 'capistrano3-puma', git: 'https://github.com/seuros/capistrano-puma.git', ref: '00708fa'
  gem 'capistrano-nginx', '~> 1.0'
  gem 'capistrano-upload-config', '~> 0.7.0'
  gem 'sshkit-sudo', '~> 0.1.0'
end

# learn-rails
gem 'bootstrap-sass'
gem 'gibbon'
gem 'high_voltage'
gem 'jquery-rails'
group :development do
  gem 'better_errors'
  gem 'rails_layout'
end
group :development, :test do
  gem 'sqlite3'
end
group :production do
  gem 'pg'
end
group :test do
  gem 'minitest-spec-rails'
end
