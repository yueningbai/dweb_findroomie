
//update:

next step: error page, algorithm


10.26 add range by age/score, add myaccount page


schema:<br>
 users<br>
 rates<br>
 
routes:<br>
 /userinfo--post--UserSchema--register: personal info (add cookie)v (tags)v option(v)<br>
 /rate--get---rateone: get info from database and display (random)v <br>
 /score--post--RateSchema: save age& score <br>
 /liked--get--likeones: find the people the user rated (range)v<br>
 /whoami--get--myaccount: display my info<br>











# NEED

node.js: v6.9.1<br>
handlebars <br>
moongoose<br>
express 4.13<br>

# build

Mac :<br>
brew install nvm<br>
vim ~/.bash_profile<br>
   `export NVM_DIR=~/.nvm`<br>
   `source $(brew --prefix nvm)/nvm.sh`<br>
$ source .bash_profile<br>
nvm ls-remote<br>
nvm install v6.9.1<br>
sudo npm install -g express --save<br>

sudo npm install -g express-generator --save<br>
npm install body-parser --save<br>
npm install cookie-parser --save<br>
npm install multer --save<br>
npm install express3-handlebars --save<br>

moongoose<br>
