# web: bin/rails server -p 3000
js: yarn build --watch
# web: node app.js

# web: bundle exec rails s
web: bundle exec puma -t 5:5 -p ${PORT:-3000} -e ${RACK_ENV:-development}
release: rails db:migrate
