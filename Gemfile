source "https://rubygems.org"

# Bundler will rely on active-fedora.gemspec for dependency information.

gemspec path: File.expand_path('..', __FILE__)


gem "ldp", github: 'cbeer/ldp'
gem 'active-triples', github: 'no-reply/ActiveTriples', ref: '4bec618710f7c87369e4e0960742d3943dec0fab'
gem 'byebug' unless ENV['TRAVIS']

group :test do
  gem 'simplecov', require: false
end

gem 'jruby-openssl', platform: :jruby
