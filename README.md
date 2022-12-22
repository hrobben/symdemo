# symdemo

Answers
Sorted by:
1724

Use n module from npm in order to upgrade node

sudo npm cache clean -f

sudo npm install -g n

sudo n stable


To upgrade to latest version (and not current stable) version, you can use

sudo n latest

    Fix PATH:

      sudo apt-get install --reinstall nodejs-legacy     # fix /usr/bin/node

    To undo:

      sudo n rm 6.0.0     # replace number with version of Node that was installed
      sudo npm uninstall -g n

You may need to restart your terminal to see the updated node version.

Found in David Walsh blog

INstallatie van deze github repository:

git clone https://github.com/hrobben/symdemo.git

doe dit in je html directory bij Xampp = c:\xampp\htdocs

er word dan een directory in htdocs aangemaakt met de naam "symdemo"

in de dosbox ga je dan naar:  cd \xampp\htdocs\symdemo

voer vervolgens uit:
- composer install
- yarn install en/of npm install  (om webencore te installeren, phpstorm doet dit vaak automatisch vragen aan gebruiker)

Eventueel mag je ook computer upgrade gebruiken.

laatste toevoeging is "Datatables"

Om deze goed te laten werken, kan het zijn dat je ook "npm run build" of "yarn watch" opnieuwe moet laten runnen.