Breakup
=======

Couple is a relationship app that strives to "keep all your moments private & make your memories last forever." (https://couple.me/)
The problem here is that even though all my moments are private, where are they stored?

This small GitHub repo hopes to provide you with the tools to scrub your data clean from Couple's database, all the while
saving all those precious moments you collected over the relationship lifetime with your significant other.

#### What We Know
* Couple stores their user's database on Amazon S3 servers
* Data is also backed up locally onto the device using a .sqlite database
* We can extract data from this database, and output it whichever manner we see fit (to a new app etc.)
