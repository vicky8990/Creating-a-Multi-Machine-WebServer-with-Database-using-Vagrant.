# Creating-a-Multi-Machine-WebServer-with-Database-using-Vagrant.
Using Vagrant to manage the Virtual Machine 

To Run this Vagrant File need to install the Vagrant. https://developer.hashicorp.com/vagrant/tutorials/get-started/install

1) Vagrant need Virtual Box to create a Virtal Machine and to Run it.
2) To run this Use POWERSHELL and run it as adminstartor
3) command :-   1) vagrant up  - it will start installing the need file.
                2) vagrant reload web  - Run Web and update

4) If you are not able to get the output try this a manully this command-      vagrant ssh web
5) After this update the vagrant file by using this command-          vagrant provision web         -It will update all required file for apache and try to ping it, This will restart the apache server.

7) finally use this url to check the output-      http://localhost:8080



------------------------------------------------------------------------------------- Enjoy --------------------------------------------------------------------------------------------------


