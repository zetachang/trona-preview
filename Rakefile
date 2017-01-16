task :build do
  sh "bundle exec opal-build --require trona trona --output build-out/trona.js"
  sh "uglifyjs build-out/trona.js --output build-out/trona.min.js"
  sh "mv build-out/trona.min.js docs/dist/trona.min.js"
end
