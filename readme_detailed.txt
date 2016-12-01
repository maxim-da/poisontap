#To install nodejs on server:
curl -sL https://deb.nodesource.com/setup_7.x | sudo -E bash -
sudo apt-get install -y nodejs
sudo apt-get install -y build-essential

#Install websocket (I did it in previousy cloned poisontap directory):
sudo npm install websocket

#Kill apache listening port 80
sudo netstat -lnpt
sudo kill (Apache pid)

#git
apt-get install git-all
git clone https://github.com/maxim-da/poisontap
git status
git add .
git commit
git push origin master

#screen
screen
#ctrl+a then d to detach
#show all sessions
screen -ls
#reattach
screen -r
