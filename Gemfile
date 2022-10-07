# frozen_string_literal: true

source "https://rubygems.org"

git_source(:github) { |repo_name| "https://github.com/#{repo_name}" }

# gem "rails"

#the reason for this to import the gem inside this program ONLY
#locally - computer/system - gemfile reference eg "gem "rest-client""
#globaly - install via terminal ex: gem install [gem]
source "https://rubygems.org"
gem "rest-client"
#lock in version 5.0 and get all of hashie or all the gems in the Gemfile dependecies 
gem 'hashie', '~> 5.0'
gem "sinatra", "2.0.2"
gem "octokit", "~> 2.0"
gem 'awesome_print', git: "git@github.com:awesome-print/awesome_print.git"
gem "pry", :group => "development"


# group :development do
#     gem 'pry'
# end 



#block syntax
group :test do
    gem "rspec"
end 