source "https://rubygems.org"
ruby '2.3.3'

# To upgrade, run `bundle update github-pages`.
gem 'github-pages', group: :jekyll_plugins

# If you have any plugins, put them here!
group :jekyll_plugins do
   gem "jekyll-feed", "~> 0.6"
end

group :api do
  gem 'netrc'
  gem 'octokit'
end

group :test do
  gem 'html-proofer'
end

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]

