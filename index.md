Hello World!

# Week 1 Lab Report
## Tutorial for all future CSE 15L students:

- **Installing VS Code:** I did not do this step because I previously had VS Code installed on my Mac from when I took CSE 11. However, for those who do not have VS Code downloaded on their device, simply navigate to their [website](https://code.visualstudio.com/) and follow the instructions. When I launched VS Code, everything seemed to be working smoothly. This is what I saw on my end when I launched: 

![Image](https://github.com/igerth/cse15l-lab-reports/blob/main/Screenshot%202023-01-12%20at%2012.20.56%20PM.png?raw=true)

- **Remotely Connecting:** First thing was to open a terminal in VS Code. I was a bit confused and asked for help on this part. Simply navigate to the top of VS Code where it says "Terminal," and select "New Terminal." I inputted the following command into the terminal, with the zz replaced by my CSE 15L account id:
```
$ ssh cs15lwi23zz@ieng6.ucsd.edu
```
I was met with a few messages after this, and simply inputted yes to what the terminal asked. After, I was remotely connected and this is what my terminal looked like:

![Image](https://github.com/igerth/cse15l-lab-reports/blob/main/Screenshot%202023-01-12%20at%2012.31.19%20PM.png?raw=true)

- **Trying Some Commands:** Last step was to try a few commands once remotely connected, like `cd`, `ls`, `pwd`, `mkdir`, and `cp`. I chose to run:

```
ls /home/linux/ieng6/cs15lwi23/cs15lwi23abc
```
I replaced the `abc` with both another group mate's CSE 15L id and mine. When I tried to list the files in my group mate's directory, it returned `Permission denied`. When I tried to list the files in my directory, however, it returned `hello.txt  per15`. This is what that looked like in my terminal:

![Image](https://github.com/igerth/cse15l-lab-reports/blob/main/Screenshot%202023-01-12%20at%2012.40.11%20PM.png?raw=true)

Other interesting commands I tried out were the `cd` and `pwd` commands. I would try changing my directory, and then after would print working directory to see if my directory did indeed change. I thought the `cd ~` command was really useful. Use this if you need to change the directory back to your home directory. 

## Summary:
In this lab, I learned how use a terminal in VS Code to remotely connect to a remote server at UCSD over the internet. I ran some different commands that I saw in lecture and learned how to publish my findings on GitHub and GitHub pages. 
