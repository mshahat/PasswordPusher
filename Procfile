release: bundle exec rails db:migrate
web: bundle exec rake db:migrate && bundle exec puma -C config/puma.rb 
internalweb: bundle exec puma -C config/puma.rb -e private
console: bundle exec rails console
