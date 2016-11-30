Question 1: How would I describe the command line to a lay person?

The command line is a system that allows a user (e.g. the person using the computer) to speak directly to the computers operating system. It uses basic words to tell the computer what we want it to do. For example, create a new folder or file, or move through those folders.

Question 2: List 10 terminal commands and in plain english (i.e. with minimal technical jargon) describe what they do.

1. cd - Change directory. A directory is, in basic terms, a folder. By using the command 'cd' and the name of the folder/directory we can move to that specific folder. We can move upwards in the hierarchical order by using .. after cd (e.g. cd ..). We can move through multiple directories through using an extended path name. For example, if I have a folder within my directory called apples, and a folder inside that called bananas - I could move to that folder directory by typing "cd apples/bananas" into the command line.

2. mkdir - A stated before, a directory is a folder. mkdir is simply short for "make directory". To "make" a "directory" I would use the command mkdir <new-directory-name> (e.g. mkdir oranges would create a new directory called oranges ).

3. pwd - pwd stands for "print working directory". This prints on screen the path of our current working directory (the directory we are currently in).

4. touch - this allows us to make empty documents. For example, if I wanted to make a text file called "pears". I would type the command "touch pears.txt" into the command line.

5. ls - this displays what files and folders present in your working directory.

6. rm - this command will allow you to remove a file from your working directory. For example, if I wanted to remove a file called "kiwi.txt", I would type "rm kiwi.txt"

7. "rm - r" is similar to the rm command but is used to delete a directory. For example, if I wished to delete a directory called "mango", I would type the command "rm -r mango"

8. * - * is used for wildcard matching. The * is known as the star wildcard and can be used to represent zero or more characters. This can be helpful in a number of areas. One example would be if I wanted see what files I had in my working directory that ended with ".md" and did not want to have to see the various other directories or files present. To do this I would type "ls *.md" and this would display only files ending in ".md". Remembering that the ls allows us to list items.

9. cp is a command used to copy files or directories. When using the cp command it is important to remember that files and directories are always copied from the source to their new destination. For example, if I wished to copy a file, kiwi.txt, from my current working directory apples, into the destination folder of bananas, I would use the command "cp kiwi.txt bananas".

10. cat - the "cat" command is used for three different functions in relation to text files. These are displaying the file, stringing together/combining copies of files and creating new ones. At the level I am currently at, I have used the command "cat command-line.txt" to view the text inside this file from within terminal. Because some txt files can be too large to read all at once, the "less" command can be used instead to scroll through the text, one screen at a time, using the spacebar key (e.g. "less command-line.txt").
