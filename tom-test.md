# Test file

Hello from the tom-test file


This is a second message

alskdjfalskdfj


[alias]
	ls = log --color --graph --abbrev-commit --decorate --pretty=format:'%C(red)%h%C(reset) -%C(yellow)%d %C(reset)%C(dim green)(%cr) - %C(dim black)%an:%C(reset) %s %Creset'
	ll = log --color --graph --abbrev-commit --decorate --numstat --pretty=format:'%C(red)%h%C(reset) -%C(yellow)%d %C(reset)%C(dim green)(%cr) - %C(dim black)%an:%C(reset) %s %C(bold blue) %C(reset)' 
	lds = log --color --graph --pretty=format:'%Cred%h% %ad%Creset -%C(yellow)%d%Creset %s %Cgreen(%cr) %C(bold blue) %Creset' --abbrev-commit --decorate --date=short
	grep = !git ls-files | grep -i
	ltg = describe --tags --abbrev=0
	unpushed = log --branches --not --remotes --color --graph --pretty=format:'%Cred%h%Creset -%C(yellow)%d%Creset %s %Cgreen(%cr) %C(bold blue)%Creset' --abbrev-commit
	visual = !gitk
	la = !git config -l | grep alias | cut -c 7-
	lg = log --graph --abbrev-commit --decorate --all --format=format:'%C(red)%h%C(reset) - %C(dim green)(%cr) - %C(dim black)%an:%C(reset)%C(reset) %C(black)%s%C(reset) %C(bold yellow)%d%C(reset)' 
[