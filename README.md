# cloudflare_bash_admin
Manage your Cloudflare from Bash


$ ./cloudflare_bash_admin 

Please Select for domain.com :

1. List and select another Domain name
2. List and change DNS Records
3. Create new DNS Record (Not DONE)
4. Add new Domain (Not Done)
0. Quit

Enter selection [0-4] > 


--------------------------------
1. List and select another Domain name

Domains in your Cloudflare account:
 
domain.com 
domain2.com
...
 
Enter the domain name (q for back)> 
--------------------------------


2. List and change DNS Records

domain.com A 123.123.123.123
www.domain.com A 123.123.123.123
-----------------------------------------------------------------------------------------------------------------------------
Enter the subdomain name (q for back)> www.domain.com A 222.222.222.222

Changing record for www.domain.com to 222.222.222.222

true
....
