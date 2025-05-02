

![Devops1](https://github.com/user-attachments/assets/c1df9c98-dd96-4ae2-b817-10d80303b2b9)


#  cd commnds pratice

cd    # Moves you to your home directory

cd <directory_name>   # Moves you to specified directory

cd ..   # Go to the Parent Directory or one directory back
{Example}
cd /home/user/raja/nisahnt
cd ..  # we will go to the /home/user/raja

cd ~   # Move you to the home directory

cd -   # Switch back to the previous directory

cd /   # Change to the root directory

cd ../..   # Move up two levels in the directory tree or move two directory back
{Example}
cd /home/user/raja/nishant
cd ../../  # we will go to /home/user/

cd !$   # This is a special variable in the shell that refers to the last argument of the previous command
{Example}
mkdir raja
cd !$ # we wlii go to the raja

 cd && <another_command>   # change directory and then run the command

cd -P  # is useful for changing to the physical directory and avoiding the symbolic link structure
{Example}
ln -s raja nishant
cd -P nishant  # take you to raja
