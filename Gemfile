source ENV['GEM_SOURCE'] || "https://rubygems.org"

group :system_tests do
  gem 'serverspec'
  gem 'beaker'
  gem 'beaker-rspec'
end

if puppetversion = ENV['PUPPET_GEM_VERSION']
  gem 'puppet', puppetversion
else
  gem 'puppet'
end

if facterversion = ENV['FACTER_GEM_VERSION']
  gem 'facter', facterversion
else
  gem 'facter'
end

gem 'puppetlabs_spec_helper'
gem 'rspec-puppet'
gem 'puppet-lint'
gem 'simplecov'
gem 'metadata-json-lint'

# vim:ft=ruby
