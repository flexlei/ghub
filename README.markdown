Git utility for pretty CLI output of github info

Things it currently does:

* List issues for a project in open/closed and by milestone

Things it will eventually do:

* Anything the api supports and makes sense to have on the CLI

Usage

* Inside a github repo: git ghub <command> [<command_arg>, ...]
* Outside a github repo: git ghub <user> <repo> <command> [<command_arg>, ...]

Commands

* issues
** git ghub issues [open,closed,milestone <milestone #>] [detail]
** [detail] is whether to expand issue descriptions or not

Requires

* PHP >= 5.3
* Git... obviously

Installation (for now)

* Clone into your bin directory
* symlink git-ghub into ~/bin/
