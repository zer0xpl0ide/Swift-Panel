# SwiftPanel
         
         
         Install SwiftPanel on Centos
         yum install redhat-lsb
         wget https://github.com/zer0xpl0ide/Swift-Panel/raw/master/SwiftPanel.zip
         chmod +x *
         ./install.sh
         
         Open DataBase
         mysql -u root -p  (Write you password)
         CREATE DATABASE zeropanel;
         CREATE USER 'zeropanel'@localhost IDENTIFIED BY 'gpanel1';
         GRANT ALL PRIVILEGES ON zeropanel.* TO 'zeropanel'@localhost;
         use zeropanel;
         exit
         
         Info DataBase
         hostname - localhost
         username - zeropanel
         name - zeropanel
         password - zeropanel
         
         
        Add info to configuration.php
        And go youdomain.com/install
        And you finish install go /var/www/html and remove folder " install "
        Thanks you
        
Problem? : contact in fb.com/zer0xpl0ide
         
        
         
         
         
        
