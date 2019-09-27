# openstack-meetup

This Lap will allow you to install httpd apache server inside Centos Machine

## Using Apache Server in Openstack VM  
1. Install httpd server `sudo yum install httpd`
2. Activate the server `sudo systemctl start httpd`
3. Verify server is running `sudo systemctl status httpd`


# Hello World Application

1. Go to the following directory `cd /var/www`
2. Create new file called `index.html` with the following content
```
<html>
  <header>
    <title>Openstack Infra</title>
  </header>
  <body> Hello From Openstack</body>
</html>
```
3. Use `vim` or `vi` editor
4. Restart the server `sudo systemctl restart httpd`
5. Visit the website using Floating IP attached to your instance
