[<<< Previous](examples.md) | [Next >>>](gitconfig.md)  
# Review of the Command Line

In this session, we'll be using the command line (terminal, bash) from the Command Line workshop. We'll also use your text editor and your browser. We'll be moving between these three spaces throughout the workshop. You may want to use (command + tab) or (ctrl + tab) to move quickly between the three windows on your desktop.

To begin with, we'll review some command line basics, including navigation. For more on the command line, review the [materials for the command line session](https://github.com/DHRI-Curriculum/command-line).

## Accessing the Terminal

### Mac OS

Press the space bar and the command key at the same time and type `terminal`. Press `Enter`.

### Windows

Press the Windows button on your keyboard. When the search menu pops up, type `git bash` and press `Enter`.

## Practice Navigating the Command Line

In this session, we will be making a syllabus and using Git to keep track of our revisions. Let's create a Git project folder

	cd <directory-name> 
	
will let you navigate inside a directory of your choosing.

Type 

	cd Desktop
	
and hit `Enter`. This will change your current working directory from `/Users/<your-name>` to `/Users/<your-name>/Desktop`.

To check your current directory, type

	pwd
	
Try this now to make sure you're in your Desktop directory.

Now, use 

	cd ..
	
to go up one directory. In this case, this will take you back to your home directory.

Practice going back and forth between your Desktop and your home directory.

When finished, go to your Desktop folder and check that you're there with `pwd`.

## Making a Git Project Folder

If you've worked through the command line session, you should see a `projects` folder on your desktop. Navigate into it with

	cd projects
	
If you don't have a projects folder on your desktop, create one with

	mkdir projects

From `Desktop`, navigate into your `projects` folder. Then create a `git-practice` folder with the below command:

	mkdir git-practice

Enter the new `git` folder with

	cd git-practice

At this point, when you type `pwd`, your folder structure should look like this:

	/home/<username>/Desktop/projects/git-practice

[<<< Previous](examples.md) | [Next >>>](gitconfig.md)  
