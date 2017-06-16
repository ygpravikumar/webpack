mkdir <Directory Name>
npm init
npm install webpack webpack-dev-server css-loader style-loader --save-dev
touch index.html
touch entry.js
mkdir js
mkdir css
touch js/content.js
touch css/style.css

add below content in entry.js
"""""""""""
require("./css/style.css");
document.write(require("./js/content.js"));
"""""""""""

populate index.html to to use bundle.js
add config settings to webpack.config.js
run ./node_modeules/.bin/webpack-dev-server to launch the webserver



