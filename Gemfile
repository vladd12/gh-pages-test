source "https://rubygems.org"

# Jekyll gem
gem "jekyll", "~> 3.9.2"

# Theme for Jekyll site
gem "jekyll-clean-dark", "~> 0.1.3" # https://rubygems.org/gems/jekyll-clean-dark
gem "webrick"

# GitHub Pages gem for Jekyll site
gem "github-pages", "~> 227", group: :jekyll_plugins

# Jekyll plugins
group :jekyll_plugins do
  gem "jekyll-feed", "~> 0.12"
  gem "jekyll-seo-tag", "~> 2.6"
end

# Platforms compability
platforms :mingw, :x64_mingw, :mswin, :jruby do
  gem "tzinfo", ">= 1", "< 3"
  gem "tzinfo-data"
end

# Performance-booster for watching directories on Windows
gem "wdm", "~> 0.1.1", :platforms => [:mingw, :x64_mingw, :mswin]

# Lock `http_parser.rb` gem to `v0.6.x` on JRuby builds
gem "http_parser.rb", "~> 0.6.0", :platforms => [:jruby]
