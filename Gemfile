source "https://rubygems.org"

# Hello! This is where you manage which Jekyll version is used to run.
# When you want to use a different version, change it below, save the
# file and run `bundle install`. Run Jekyll with `bundle exec`, like so:
#
#     bundle exec jekyll serve
#
# This will help ensure the proper Jekyll version is running.
# Happy Jekylling!

# NOTE on local vs. GitHub Pages:
# GitHub Pages builds this site itself, server-side, using its own locked
# Ruby/Jekyll/plugin versions (the "github-pages" gem) -- it does not run
# `bundle install` against this Gemfile. So the choice of gem here only
# affects local preview and has no effect on the published site.
#
# The "github-pages" gem pins a very old Jekyll/Liquid that no longer runs
# on modern Ruby (3.2+ removed String#tainted?, which old Liquid needs), so
# we use native Jekyll locally instead. GitHub Pages only allows a specific
# whitelisted set of plugins in production regardless -- see `plugins:` in
# _config.yml -- so listing the same plugins below keeps local preview
# matching production behavior.
gem "jekyll"

gem "wdm", "~> 0.1.0" if Gem.win_platform?

# If you have any plugins, put them here!
group :jekyll_plugins do
  gem "jekyll-paginate"
  gem "jekyll-sitemap"
  gem "jekyll-gist"
  gem "jekyll-feed"
  gem "jekyll-redirect-from"
end

# Ruby 3.4+ no longer bundles these by default; some dependencies still
# expect them to be available.
gem "csv"
gem "logger"
gem "base64"
gem "bigdecimal"
