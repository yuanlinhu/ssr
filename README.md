wget --no-check-certificate https://raw.githubusercontent.com/teddysun/shadowsocks_install/master/shadowsocksR.sh

chmod +x shadowsocksR.sh

./shadowsocksR.sh 2>&1 | tee shadowsocksR.log



#bbr

wget --no-check-certificate https://github.com/teddysun/across/raw/master/bbr.sh && chmod +x bbr.sh && ./bbr.sh


sudo yum install httpd -y
sudo systemctl start httpd.service
sudo firewall-cmd --zone=public --permanent --add-service=http
sudo firewall-cmd --reload
cd /var/www/html
sudo dd if=/dev/zero of=500mb.zip bs=1024k count=500









#ssr example
Congratulations, ShadowsocksR server install completed!
Your Server IP        :  149.248.1.98
Your Server Port      :  3333
Your Password         :  123
Your Protocol         :  origin
Your obfs             :  plain
Your Encryption Method:  aes-256-cfb

Welcome to visit:https://shadowsocks.be/9.html
Enjoy it!
