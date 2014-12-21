Vagrant setup
=============

The main goal of this repository is to provide simple Vagrant setup. 

This repository contain scripts for:
- adding box: local and remote
- config sudoers for: linux fedora, linux ubuntu, osx 
- install plugin: vbguest

It also contains 'Vagrantfile' with its associated 'Personalization.dist' file example.

They are in separated 'vagrant' folder, to allow you easily copy only this folder to your project.
Then you can copy 'Personalization.dist' to 'Personalization' file, and modify only the latter one, because only this file, changes from project to project.
After all, you will be able to run 'vagrant up' command.
