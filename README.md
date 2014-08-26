README
==========

We are using deployed instance of openEdx as baseline for development.  However, the initial size of deployed version takes ~2GB space with everything , we can't check in all into the github.  

So we will only check in the modifed files in this repository.

For example:

If you change /edx/app/edxapp/edx-platform/setup.cfg, please check in(add/modify) a file and folder under <git_root_folder>/edx with the exact same folder structure:

For our development environemnt, it looks like :

/root/workspace/courszilla/edx/app/edxapp/edx-platform/setup.cfg


So, anyone can easily apply the new files to their deployed instance. 

