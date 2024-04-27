# Metasploit-for-reconnaissance
Metasploit for reconnaissance in pentesting

# AIM:

To get introduced to Metasploit Framework and to  perform reconnaissance  in pentesting .

## DESIGN STEPS:

- `Step 1:` Install kali linux either in partition or virtual box or in live mode

- `Step 2:` Investigate on the various categories of tools as follows:

- `Step 3:` Open terminal and try execute some kali linux commands

### DEVELOPED BY : Lokesh N
### REGISTER NO : 212222100023

## EXECUTION STEPS AND ITS OUTPUT:
Find out the ip address of the attackers system

![ethical_5 1](https://github.com/gummadileepkumar/Metasploit-for-reconnaissance/assets/118707761/04220a00-3388-4bc9-a1f1-158ee227e9ed)

Invoke msfconsole
![ethical_5 2](https://github.com/gummadileepkumar/Metasploit-for-reconnaissance/assets/118707761/5b3f13e7-02d6-4ae9-a679-1e29814c1f36)


Type help or a question mark "?" to see the list of all available commands you can use inside msfconsole.
![ethical_5 3](https://github.com/gummadileepkumar/Metasploit-for-reconnaissance/assets/118707761/6c95ae22-de63-4a00-88f6-4bc30dc12444)


### Port scanning:
msf > nmap -sT 192.168.1810/24-p1-1000
![ethical_5 4](https://github.com/gummadileepkumar/Metasploit-for-reconnaissance/assets/118707761/7b3b9751-0f3d-4d24-89ed-0c355510e584)


msf > db_nmap 192.168.181.0/24
![ethical_5 5](https://github.com/gummadileepkumar/Metasploit-for-reconnaissance/assets/118707761/7308445a-9df5-4fd4-8077-d531ebee15a8)


kali > ls-l
![ethical_5 6](https://github.com/gummadileepkumar/Metasploit-for-reconnaissance/assets/118707761/98842d34-af18-450d-9add-702185e645d9)


search
![ethical_5 7](https://github.com/gummadileepkumar/Metasploit-for-reconnaissance/assets/118707761/1c0f045a-d5c1-4f90-9c79-1e9eba202c18)


info

![ethical_5 8](https://github.com/gummadileepkumar/Metasploit-for-reconnaissance/assets/118707761/9bc1819e-5511-4ce0-84d7-4ba1c793bd76)


### MYSQL ENUMERATION
db_nmap -sV -sC -p 3306 <metasploitable_ip_address>
![ethical_5 9](https://github.com/gummadileepkumar/Metasploit-for-reconnaissance/assets/118707761/fb1ea679-eb44-4e03-9ba3-4dd22b7ee4f3)


search

![ethical_5 10](https://github.com/gummadileepkumar/Metasploit-for-reconnaissance/assets/118707761/2b8cc4f8-dad6-4b88-8f42-0c40ca910f9e)


use 11 Or: use auxiliary/scanner/mysql/mysql_version

![ethical_5 11](https://github.com/gummadileepkumar/Metasploit-for-reconnaissance/assets/118707761/1ed2c0cf-e534-4480-be7c-92ad93aff9af)


Use the set rhosts command to set the parameter and run the module, as follows:

![ethical_5 12](https://github.com/gummadileepkumar/Metasploit-for-reconnaissance/assets/118707761/fe0a84b6-736b-4327-bd36-5f0041c3be04)


After scanning, you can also brute force MySQL root account via Metasploit's auxiliary(scanner/mysql/mysql_login) module
![ethical_5 13](https://github.com/gummadileepkumar/Metasploit-for-reconnaissance/assets/118707761/b15e8e09-e2fd-46cc-9069-df3845418aee)


/usr/share/wordlists: set PASS_FILE /usr/share/wordlistss/rockyou.txt
![ethical_5 14](https://github.com/gummadileepkumar/Metasploit-for-reconnaissance/assets/118707761/03ba1329-f140-4880-a8d0-9ce3dc5d6978)

![ethical_5 15](https://github.com/gummadileepkumar/Metasploit-for-reconnaissance/assets/118707761/505ee333-6a46-4fe5-9fac-3334d6401141)


## RESULT:
The Metasploit framework for reconnaissance is  examined successfully
