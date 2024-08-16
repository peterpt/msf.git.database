# msf.git.database

msfdb to be used in metasploit-framework from github
this msfdb was extracted from metasploit debian package and
it works perfectly on creating the databases on postgresql
and where you can connect ahead with armitage .

armitage login data set by default :
- port : 55553
- ip : 127.0.0.1
- login : msf
- password : msf3

Notes : your git metasploit must be in /usr/share/metaploit-framework

![Alt text](https://github.com/peterpt/msf.git.database/blob/main/Armitage_001.png "Armitage")

# to change the default password
- you must edit line 75 in msfdb and change msf3 to whatever you want inside the double cotes
![Alt text](https://github.com/peterpt/msf.git.database/blob/main/pass.png "Change Password")

  
