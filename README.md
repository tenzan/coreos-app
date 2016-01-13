# README

This will fire up one single machine.

_Note_: In production `config.rb` and `user-data` are included in `.gitignore`, but for the testing purposes they're not there

## Steps

1. `git clone https://github.com/tenzan/coreos-app`

2. `cd coreos-app`

3. `vagrant up`

4. Connect to the machine: `vagrant ssh core-01 -- -A`

# TODO

Fire up 3 docker containers using 3 files from the `share` folder, so that 3 containers will interact with each other and show the output of the `index.php` on the browser.

## This has been forked from here
https://github.com/coreos/coreos-vagrant.git
