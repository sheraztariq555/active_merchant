source :rubygems
gemspec

group :test do
  gem 'json-jruby', :platforms => :jruby
  gem 'jruby-openssl', :platforms => :jruby
end

group :remote_test do
  gem 'mechanize'
  gem 'launchy'
  gem 'mongrel', '1.2.0.pre2', :platforms => :ruby
end

group :test, :remote_test do
  gem 'rails', '~> 3.1.8'

  # gateway-specific dependencies, keeping these gems out of the gemspec
  gem 'samurai', '>= 0.2.25'
  gem 'braintree', '>= 2.0.0'
  gem 'vindicia-api', :git => 'git://github.com/agoragames/vindicia-api.git', :ref => "4e78744c79cb97448ff46c21301f53b346db4c91"
  gem 'LitleOnline', '>= 8.13.2'
end
