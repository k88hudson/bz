# A command-line tool for Bugzilla

### Open a ticket by number

`bz t12345`

Opens ticket 12345

### Open a ticket referring to the current branch

`bz open`

Opens bugzilla ticket based on your current branch name (bug 12345, t12345, etc.)

### Create a new bug

`bz new [-me] -c {{Component}} -m "{{Your bug title}}"`

New ticket assigned to me, in Webmaker:Webmaker.org with text 'New Ticket!!'

Component shortcuts:

* `wm`: Webmaker
* `popcorn`: Popcorn Maker
* `thimble`: Thimble
* `valet`: Make Valet
* `login`: Login


### Open your dashboard

`bz dashboard`

