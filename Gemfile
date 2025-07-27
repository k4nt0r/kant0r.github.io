source "https://rubygems.org"

# Updated Jekyll to latest 4.3.x for Ruby 3.4 compatibility
gem "jekyll", "~> 4.3"

# This is the default theme for new Jekyll sites. You may change this to anything you like.
# gem "minima", "~> 2.5"

# If you want to use GitHub Pages, remove the "gem 'jekyll'" above and
# uncomment the line below. To upgrade, run `bundle update github-pages`.
# gem "github-pages", group: :jekyll_plugins

# Jekyll plugins
group :jekyll_plugins do
  gem "jekyll-feed", "~> 0.12"
  gem "jekyll-tidy"
end

# Windows and JRuby do not include zoneinfo files, so bundle the tzinfo-data gem
# and associated library.
install_if -> { RUBY_PLATFORM =~ %r!mingw|mswin|java! } do
  gem "tzinfo", "~> 1.2"
  gem "tzinfo-data"
end

# Performance booster for watching directories on Windows (optional)
gem "wdm", "~> 0.2.0", :install_if => Gem.win_platform?

# Extra plugins and dependencies
gem "jekyll-sitemap"
gem "kramdown-math-katex"
gem "webrick", "~> 1.7"

# Required for Ruby 3.3+ because CSV is no longer bundled
gem "csv"
