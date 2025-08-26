# frozen_string_literal: true

source "https://rubygems.org"

gem "jekyll-theme-chirpy"
gem "html-proofer"

# Windows and JRuby do not include zoneinfo files, so bundle the tzinfo-data gem
platforms :windows, :jruby do
  gem "tzinfo"
  gem "tzinfo-data"
end

# Performance booster for watching directories on Windows
gem "wdm", :platforms => [:windows]

# Lock http_parser.rb to 0.6.x on JRuby
gem "http_parser.rb", :platforms => [:jruby]
