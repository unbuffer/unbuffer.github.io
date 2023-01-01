# frozen_string_literal: true

source "https://rubygems.org"

ruby "3.1.3"

gem "jekyll-theme-chirpy", "~> 5.4", ">= 5.4.0"

group :test do
  gem "html-proofer", "~> 3.18"
end

#gem "google-protobuf", "~> 3.21","<= 3.21.8"
#gem "nokogiri","~> 1.13", "<= 1.13.9"

# Windows and JRuby does not include zoneinfo files, so bundle the tzinfo-data gem
# and associated library.
install_if -> { RUBY_PLATFORM =~ %r!mingw|mswin|java! } do
  gem "tzinfo", "~> 1.2"
  gem "tzinfo-data"
end

# Performance-booster for watching directories on Windows
gem "wdm", "~> 0.1.1", :install_if => Gem.win_platform?

# Jekyll <= 4.2.0 compatibility with Ruby 3.0
gem "webrick", "~> 1.7"
