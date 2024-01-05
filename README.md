# ssh_commands

###To generate key 
ssh-keygen -f C:/Users/LENOVO/vagrant/id_rsa

###for generated keygen file in particular location
ssh-keygen -t rsa -b 2048 -f path/test

####output we can see two files private and pub ( public) public key we add to authorized key and use private to try ssh

example :- ssh-keygen -t rsa -b 2048 -f C:\path\to\your\directory\my_key
