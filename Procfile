web: node server.js
sync: browser-sync start --files "*.html, dist/*.js, dist/*.css" --proxy localhost:3001
signalhub: signalhub listen -p 8080
watch: watchify src/index.js -o dist/bundle.js
css: node-sass -w css/index.scss dist/bundle.css
