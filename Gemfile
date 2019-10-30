source 'https://rubygems.org'

gemspec

group :development do
  gem 'locomotivecms_common', github: 'locomotivecms/common', ref: '4d1bd56'
  # gem 'locomotivecms_common', path: '../common'
  # gem 'locomotivecms_models', '~> 0.0.1', path: '../models'
  # gem 'locomotivecms_models', '0.0.1.pre.alpha'
  # gem 'locomotivecms-liquid', path: '../liquid'
  gem 'locomotivecms-liquid', github: 'locomotivecms/liquid', ref: 'b3789b1'
  # gem 'duktape', path: '../tmp/duktape.rb'
  # gem 'duktape', github: 'judofyr/duktape.rb', ref: '20ef6a5'
  # gem 'duktape', github: 'did/duktape.rb', branch: 'any-fixnum'
  # gem 'thin'

  gem 'puma',               '~> 4.2.1'
  gem 'haml',               '~> 5.0.4'

  gem 'rack-mini-profiler', '~> 0.10.1'
  gem 'flamegraph'
  gem 'stackprof' # ruby 2.1+ only
  gem 'memory_profiler'
end

group :test do
  gem 'rspec',              '~> 3.7.0'
  gem 'json_spec',          '~> 1.1.5'
  gem 'i18n-spec',          '~> 0.6.0'

  gem 'timecop',            '~> 0.9.1'

  # gem 'pry-byebug',         '~> 3.3.0'

  gem 'rack-test',          '~> 0.8.2'

  gem 'codeclimate-test-reporter',  '~> 0.4.7',   require: false
  gem 'coveralls',                  '~> 0.8.1',   require: false
end
