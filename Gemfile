source 'https://rubygems.org'

gemspec

gem 'devise', :git => 'git://github.com/plataformatec/devise.git', :branch => 'rails4'

group :test do
  platforms :jruby do
    gem 'activerecord-jdbcsqlite3-adapter'
    gem "bson", "~> 1.3"
  end

  platforms :ruby do
    gem "sqlite3", "~> 1.3.4"
    gem "bson_ext", "~> 1.3"
  end

  gem 'activerecord', '~> 4.0.0.beta'
  gem "mongoid", :github => "mongoid/mongoid", :branch => "master"
  gem "capybara", "~> 1.1.0"
  gem 'shoulda', '~> 2.11.3'
  gem 'mocha', '~> 0.13.0'
  gem 'factory_girl_rails', '~> 1.2'
end
