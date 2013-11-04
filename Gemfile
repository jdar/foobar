source 'http://rubygems.org'
#ruby '2.0.0'
gem 'rails', '3.2.14'

group :assets do
  gem 'sass-rails',   '~> 3.2.3'  # Dynamic CSS
  gem 'coffee-rails', '~> 3.2.1'  # Coffee Syntax for JavaScript
  gem 'uglifier', '>= 1.0.3'      # JavaScript Compression
  gem 'jquery-rails'              # JQuery
  gem 'jquery-ui-rails'           # JQuery
  gem 'ckeditor_rails'
  gem 'less-rails'
  gem 'therubyracer'              # JavaScript Runtime Library
  gem 'less-rails-bootstrap'
end

group :development do
  gem 'capistrano'
  gem 'capistrano-ext'
  gem 'rvm-capistrano'
  gem 'better_errors'
  gem 'binding_of_caller'
  gem 'meta_request'
end

# Any gems that are built using native extensions should be placed in the native group.  This will
# keep them from being loaded once the code is pushed to ALTESS.  These gems should be manually installed
# on all the ALTESS web servers.
group :native do
  gem 'mysql2', "= 0.3.13"
  gem 'nokogiri', "= 1.6.0"
end

gem 'paper_trail', '~> 2'   # Versioning for models (Auditing, See versions table in DB)
gem 'kaminari'              # Paging large result sets (Navigation)
gem "ransack", "~> 1.0.0"
gem 'validates_timeliness', '~> 3.0.2'
gem "best_in_place"
gem 'jbuilder'
gem 'whenever'
gem 'memcache-client' #TODO: Change to dalli
gem 'libxml-ruby'
gem 'libxslt-ruby'
gem 'diffy'

# Procurement Document export gems
gem 'wicked_pdf'            # Used to export .pdf files
gem 'wkhtmltopdf_32_amd64'  # PDF library
gem 'serenity-odt'          # Used to export .odf files
gem 'rubyzip'               # required by odf-report

group :test do
  gem 'minitest-spec-rails'
  gem "mocha", :require => false

  gem "minitest-metadata", "~> 0.4.0"
  gem "minitest-reporters", "~> 0.14.23"
  #gem "fakefs", :require => "fakefs/safe"
  gem "vcr", "~> 2.6.0"
  gem "webmock", "= 1.13.0"
  gem 'cucumber-rails', :require => false
  gem 'capybara'
  gem "poltergeist", "~> 1.4.1"  # 'brew install phantomjs' is required locally; Travis CI has PhantomJS pre-installed.
  gem 'database_cleaner', '~> 0.7.2'
  gem 'factory_girl_rails', '~> 4.2.1'
  gem 'faker', '~> 1.2.0'
  gem 'autotest-standalone'
  gem 'autotest-rails-pure'
  gem 'autotest-standalone'
  gem 'autotest-notification'
  gem 'autotest-fsevent'
  gem "test_after_commit", "~> 0.2.1"
  #gem "launchy", "~> 2.3.0"
end

group :test, :development do
  gem "m"
  gem 'pry', :require => false
  gem 'simplecov', :require => false  # code coverage reports
end

