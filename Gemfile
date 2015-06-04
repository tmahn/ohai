source "https://rubygems.org"

gemspec

# https://github.com/sj26/rspec_junit_formatter/pull/14
# rspec_junit_formatter isn't compatible with RSpec3 yet, but is fixed in
# master. Once it's released we should remove this.
gem "rspec_junit_formatter", :git => 'https://github.com/sj26/rspec_junit_formatter.git',
                             :ref => "147836c41fab23ff7b92806f34122c8e5f2ddcad"

gem 'ffi', :git => 'https://github.com/tmahn/ffi.git', :branch => 'smartOS'

group :development do
  gem "chef", github: "opscode/chef", branch: "master"

  gem "sigar", :platform => "ruby"
  gem 'plist'

  # gem 'pry-debugger'
  # gem 'pry-stack_explorer'
end
