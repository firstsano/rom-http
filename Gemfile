source 'https://rubygems.org'

gemspec

group :test do
  gem 'rom', git: 'https://github.com/rom-rb/rom', branch: 'master' do
    gem 'rom-core'
    gem 'rom-mapper'
    gem 'rom-repository', group: :tools
  end

  gem 'faraday'
  gem 'simplecov', platforms: :mri
  gem 'codeclimate-test-reporter', platforms: :mri
end

group :tools do
  gem 'byebug'
end
