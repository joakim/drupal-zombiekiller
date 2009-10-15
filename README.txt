/* $Id: README.txt,v 1.1 2009/10/13 10:40:18 dixon Exp $ */

This module kills zombies. Why? Because someone said "Bet Drupal can't kill
zombies". How wrong can you be.

Zombie killer lets you kill (reap) zombie processes on UNIX-like systems,
using either a shovel (kill -s SIGCHLD) or a sledgehammer (kill -9). In order
for this to actually work, the user running apache must have the ability to
"kill" processes.

This project was just for fun. But who knows, it might actually even work!


WARNING:
You should not use this module unless you understand the consequences of
killing processes. Killing zombie processes or their parents can cause serious
trouble. So think twice before going on a killing spree.


The blog post that started this sillyness:
http://www.sheenadonnelly.net/blog/archive/2009/challenge-my-father

Read more about zombie processes on Wikipedia:
http://en.wikipedia.org/wiki/Zombie_process

Or on this aptly named blog:
http://zombieprocess.wordpress.com/what-is-a-zombie-process/
