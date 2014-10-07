source ENV['GEM_SOURCE'] || "https://rubygems.org"

case RUBY_VERSION
when '1.8.7'
  gem 'rake', '<= 10.1.1'
else
  gem 'rake'
end

group :acceptance do
  gem 'beaker', '~> 1.11'
  gem 'beaker-rspec', :require => false
end
