# Web-Security

T1 attack is basically defining how XSRF(cross site request forgery) attack works. In this case i used a dummy GaTech payroll site where, i crafted a web page and set the account and routing number of my choice, becasue a person was logged in already and session was active. In this way he/she redirected to my crafted page.<br><br>
T2 implements XSS(cross site scripting) attacks. Basically i crafted a GaTech payroll site. But this time i used my own code and also initialize some script inside that html. So as soon as a person logs in i will get an email with his/her username and password. The attack happened cause there was no input validation in the payroll site, and all the html tags were allowed.<br><br>
T3 implements SQL Injection attack. I created a HTML page where i used a username  that was registered in a database. Since there was a vunerability in the given database and it was only checking one thing to be true in order to login. So i put a script in a way where when a user logs in with his user name and its registered in the database, it will skip the password step and logs him/her in.

****************************IMPORTANT_NOTICE*******

GaTech payroll site was written in PHP and i was not allowed to put it over here for confedentiality
