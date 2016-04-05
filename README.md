git-ssh---git-github.com-wprl-sports-mashup-api
===============================================

git-ssh---git-github.com-wprl-sports-mashup-api.git test




A test for  setting up a vagrant box with Ubuntu and Node.js MongoDb Redis and some other modules

First Test:

On my local machine with Vagrant set up  and using the Git Shell console (it has a ssh client)
Ran Vagrant Up  it installed the ssh files Node.js  MongoDb ect via the ssh files
Then  ran vagrant ssh
Then changed the directory 'cd /vagrant'
Then ran  'test.js' node test     and it displayed test in the console
Then ran   'test2.js' node test2  and it displayed 'server started' in the console
Browsed to localhost:3000 on my browser and it displayed 'Hello World'
On network settings it showed being connected to the internet over a virtual network 


Second Test:

Cloned the github repo
git clone git@github.com:scotty845/git-ssh---git-github.com-wprl-sports-mashup-api.git
To a folder on my local drive
Using the Git Shell console (it has a ssh client)
Ran Vagrant Up  but it did not install the ssh files Node, MongoDb,ect  (error message was permission denied must be admin I tried this in the root directory but  it also failed and displayed the same error)
Then did a NPM install ( had to use ssh syntax )
Then  ran vagrant ssh
Then changed the directory 'cd /vagrant'
Then ran 'test.js' and it displayed 'test' in the console
Then ran 'test2.js' and it displayed 'server started' in the console
I browsed to localhost:3000 on my browser and it displayed 'Hello World'
on network settings it showed I was connected to the internet over a virtual network



