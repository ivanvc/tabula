#since war/jar bundle requires gem package; use gem-in-a-box for testing
#or execute tabula via "rackup".
#source "http://127.0.0.1:9292"

source "https://rubygems.org"

ruby "2.5.7", :engine => "jruby", :engine_version => "9.2.13.0"

platform :jruby do
  gem "cuba", "~> 3.9.2"
  gem "rack", ">= 2.0.6"
  gem "tilt", "~> 2.0.8"

  group :development do
    gem 'jar-dependencies', '0.3.12'
    gem 'jbundler', '~> 0.9.3'
    gem "rake", '13.0.1'
    gem "warbler", "~> 2.0.5"
    gem "jruby-jars", "9.2.0.0"
    gem "bootstrap-sass", ">= 3.4.1"
    gem "compass", '1.0.3'
  end
end
