infinite
========
apt-get install git-core
cd /opt
git clone https://github.com/sysopcorner/infinite.git

#install chef-solo
curl -L https://www.opscode.com/chef/install.sh | sudo bash


#run chef
chef-solo -c solo.rb -j node.json
