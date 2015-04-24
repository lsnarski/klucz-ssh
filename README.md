# klucz-sshlsnarski@p210-7:~$ ls
Dokumenty  mail  Muzyka  Obrazy  Pobrane  Publiczny  Pulpit  Szablony  Wideo
lsnarski@p210-7:~$ ssh-keygen
Generating public/private rsa key pair.
Enter file in which to save the key (/home/studpoz/lsnarski/.ssh/id_rsa): 
Created directory '/home/studpoz/lsnarski/.ssh'.
Enter passphrase (empty for no passphrase): 
Enter same passphrase again: 
Your identification has been saved in /home/studpoz/lsnarski/.ssh/id_rsa.
Your public key has been saved in /home/studpoz/lsnarski/.ssh/id_rsa.pub.
The key fingerprint is:
0a:cb:a0:2d:17:6e:3b:00:45:66:1d:a5:68:c4:81:3f lsnarski@p210-7
The key's randomart image is:
+--[ RSA 2048]----+
| +*o.o.          |
|.+o...           |
| oo .            |
|..E              |
|. o..   S        |
|.+ + o .         |
|o.= o .          |
| +..             |
|  ..             |
+-----------------+
lsnarski@p210-7:~$ cd lsnarski@p210-12:~/.ssh/id_rsa.pub
bash: cd: lsnarski@p210-12:~/.ssh/id_rsa.pub: Nie ma takiego pliku ani katalogu
lsnarski@p210-7:~$ cd
lsnarski@p210-7:~$ cat ~/.ssh/id_rsa.pub
ssh-rsa AAAAB3NzaC1yc2EAAAADAQABAAABAQDhwV9LnBmYRwVDgAJ/0jiXgg00MoBf68w0GdLQknv889Nit18PAb2ibcl6osiaG8Xf6CE1XmY5mfvKLPwAYxJoX+LCIS6mgOsUJF0ePCDAg8SRK6D3s1F1hx4DYZsHm7AgBBw4y9r5KLhmbbOZg84h5YDf042KHLRDsP2a7Hfi3xnYPEnLhlNWkmj8em2ACcxjadrMavdYB6H6RApLFZpI4NNAG+NiKHP5bPRL7Sicd2rztOzWGJXgrqZGh/e9JMaamcT7gYiEUZflQU9FkYJE8zl/eO4/1c3Lx2IwiRJ6pUZzjKAvUFt6YIp0FIuGagh0NDaWwz1CNF/1v/QWmZDX lsnarski@p210-7
