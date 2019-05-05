# OSECMS
Open Source Educational CMS.This software is not intended for production environment. It's here only for educational reasons. You 're welcome to contribute or give suggestions that will make all this better for all.
------------------------------------------------------------------------------------------------------------------------


OSECMS is currently being developed to educate myself the following concepts, in order to create my own CMS: PHP Composer, PHP Autoloader, PSR-4, PDO, MVC OOP logic, Routing, SEO friendly URL's structure and implementation of encryption.

The reason for making one more "Simple CMS" from start, is because i want to study the aforementioned concepts, and although i did search thoroughly to find a CMS that implements all of the above, to get an example, i didn't found anything. 

So, the plan here is to not just write some classes and add some, 1 or 2 lines of comments but also do my best to fully explain every concept and also provide links for further studying about all used concepts. 
I'm adding a Wiki page to this project, in which there will be notes and links for Studying material as the OSECMS proceeds. 
Check this for the Wiki http://wiki.osecms.com  and at http://osecms.com the live CMS.

For the time being this is a personal project aiming to help mastering these topics, and maybe help others too. :) 
------------------------------------------------------------------------------------------------------------------------


So, lets dive in!


This project is being made on a Linux Mint 19.1 Tessa, is using PHP 7.1.23 (cli) (built: Feb 22 2019 22:08:13) ( NTS )
Copyright (c) 1997-2018 The PHP Group and PhpStorm a commercial, cross-platform IDE for PHP built on JetBrain's IntelliJ IDEA platform.
So make sure that you have PHP 7.1.23+ installed in your system and PhpStorm preferably or any other PHP IDE you prefer.

I will list all the software libraries and frameworks used, the moment they will be used and not before. This way we can make small understandable steps and then move on.
This solution currently is incomplete. In software development we should try to start by making an MVP (minimum viable product). This means that we may, at first, purposely leave out functionality that isn’t absolutely necessary and proceed as needed. 

The 1st step to begin is to open up PhpStorm's Terminal and create a new empty project folder that will contain all of the software. Here the use of Terminal goes as needed and learning all essential commands for managing any professional software development project. 

So, start up PhpStorm and navigate to your Project's Directory. 
Open Terminal and make a new directory named "OSECMS" in our case.
#mkdir OSECMS  

Enter the new directory
#cd OSECMS 

Initiate a new Git local repository.
#git init

Make a new file called index.php
#touch index.php

And at this point we will have to make a few decisions like to use PhpStorm's IDE environment to work with our project, instead of doing everything from the Terminal, which would include the working knowledge of Vi, or Vim, or Nano, or Emacs, or whichever else terminal Text editor you name.
So, open the file index.php which is listed inside the Project's folder and add the following code:
#<?PHP
# 
#echo "foo";

Next step we make the index.php file the one and only entrance point to the application.
