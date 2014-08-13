# blog.pebblecode.com Ghost theme

**Getting started**

First download the existing blog content from Dropbox. See MD for details.

**Installing Ghost**
* Pull down the Ghost repo `git clone https://github.com/TryGhost/Ghost.git`
* Revert to Ghost V 0.0.5 `git reset --hard b6507bed9be699e039e127130b950814c7b79974`
* Install Grunt `npm install -g grunt-cli`
* Install Dependancies `npm install`
* Build Assets `grunt init`
* Start Ghost `npm start`
* View Ghost at `http://localhost:2368`

**Adding content**
* Log into Ghost at `http://localhost:2368/ghost`
* Create an Account
* Navigate to `http://localhost:2368/ghost/debug/`
* Under 'import' chose the file `pc-blog-posts.json` from the Dropbox download.
* Copy contents of Dropbox 'archive' directory to `../content/images/archive`

**Install blog.pebblecode theme**
* Clone this repo into `/content/themes/`
* Restart Ghost if running
* Log into Ghost at `http://localhost:2368/ghost`
* Go to settings, Under theme select `blog.pebblecode.com Ghost theme - 0.0.1`