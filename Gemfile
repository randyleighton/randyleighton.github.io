source 'https://rubygems.org'

ruby ENV['CUSTOM_RUBY_VERSION'] || '2.2.2'
require 'json'
require 'open-uri'
versions = JSON.parse(open('https://pages.github.com/versions.json').read)

gem 'github-pages', versions['github-pages']

