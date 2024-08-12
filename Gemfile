# ===============================================================
# Gemfile for Sale Photo Gallery Project
# ===============================================================

# Specify the source for Ruby gems
source "https://rubygems.org"

# ---------------------------------------------------------------
# Core Dependencies
# ---------------------------------------------------------------

# GitHub Pages compatibility
# This includes Jekyll and other dependencies that GitHub Pages supports
# Rationale: Ensures your site is compatible with GitHub Pages hosting
gem "github-pages", group: :jekyll_plugins

# ---------------------------------------------------------------
# Jekyll Plugins
# ---------------------------------------------------------------

group :jekyll_plugins do
  # Jekyll Feed: Generates an Atom feed of your Jekyll posts
  # Rationale: Allows readers to subscribe to your updates
  gem "jekyll-feed", "~> 0.12"
  
  # Jekyll Remote Theme: Allows use of remote themes hosted on GitHub
  # Rationale: Necessary for using the Photorama theme
  gem "jekyll-remote-theme"
  
  # Jekyll Admin: Provides a CMS-like interface for your Jekyll site
  # Rationale: Easier content management during local development
  # Note: Comment this out when deploying to GitHub Pages
  # gem 'jekyll-admin'

  # Potential future plugins (uncomment as needed):
  # gem "jekyll-seo-tag"        # For improved SEO
  # gem "jekyll-sitemap"        # For generating sitemaps
  # gem "jekyll-paginate"       # For pagination
  # gem "jekyll-archives"       # For generating archive pages
    
    gem 'faraday-retry'
end

# ---------------------------------------------------------------
# Platform-Specific Dependencies
# ---------------------------------------------------------------

# Windows and JRuby dependencies
# Rationale: Ensures compatibility across different operating systems
platforms :mingw, :x64_mingw, :mswin, :jruby do
  gem "tzinfo", ">= 1", "< 3"
  gem "tzinfo-data"
end

# Windows-specific performance booster
# Rationale: Improves performance when running Jekyll on Windows
gem "wdm", "~> 0.1.1", platforms: [:mingw, :x64_mingw, :mswin]

# JRuby-specific HTTP parser
# Rationale: Ensures compatibility with JRuby
gem "http_parser.rb", "~> 0.6.0", platforms: [:jruby]

# ---------------------------------------------------------------
# Ruby 3.0+ Compatibility
# ---------------------------------------------------------------

# WebRick: HTTP server toolkit
# Rationale: Necessary for Ruby 3.0+ as it's no longer in standard library
gem "webrick", "~> 1.7"

# ---------------------------------------------------------------
# Development and Testing (Uncomment as needed)
# ---------------------------------------------------------------

# Rake: Ruby build program with capabilities similar to Make
# Rationale: Useful for automating tasks in Ruby projects
# gem "rake", "~> 13.0"

# RSpec: Behaviour Driven Development for Ruby
# Rationale: For writing and running tests
# gem "rspec", "~> 3.0"

# ---------------------------------------------------------------
# Future Considerations
# ---------------------------------------------------------------

# Uncomment these if you plan to use them in the future:

# Sass processing (if you decide to use Sass for styling)
# gem "sassc", "~> 2.4"

# Image processing (if you need to manipulate images)
# gem "mini_magick", "~> 4.11"

# Markdown processing alternatives
# gem "redcarpet", "~> 3.5"    # If you prefer Redcarpet over Kramdown
# gem "commonmarker", "~> 0.23" # For GitHub-flavored Markdown processing

# ---------------------------------------------------------------
# Version Control (Uncomment to lock Jekyll version)
# ---------------------------------------------------------------

# Uncomment to use a specific Jekyll version
# Note: This may override the version used by github-pages
# gem "jekyll", "~> 4.3.3"

# ===============================================================
# End of Gemfile
# ===============================================================