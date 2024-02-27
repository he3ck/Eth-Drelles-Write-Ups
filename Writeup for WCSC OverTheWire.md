Bandit5: 
cd to the "inhere directory"
find -size 1033c
	use to find file thats 1033 bytes
cat ./maybehere07/.file2
	use to get password

Bandit6:
cd /
	cd to home directory
find -size 33c -group bandit6 -user bandit7 2>/dev/null
	find file thats 33 bytes owned by bandit7 in group6 then dump errors
cat ./var/lib/dpkg/info/bandit7.password

Bandit7:
ls
	find files
cat data.txt | grep "millionth"
	find string that contains millionth

Bandit8:
ls
	find files
sort data.txt | uniq -c | grep -w "1"
	Sort file, count how many times each line occurs, find the only line that appears once

Bandit9: 
cat data.txt | grep -a "=="`
Locate flag as 4th occurance
	