source 'https://rubygems.org'

git_source(:github) do |repo_name|
  repo_name = "#{repo_name}/#{repo_name}" unless repo_name.include?("/")
  "https://github.com/#{repo_name}.git"
end


# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem 'rails', '~> 5.0.1'
gem 'devise', github: 'plataformatec/devise', branch: 'master'

gem 'puma'

#gem 'active_model_serializers', '~> 0.10.0.rc2'
gem "active_model_serializers", github: "rails-api/active_model_serializers", tag: "v0.10.0.rc4"
gem 'will_paginate', '~> 3.1.0'


# gem 'active-model-adapter-source', '~> 0.1.7'

gem 'rack-cors', :require => 'rack/cors'

gem 'carrierwave', github: 'carrierwaveuploader/carrierwave'
gem 'cloudinary'
gem "mini_magick"
gem 'active_model_otp'




group :production do
  gem 'pg' ,'0.18.1'
   gem 'rails_12factor', '0.0.2'
end



group :development do
  gem 'byebug'

  gem 'mysql2', '~> 0.3.18'
  gem 'listen', '~> 3.0.5'


end
