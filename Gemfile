source 'https://rubygems.org'

git_source(:github) do |repo_name|
  repo_name = "#{repo_name}/#{repo_name}" unless repo_name.include?("/")
  "https://github.com/#{repo_name}.git"
end

ruby "2.2.3"
gem 'rails', '~> 5.0.2'
gem 'pg', '~> 0.18'
gem 'puma', '~> 3.0'
gem 'sqlite3', '~> 1.3'

group :development, :test do
  gem 'byebug', platform: :mri
end

group :development do
  gem 'listen', '~> 3.0.5'
end

gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]
