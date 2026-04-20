source "https://rubygems.org"

gemspec

# Core Ruby 3.4+ fixes
gem "csv"
gem "base64"
gem "bigdecimal"
gem "logger"
gem "fiddle" 

# Plugin group - Added redirect gem here
group :jekyll_plugins do
  gem "jekyll-feed"
  gem "jekyll-gist"
  gem "jekyll-include-cache"
  gem "jekyll-paginate"
  gem "jekyll-sitemap"
  gem "jekyll-seo-tag"
  gem "jekyll-redirect-from" 
end

platforms :windows, :mingw, :x64_mingw, :mswin do
  gem "tzinfo", "~> 2.0"
  gem "tzinfo-data"
end