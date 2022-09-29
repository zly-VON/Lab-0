*Lab 0, OOP*


## Task 1: 
I downloaded and dual-booted Ubuntu 22.04.1 along Windows 10. The proof is the sccreenshot 'ubuntu.png'.


## Task 2:  

Using the command  line I installed zsh
	
	sudo apt install zsh
	
Then I checked that it was corectly installed

	zsh --version
	
I made it default and checked with

	echo $SHELL
	
Next I installed curl to be able later to install oh my zsh
	
	sudo apt install curl
	
And I installed oh my zsh with

	sh -c "$(curl -fsSL https://raw.github.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"
		
I installed gcc with

	sudo apt install gcc

For the editor I installed VS Code

	sudo snap install --classic code

And also git with

	sudo apt install git
		
All the proofs are the screenshots taken during the proccess, they are in the 'task 2' folder.


## Task 3:

Using the command line I created a c file called hello.c

	gedit hello.c
		
Compiling with gcc and execute it

	gcc -o hello hello.c
	./hello
		
To compile with Makefile, I firstly installed it with

	sudo apt install Makefile
	
Then I created a Makefile and edited it

	gedit Makefile
	hello: hello.c
		cc hello.c -o hello
		
In the command line I compiled the c file with comand 

	make
	
And then executed it with

	./hello
			
As previously stated, all the proofs are screenshots taken during the proccess, they are in the 'task 3' folder.

	
Lastly, I created a repository in git, added all the files, commited them with comments for all files individually, and pushed them into the GitHub repository

	git init
	git add (file name)
	git commit -m "comementary"
	git remote add origin (link)
	git push -u origin master
