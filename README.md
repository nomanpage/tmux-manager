# tmux-manager - unixify tmux as it should be. 

I made this little manager because typing full tmux commands was too much of a hassle. At work I spend hours in the Unix terminal creating and switching sessions between projects and I needed tmux to work more like normal Unix commands. This started out as a tool just for me but I ended up using it way more than I expected.

You can name the manager whatever you like. It’s called "lt" (launch tmux) here but that’s just what I’ve used personally.

With the script named "lt" you can do the following:

```console
lt <session>              attach or create
lt rm <session>           remove session
lt mv <old> <new>         rename session
lt ls                     list sessions
lt nuke                   remove all sessions
```


More commands are planned to be added in the future. 

### How to use
- Clone this repo or just copy the raw file from Github and paste it into a file of your own on your machine. 
- Make the file executable.
- Put it in your path. 

