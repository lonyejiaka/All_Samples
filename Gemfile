source 'https://rubygems.org'

git_source(:github) do |repo_name|
  repo_name = "#{repo_name}/#{repo_name}" unless repo_name.include?("/")
  "https://github.com/#{repo_name}.git"
end

gem 'rest-client'
gem 'json'

# Only required for file upload types (Guardium and Qualys to Kenna Direct), comment out if unneeded:
gem 'nokogiri'
