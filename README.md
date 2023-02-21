# Shell Snake

Hello!

This is the classic game of snake.

I have tried to write it so that it will run on most shells and so that it does not rely on many other applications. In other words, I'm trying to make this game portable and light.

Currently, this program relies on:

- stty. I use this for handling input and getting terminal dimensions.
- the $RANDOM variable. I could use awk to be more POSIX compliant,
  but the $RANDOM variable feels lighter.
