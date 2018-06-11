source 'https://rubygems.org'

gem 'jekyll', '~> 3'

group :jekyll_plugins do
  gem 'jekyll-assets', '~> 2'
end

group :jekyll_assets do
  gem 'uglifier', '~> 3.2'
  gem 'sass', '~> 3.5'
  gem 'autoprefixer-rails', '~> 7.1'
  gem "mini_magick", '~> 4.8' #Requires ImageMagick or GraphicsMagick command-line tool. https://github.com/minimagick/minimagick
end

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem "tzinfo-data", platforms: [:mingw, :mswin, :x64_mingw, :jruby]

# Performance-booster for watching directories on Windows
gem "wdm", "~> 0.1.0" if Gem.win_platform?
