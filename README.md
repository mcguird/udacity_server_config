# udacity_server_config

i. The IP address and SSH port so your server can be accessed by the reviewer.
52.212.131.161 SSH port 2200

ii. The complete URL to your hosted web application.
http://52.212.131.161/

iii. A summary of software you installed and configuration changes made.
* Installed virtualenv and put all the flask specific installs in there; such as requests, sqlalchemy, oauth2 and flask itself.
* Installed libapache2-mod-wsgi and postgresql
* Created a config file for udacity_catalog.conf in /etc/apache2/sites-available and set up my python-home for wsgi within it while also pointing to the wsgi app to run.
* Used ufw to lock down the ports and start up the firewall
* Set ssh permissions in sshd_config

iv. A list of any third-party resources you made use of to complete this project.
* https://blog.miguelgrinberg.com/post/the-flask-mega-tutorial-part-i-hello-world
* http://flask.pocoo.org/docs/1.0/deploying/mod_wsgi/
