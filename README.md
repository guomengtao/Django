# Django
First Learning Django and Python Notes


This week I try to developent a Django project with a team ,I am a new to user Python and Django.
I leanged a lot , I meeting a lot problems ,try record it on here.

1. on the Ubuntu install pip3

sudo apt-get install python3-pip

this can not run ,use the

sudo apt-get update

change the download library ,then run again its working

# install Django 
  when runed the : python -m pip install Django 
  
  then runing :django-admin startproject mysite
  
  It is still show a bad news:
      
  Command 'django-admin' not found, but can be installed with:
sudo apt install python3-django

 
  So, run the sudo apt install python3-django it is working
  
  Who is the right comman? A Or B ,What different by these ?
  A: python -m pip install Django
  B: sudo apt install python3-django
## runing Django 

I running at Ubuntu Multipass ,this could run windows/macOS ,let we use same setup ,even win/macOS

vim edit settings.py check "a" to edit the file

ALLOWED_HOSTS = ['*'] // if you are in dev or docker

set the ip

use command : ip a /address to see the ip adderess

