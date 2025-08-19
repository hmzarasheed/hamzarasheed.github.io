source "https://rubygems.org"
# Hello! This is where you manage which Jekyll version is used to run.
# When you want to use a different version, change it below, save the
# file and run `bundle install`. Run Jekyll with `bundle exec`, like so:
#
#     bundle exec jekyll serve
#
# This will help ensure the proper Jekyll version is running.
# Happy Jekylling!
gem "jekyll", "~> 3.9"

# If you want to use GitHub Pages, remove the "gem "jekyll"" above and
# uncomment the line below. To upgrade, run `bundle update github-pages`.
# gem "github-pages", group: :jekyll_plugins
# If you have any plugins, put them here!
group :jekyll_plugins do
  gem "jekyll-feed", "~> 0.12"
  gem "jekyll-sitemap", "~> 1.3", '< 1.4'
  gem "jekyll-seo-tag", "~> 2.6"
  gem "kramdown-parser-gfm", "~> 1.1.0"
  gem "webrick", "~> 1.7.0"
end

# Windows and JRuby does not include zoneinfo files, so bundle the tzinfo-data gem
# and associated library.
platforms :windows, :jruby do
  gem "tzinfo", ">= 1", "< 3"
  gem "tzinfo-data"
end

# Performance-booster for watching directories on Windows
# Using listen gem instead of wdm for better Ruby 3.4+ compatibility
gem "listen", "~> 3.0", :platforms => [:windows]

# Required gems for Ruby 3.4+ compatibility (moved from default to bundled gems)
gem "base64"
gem "logger"
gem "bigdecimal"
gem "csv"
gem "drb"
gem "getoptlong"
gem "mutex_m"
gem "nkf"
gem "observer"
gem "racc"
gem "resolv-replace"
gem "rinda"
gem "syslog"

# Lock `http_parser.rb` gem to `v0.6.x` on JRuby builds since newer versions of the gem
# do not have a Java counterpart.
gem "http_parser.rb", "~> 0.6.0", :platforms => [:jruby]
