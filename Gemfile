source "https://rubygems.org"

gem "middleman", "~>3.0.11"
gem "middleman-deploy", "~> 0.0.11"

gem "pdfkit", "~>0.5.2"
gem 'wkhtmltopdf_binary_provider'

if /linux|bsd/ =~ RUBY_PLATFORM
    gem 'execjs'
    gem 'therubyracer'
    if /linux/ =~ RUBY_PLATFORM
        gem 'rb-inotify', '~> 0.9'
    end
end


