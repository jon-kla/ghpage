source "https://rubygems.org"

# GitHub Pages Gem - enthält Jekyll und alle unterstützten Plugins
gem "github-pages", group: :jekyll_plugins

# Windows-spezifische Gems
platforms :mingw, :x64_mingw, :mswin, :jruby do
  gem "tzinfo", ">= 1", "< 3"
  gem "tzinfo-data"
end

# Performance-Booster für Windows Directory Watching
gem "wdm", "~> 0.1", :platforms => [:mingw, :x64_mingw, :mswin]