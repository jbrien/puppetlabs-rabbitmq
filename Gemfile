source 'https://rubygems.org'

group :development, :test do
  gem 'rake'
  gem 'rspec-puppet'
  gem 'puppetlabs_spec_helper',  :require => false
  gem 'rspec-system-puppet', github: 'puppetlabs/rspec-system-puppet'
  gem 'puppet-lint'
  gem 'serverspec'
  gem 'rspec-system-serverspec'
  gem 'pry'
end

if puppetversion = ENV['PUPPET_GEM_VERSION']
  gem 'puppet', puppetversion, :require => false
else
  gem 'puppet', :require => false
end

# vim:ft=ruby
