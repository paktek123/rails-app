Instructions to run:

apt-get install ruby-rvm

cd /rails-app

bundle update
bundle install Gemfile

rake db:migrate

rails s
