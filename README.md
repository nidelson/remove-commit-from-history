# remove-commit-from-history

Steps to reproduce:

1. git clone
2. first commit
3. git add giant file
4. git add print screen (du -hc .)
5. git rm giant file

Disk usage:

> du (32M)

Step to fix

1. execute bfg in mirror repository
2. git push

Disk usage:

> du (200K)

All ready!

Clone the repository again.
