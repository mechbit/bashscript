# bashscript

----------------ISPCONFIG3 SERVER MOVE-----------------

# Migrate ISPConfig 3 installation from one server to another
# This script should run on the final/destination ISPConfig 3 server
# You must first install the same ISPConfig on the destination server
# and make sure to create all the users from the previous installation
# (ISPConfig creates users for each client and web page)

 # TODO:
  # You should update ISPConfig MySQL Password to match your new server's, as it's stored in
  # several ISPConfig files (it's a faster approach than updating the password in all those places)
  # Enter MySQL on the destination server and run:
  # SET PASSWORD FOR 'ispconfig'@'localhost' = PASSWORD('YOUR NEW ISPCONFIG MYSQL PASSWORD'); 
  # You should also make shure all the tables on the destination server are clean:
  # mysqlcheck -A --auto-repair

Download th script:

wget -O - https://raw.githubusercontent.com/mechbit/bashscript/main/ispconfig3-server-move.sh

Change permission

chmod +x

Execute the script :

./ispconfig3-server-move.sh

Enter 1,2,3.....7 for each step

----------------ISPCONFIG3 SERVER MOVE-----------------
