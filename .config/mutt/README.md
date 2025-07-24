# Mutt dotfiles




# Key Bindings

All default keys are unbound to remove random, unwanted bindings and commands. Therefore all bindings are explicit.

Press `?` inside Mutt to see available keybinds for your current context.

### General

* `q` exit/close/back
* `<escape>` abort command
* `?` help
* `/` search
* `j` scroll down 
* `k` scroll up
* `gg` first item/top
* `G` last item/bottom
* `<return>` open/select/confirm
* `<tab>` trigger auto-complete
* `n` (when searching) search next
* `Shift-n` or `p` (when searching) search previous
* `Ctrl-u` scroll half a page upwards
* `Ctrl-d` scroll half a page downwards
* `Ctrl-n` next unread message
* `Ctrl-p` previous unread message
* `zz` center screen on current selection (similar to Vim)
* `zt` center screeen at top of current selection (similar to Vim)
* `zb` center scren at bottom of current selection (similar to Vim)

### Index-specific

* `<left>` or `<right>` or `h`  toggle thread open/collapse 
* `g` `i` go to inbox
* `g` `s` go to sent items
* `g` `d` go to drafts
* `g` `a` go to archive
* `g` `Shift-s` go to spam
* `f` change folder
* `Ctrl-b` toggle sidebar
* `Ctrl-j` sidebar next item
* `Ctrl-k` sidebar previous item
* `Ctrl-o` open current sidebar item
* `<space>` flag current email (toggle)
* `t` tag current email (toggle)
* `T` tag current thread (toggle)
* `Shift-m` `i` move email(s) to inbox (works on tagged emails)
* `Shift-m` `s` move email(s) to sent items (works on tagged emails)
* `Shift-m` `d` move email(s) to drafts (works on tagged emails)
* `Shift-m` `a` move email(s) to archive (works on tagged emails)
* `Shift-m` `Shift-S` move email(s) to spam (works on tagged emails)
* `Shift-c` `i` copy email(s) to inbox (works on tagged emails)
* `Shift-c` `s` copy email(s) to sent items (works on tagged emails)
* `Shift-c` `d` copy email(s) to drafts (works on tagged emails)
* `Shift-c` `a` copy email(s) to archive (works on tagged emails)
* `Shift-c` `Shift-S` copy email(s) to spam (works on tagged emails)
* `d` mark current email(s) for deletion (works on tagged emails)
* `u` undelete email(s) (works on tagged emails)
* `Shift-d` quick delete current email(s) (works on tagged emails)
* `Shift-a` quick archive current email(s) (works on tagged emails)
* `l` add/edit label
* `\` filter (limit) current mailbox (see [filters cheat sheet](https://github.com/fredrikhl/cheatsheets/blob/master/mutt-limit.md))
* `x` clear current filter/limit
* `Ctrl-i` only show flagged messages (press `x` to clear)
* `Shift-l` filter by label
* `+`  link current thread with a tagged thread
* `c` compose new mail
* `Ctrl-r` recall draft (postponed) message
* `r` reply to message
* `Shift-r` reply all
* `Shift-f` forward message
* `v` view email attachments
* `|` pipe current email to shell command
* `Ctrl-a` mark all messages as read
* `$` sync mailbox to local filesystem
* `o` remote sync current account (send/receive from IMAP)

### Pager-specific (email view)

* `Shift-j`  next email
* `Shift-k`  previous email
* `r` reply to message
* `Shift-r` reply all
* `Shift-f` forward message
* `v` view email attachments
* `|` pipe current email to shell command
* `Ctrl-l` call urlscan to show all links in the current email
* `Shift-a` (when viewing a calendar invite) respond to invite

### Attachment List

* `s` save current attachemnt to ~/Downloads

### Compose-specific (the confirmation screen before you send an email)

* `y` send 
* `a` attach file
* `p` postpone message (save to drafts)
* `e` edit message
* `t` edit "to" field (recipient)
* `f` edit "from" field (sender)
* `s` edit subject
* `c` edit "CC" field
* `b` edit "BCC" field

