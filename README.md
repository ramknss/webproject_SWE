create instance 

with all traffic in the advanced network settings 

sudo apt install update 
sudo apt install upgrade 
sudo apt install docker.io
git clone https://github.com/saiguptha2003/webproject_SWE
sudo -i
cd /home/ubuntu
cd webproject_SWE
vim index.html 
go to name and change name and roll by pressing i 
and press esc and then wq and enter 
cat index.html #to check file edited or not
docker build -t my-apache2 .
docker run -d --name containername -p 8080:80 my-apache2 
https://publicipaddress:8080
