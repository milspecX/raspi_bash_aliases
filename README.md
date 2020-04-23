# Raspberry Pi Bash Aliases
Some commonly and useful aliases to be included into my standard Pi setup.

## Getting Started
Download and save into .bashrc directory. Then add the following to .bashrc

```console
if [ -f ~/.bash_aliases ]; then
  source ~/.bash_aliases
fi
```

Logout and log back in or load :

```console
source ~/.bashrc
```



### Here's the list so far:

```console
alias temp = '/opt/vc/bin/vcgencmd measure_temp'
```







