# shutuprecall
A simple batch script to disable MSRecall

To run the batch file:
1. Save the file to your desktop (or wherever you'd like).
2. Right-click on the file and click "Run as administrator".
3. Click 'Yes' when prompted, and a CMD window will briefly appear.
4. Restart your computer after running the script.

And you're done.  Re-run the script as needed (e.g., a Windows update re-enables MSRecall).

# Q/A
### Why do you need a whole batch file to disable MSRecall?
You don't.  You can just copy the command from the batch file and run that in a CMD in administrator mode, if that's what you prefer.

### So then why make it?
Because I can. To protest (in vain) against MSRecall. Etcetera Etcetera.

Also, because I know there are people who get nervous about having to use anything related to the terminal/CMD.  This gives them an easy way to disable it without having to do anything CLI-related.

### Why is this here when MSRecall isn't even out on most machines yet?
See previous question. Just because it's not here yet doesn't mean it won't be soon.

### Will there be updates?
Dunno, probably? It depends on if something happens and the command becomes unusable.  

I also thought about looking into how to make the command run at start-up, but since you have to restart anyway to completely disable it, it's easier to just run the script and reboot manually.

Another potential update could be making the command conditional (if MSRecall is enabled, then yada yada).  Again, probably just easier to run the script as-is.

### I don't trust random batch scripts in repositories I don't know
Good, you shouldn't.  If you think I hid some super-duper-uber secret CMD command in the file (somehow?), just copy/type what you see in the batch file into an admin CMD prompt.  
