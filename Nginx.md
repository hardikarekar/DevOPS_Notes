* Update your system  
      * `dnf update -y`  
* Install **nginx**  
      * `dnf install nginx -y`  
* Start nginx  
      * `systemctl start nginx`  
* Enable nginx to start on boot  
      * `systemctl eable nginx`  
* Verify installation  
      * Open your browser and enter your EC2 instance’s public IP. You should see the default Nginx welcome page.