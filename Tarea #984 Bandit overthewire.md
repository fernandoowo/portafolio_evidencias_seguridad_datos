// TAREA #984 BANDIT EN OVERTHEWIRE
//Gonzalez Navarro Brandon

nivel o entrar a servidor 
ssh -p 2220 bandit0@bandit.labs.overthewire.org
contraseña bandit0
 ls -apls

nivel 0-1
cat readme
boJ9jbbUNNfktd78OOpsqOltutMc3MY1 
ssh bandit1@bandit.labs.overthewire.org -p2220
boJ9jbbUNNfktd78OOpsqOltutMc3MY1
ls -alps

nivel 1-2
cat ./-
CV1DtqXWVFXTvM2F0k09SHz0YwRINYA9
ssh bandit2@bandit.labs.overthewire.org -p2220
CV1DtqXWVFXTvM2F0k09SHz0YwRINYA9
ls alps

nivel 2-3
cat spaces\ in\ this\ filename
UmHadQclWmgdLOKQ3YNgjWxGoRMb5luK
ssh bandit3@bandit.labs.overthewire.org -p2220
UmHadQclWmgdLOKQ3YNgjWxGoRMb5luK
ls -alps

nivel 3-4 
cd inhere/
ls -al
cat .hidden
pIwrPrtPN36QITSp3EQaw936yaFoFgAB
ssh bandit4@bandit.labs.overthewire.org -p2220
pIwrPrtPN36QITSp3EQaw936yaFoFgAB
ls -alps

level 4-5
cd inhere/
ls
find . -type f| xargs file
man xargs
cat ./-file07
koReBOKuIDDepwhWk7jZC0RTdopnAYKh
exit
ssh bandit5@bandit.labs.overthewire.org -p2220
koReBOKuIDDepwhWk7jZC0RTdopnAYKh

level 5-6
ls
cd inhere/
find . -type f -size 1033c ! -executable
cat ./maybehere07/.file2
DXjZPULLxYr17uwoI01bNLQbtFemEgo7
  HKBPTKQnIay4Fw76bEy8PVxKEDQRKTzs
  ssh bandit6@bandit.labs.overthewire.org -p2220                                
DXjZPULLxYr17uwoI01bNLQbtFemEgo7
                         
                         
level 6-7                         
find / -type f -user bandit7 -group bandit6 -size 33c
cat /var/lib/dpkg/info/bandit7.password
HKBPTKQnIay4Fw76bEy8PVxKEDQRKTzs
ssh bandit7@bandit.labs.overthewire.org -p2220 
HKBPTKQnIay4Fw76bEy8PVxKEDQRKTzs

level 7-8
ls -apls
cat data.txt
whatis strings
strings data.txt
strings data.txt | grep "millionth"
millionth	cvX2JJa4CFALtqS87jk27qwqGhBM9plV
UsvVyFSfZZWbi6wgC7dAFyFuR6jQQUhR
ssh bandit8@bandit.labs.overthewire.org -p2220
cvX2JJa4CFALtqS87jk27qwqGhBM9plV

level 8-9 tuberia y direcionamiento 
cat data.txt
sort data .txt
man uniq
sort data. txt | uniq -c
UsvVyFSfZZWbi6wgC7dAFyFuR6jQQUhR
exit
ssh bandit9@bandit.labs.overthewire.org -p2220
UsvVyFSfZZWbi6wgC7dAFyFuR6jQQUhR

level 9-10 
strings data.txt | grep "="
truKLdjsbJ5g7yyJ2X2R0o3a5HQJFuLk
exit
ssh bandit10@bandit.labs.overthewire.org -p2220
truKLdjsbJ5g7yyJ2X2R0o3a5HQJFuLk

level 10-11 base 64 
cat data.txt
base
man base64
base64 -d data.txt
IFukwKGsFW8MOq3IRFqrxE1hxTNEbUPR
exit
ssh bandit11@bandit.labs.overthewire.org -p2220
IFukwKGsFW8MOq3IRFqrxE1hxTNEbUPR

level 11-12 rot13
//ciberchef
cat data.txt

 5Te8Y4drgCRfCx8ugdwuEX8KFC6k2EUu
 exit
 ssh bandit12@bandit.labs.overthewire.org -p2220
5Te8Y4drgCRfCx8ugdwuEX8KFC6k2EUu
  
level 12-13
cat data.txt
//man xxd 
mkdir /tmp/cintya
cp data.txt /tmp/cintya
cd /tmp/cintya
ls
xxd -r data.txt > data
ls
file data 
mv data file.gz
gzip -d file.gzfile
ls
file file 
mv file file.bz2
bzip2 -d file.bz2
ls
file file
mv file file.gz
gzip -d file.gz
ls
file file
mv file file.tar 
tar -xf file.tar
ls
file data5.bin
rm file.tar
rm data 
rm data.txt
ls 
file file 
file data5.bin
mv data5.bin data.tar
tar xf data.tar
ls 
file data6.bin
mv data6.bin data.bz2
bzip2 -d data.bz2
ls
file file
file date
file data 
mv data data.tar
ls 
tar xf data.tar
ls
file data8.bin
mv data8.bin data.gz
gzip -d data.gz
ls 
file data
cat data 
 ssh bandit13@bandit.labs.overthewire.org -p2220
 8ZjyCRiBWFYkneahHwxCv3wb2a1ORpYL
 

 level 13-14 open ssh 
 ls 
 ssh -i sshkey.private bandit14@localhost
 cat /etc/bandit_pass/bandit14
4wcYUJFw0k0XLShlDzztnTBHiqxU3b3e


level 14-15 
nc localhost 30000 
cat /etc/bandit_pass/bandit14 
nc localhost 30000 
4wcYUJFw0k0XLShlDzztnTBHiqxU3b3e
ssh bandit15@bandit.labs.overthewire.org -p2220
BfMYroe26WYalil77FoDi9qh59eK5xNr

level 15-16 
cat /ect/bandit_pass/bandit15
BfMYroe26WYalil77FoDi9qh59eK5xNr
 man nc | grep ssl
 man nc
man ncat
man ncat | grep ssl
ncat --ssl localhost 30001
BfMYroe26WYalil77FoDi9qh59eK5xNr
cluFn7wTiGryunymYOu4RcffSxQluehd


level 16-17 
cat /etc/bandit_pass/bandit16
cluFn7wTiGryunymYOu4RcffSxQluehd
nmap localhost -p 31000-32000
cluFn7wTiGryunymYOu4RcffSxQluehd
nc localhost 31790
nmap localhost -p 31000-32000
cluFn7wTiGryunymYOu4RcffSxQluehd
ncat --ssl localhost 31790
nmap localhost -p 31000-32000
cluFn7wTiGryunymYOu4RcffSxQluehd

-----BEGIN RSA PRIVATE KEY-----
MIIEogIBAAKCAQEAvmOkuifmMg6HL2YPIOjon6iWfbp7c3jx34YkYWqUH57SUdyJ
imZzeyGC0gtZPGujUSxiJSWI/oTqexh+cAMTSMlOJf7+BrJObArnxd9Y7YT2bRPQ
Ja6Lzb558YW3FZl87ORiO+rW4LCDCNd2lUvLE/GL2GWyuKN0K5iCd5TbtJzEkQTu
DSt2mcNn4rhAL+JFr56o4T6z8WWAW18BR6yGrMq7Q/kALHYW3OekePQAzL0VUYbW
JGTi65CxbCnzc/w4+mqQyvmzpWtMAzJTzAzQxNbkR2MBGySxDLrjg0LWN6sK7wNX
x0YVztz/zbIkPjfkU1jHS+9EbVNj+D1XFOJuaQIDAQABAoIBABagpxpM1aoLWfvD
KHcj10nqcoBc4oE11aFYQwik7xfW+24pRNuDE6SFthOar69jp5RlLwD1NhPx3iBl
J9nOM8OJ0VToum43UOS8YxF8WwhXriYGnc1sskbwpXOUDc9uX4+UESzH22P29ovd
d8WErY0gPxun8pbJLmxkAtWNhpMvfe0050vk9TL5wqbu9AlbssgTcCXkMQnPw9nC
YNN6DDP2lbcBrvgT9YCNL6C+ZKufD52yOQ9qOkwFTEQpjtF4uNtJom+asvlpmS8A
vLY9r60wYSvmZhNqBUrj7lyCtXMIu1kkd4w7F77k+DjHoAXyxcUp1DGL51sOmama
+TOWWgECgYEA8JtPxP0GRJ+IQkX262jM3dEIkza8ky5moIwUqYdsx0NxHgRRhORT
8c8hAuRBb2G82so8vUHk/fur85OEfc9TncnCY2crpoqsghifKLxrLgtT+qDpfZnx
SatLdt8GfQ85yA7hnWWJ2MxF3NaeSDm75Lsm+tBbAiyc9P2jGRNtMSkCgYEAypHd
HCctNi/FwjulhttFx/rHYKhLidZDFYeiE/v45bN4yFm8x7R/b0iE7KaszX+Exdvt
SghaTdcG0Knyw1bpJVyusavPzpaJMjdJ6tcFhVAbAjm7enCIvGCSx+X3l5SiWg0A
R57hJglezIiVjv3aGwHwvlZvtszK6zV6oXFAu0ECgYAbjo46T4hyP5tJi93V5HDi
Ttiek7xRVxUl+iU7rWkGAXFpMLFteQEsRr7PJ/lemmEY5eTDAFMLy9FL2m9oQWCg
R8VdwSk8r9FGLS+9aKcV5PI/WEKlwgXinB3OhYimtiG2Cg5JCqIZFHxD6MjEGOiu
L8ktHMPvodBwNsSBULpG0QKBgBAplTfC1HOnWiMGOU3KPwYWt0O6CdTkmJOmL8Ni
blh9elyZ9FsGxsgtRBXRsqXuz7wtsQAgLHxbdLq/ZJQ7YfzOKU4ZxEnabvXnvWkU
YOdjHdSOoKvDQNWu6ucyLRAWFuISeXw9a/9p7ftpxm0TSgyvmfLF2MIAEwyzRqaM
77pBAoGAMmjmIJdjp+Ez8duyn3ieo36yrttF5NSsJLAbxFpdlc1gvtGCWW+9Cq0b
dxviW8+TFVEBl1O4f7HVm6EpTscdDxU+bCXWkfjuRb7Dy9GOtt9JPsX8MBTakzh3
vBgsyi/sN3RqRBcGU40fOoZyfAMT8s1m/uYv52O6IgeuZ/ujbjY=
-----END RSA PRIVATE KEY-----

vim key 
sudo apt install vim
:wq
chmod 400 key
ssh -i key bandit17@bandit.labs.overthewire.org -p2220

level 17-18
diff passwords.old passwords.new
42c42
< w0Yfolrc5bwjS4qw5mq1nnQi6mF03bii
---
> kfBf3eYk5BPBRzwjqutbbfE887SVc5Yd
IueksS7Ubh8G3DCwVzrTd8rAVOwq3M5x
ssh bandit18@bandit.labs.overthewire.org -p2220
kfBf3eYk5BPBRzwjqutbbfE887SVc5Yd

level 18-19
man ssh 
man ssh | grep shell
ssh -t  bandit18@bandit.labs.overthewire.org -p 2220 /bin/sh
kfBf3eYk5BPBRzwjqutbbfE887SVc5Yd
ls
cat readme
IueksS7Ubh8G3DCwVzrTd8rAVOwq3M5x
exit
ssh bandit19@bandit.labs.overthewire.org -p 2220 
IueksS7Ubh8G3DCwVzrTd8rAVOwq3M5x

level 19-20 binario setuid
ls
./bandit20-do id
./bandit20-do ls
./bandit20-do cat /etc/bandit_pass/bandit20
GbKksEFF4yrVs6il55v6gwY5aVje5f0j
ssh bandit20@bandit.labs.overthewire.org -p 2220 
GbKksEFF4yrVs6il55v6gwY5aVje5f0j

level 20-21
ls 
./suconnect
cat /etc/bandit_pass/bandit20
GbKksEFF4yrVs6il55v6gwY5aVje5f0j
nmap -f localhost
bash 
ssh bandit20@bandit.labs.overthewire.org -p 2220
GbKksEFF4yrVs6il55v6gwY5aVje5f0j
cat /etc/bandit_pass/bandit20 | nc -l localhost 1234
gE269g2h3mw3pwgrj0Ha9Uoqen1c9DGr
./suconnect 1234
Read: GbKksEFF4yrVs6il55v6gwY5aVje5f0j
Password matches, sending next password
exit
ssh bandit21@bandit.labs.overthewire.org -p 2220
gE269g2h3mw3pwgrj0Ha9Uoqen1c9DGr

level 21-22
cd /etc/cron.d
ls a directory
vim /etc/cron.d/
ls /etc/cron.d/
cat /etc/cron.d/cronojob_bandit22 @reboot bandit22 /usr/bin/cronjob_bandit22.sh &> /dev/null ****** bandit22 /usr/bin/cronjob_bandit22.sh &> /dev/null
cat /usr/bin/cronjob_bandit22.sh
#!/bin/bash
chmod 644 /tmp/t7O6lds9S0RqQh9aMcz6ShpAoZKF7fgv
cat /etc/bandit_pass/bandit22 > /tmp/t7O6lds9S0RqQh9aMcz6ShpAoZKF7fgv
Yk7owGAcWjwMVRwrTesJEwB7WVOiILLI
exit
level 22-23
ssh bandit22@bandit.labs.overthewire.org -p 2220
us
cat /etc/cron.d/cronojob_bandit23 @reboot bandit23 /usr/bin/cronjob_bandit23.sh &> /dev/null ****** bandit23 /usr/bin/cronjob_bandit23.sh &> /dev/null
whoami
myname
myname=bandit23
echo I am user name $myname | md5sum l cut -d '' -f 1
8ca319486bfbbc3663ea0fbe81326349
cat /tmp/8ca319486bfbbc3663ea0fbe81326349
jc1udXuA1tiHqjIsL8yaapX5XIAI6i0n
exit 
level 23-24
ssh bandit23@bandit.labs.overthewire.org -p 2220
jc1udXuA1tiHqjIsL8yaapX5XIAI6i0n
ls /etc/cron.d
cat /etc/cron.d/cronojob_bandit24 @reboot bandit24 /usr/bin/cronjob_bandit24.sh &> /dev/null ****** bandit24 /usr/bin/cronjob_bandit24.sh &> /dev/null
cat /etc/cron.d/cronojob_bandit24.sh
cat /usr/bin/cronjob_bandit24.sh
mkdir /tmp/bandit-pass24
chmod 777 /tmp/bandit-pass24/
vim get-pass.sh
which bash
cat /etc/bandit_pass/bandit24 > /tmp/bandit-pass24/password.txt
chmod +x get-pass.sh
date
ls /tmp/bandit-pass24/password.txt
cat /tmp/bandit-pass24/password.txt
UoMYTrfrBFHyQXmg6gzctqAwOmw1Iohz
exit

level 24-25
ssh bandit24@bandit.labs.overthewire.org -p 2220
UoMYTrfrBFHyQXmg6gzctqAwOmw1Iohz
nc locahost 30002
mkdir /tmp/bandit-pass25
cd /tmp/bandit-pass25
vim script.sh
chmod +x script.sh
ls -l
./script.sh | nc locahost 30002
uNG9O58gUE7snukf3bvZ0rxhtnjzSGzG

level 25-26
ssh bandit25@bandit.labs.overthewire.org -p 2220
uNG9O58gUE7snukf3bvZ0rxhtnjzSGzG
cat /etc/passwd | grep bandit26
ls 
cat bandit26.sshkey
-----BEGIN RSA PRIVATE KEY-----
MIIEpQIBAAKCAQEApis2AuoooEqeYWamtwX2k5z9uU1Afl2F8VyXQqbv/LTrIwdW
pTfaeRHXzr0Y0a5Oe3GB/+W2+PReif+bPZlzTY1XFwpk+DiHk1kmL0moEW8HJuT9
/5XbnpjSzn0eEAfFax2OcopjrzVqdBJQerkj0puv3UXY07AskgkyD5XepwGAlJOG
xZsMq1oZqQ0W29aBtfykuGie2bxroRjuAPrYM4o3MMmtlNE5fC4G9Ihq0eq73MDi
1ze6d2jIGce873qxn308BA2qhRPJNEbnPev5gI+5tU+UxebW8KLbk0EhoXB953Ix
3lgOIrT9Y6skRjsMSFmC6WN/O7ovu8QzGqxdywIDAQABAoIBAAaXoETtVT9GtpHW
qLaKHgYtLEO1tOFOhInWyolyZgL4inuRRva3CIvVEWK6TcnDyIlNL4MfcerehwGi
il4fQFvLR7E6UFcopvhJiSJHIcvPQ9FfNFR3dYcNOQ/IFvE73bEqMwSISPwiel6w
e1DjF3C7jHaS1s9PJfWFN982aublL/yLbJP+ou3ifdljS7QzjWZA8NRiMwmBGPIh
Yq8weR3jIVQl3ndEYxO7Cr/wXXebZwlP6CPZb67rBy0jg+366mxQbDZIwZYEaUME
zY5izFclr/kKj4s7NTRkC76Yx+rTNP5+BX+JT+rgz5aoQq8ghMw43NYwxjXym/MX
c8X8g0ECgYEA1crBUAR1gSkM+5mGjjoFLJKrFP+IhUHFh25qGI4Dcxxh1f3M53le
wF1rkp5SJnHRFm9IW3gM1JoF0PQxI5aXHRGHphwPeKnsQ/xQBRWCeYpqTme9amJV
tD3aDHkpIhYxkNxqol5gDCAt6tdFSxqPaNfdfsfaAOXiKGrQESUjIBcCgYEAxvmI
2ROJsBXaiM4Iyg9hUpjZIn8TW2UlH76pojFG6/KBd1NcnW3fu0ZUU790wAu7QbbU
i7pieeqCqSYcZsmkhnOvbdx54A6NNCR2btc+si6pDOe1jdsGdXISDRHFb9QxjZCj
6xzWMNvb5n1yUb9w9nfN1PZzATfUsOV+Fy8CbG0CgYEAifkTLwfhqZyLk2huTSWm
pzB0ltWfDpj22MNqVzR3h3d+sHLeJVjPzIe9396rF8KGdNsWsGlWpnJMZKDjgZsz
JQBmMc6UMYRARVP1dIKANN4eY0FSHfEebHcqXLho0mXOUTXe37DWfZza5V9Oify3
JquBd8uUptW1Ue41H4t/ErsCgYEArc5FYtF1QXIlfcDz3oUGz16itUZpgzlb71nd
1cbTm8EupCwWR5I1j+IEQU+JTUQyI1nwWcnKwZI+5kBbKNJUu/mLsRyY/UXYxEZh
ibrNklm94373kV1US/0DlZUDcQba7jz9Yp/C3dT/RlwoIw5mP3UxQCizFspNKOSe
euPeaxUCgYEAntklXwBbokgdDup/u/3ms5Lb/bm22zDOCg2HrlWQCqKEkWkAO6R5
/Wwyqhp/wTl8VXjxWo+W+DmewGdPHGQQ5fFdqgpuQpGUq24YZS8m66v5ANBwd76t
IZdtF5HXs2S5CADTwniUS5mX1HO9l5gUkk+h0cH5JnPtsMCnAUM+BRY=
-----END RSA PRIVATE KEY-----

cat /usr/bin/showtext
ssh -i bandit26.sshkey bandit26@localhost 
more -V
::
configurar /bin/bash
 ./bandit27-do cat /etc/bandit_pass/bandit27
 3ba3118a22e93127a4ed485be72ef5ea
 exit

level 26-27
cat /usr/bin/showtext
ssh -i bandit26.sshkey bandit26@localhost 
more -V
::
configurar /bin/bash
 ./bandit27-do cat /etc/bandit_pass/bandit27
 3ba3118a22e93127a4ed485be72ef5ea
 exit
ssh bandit27@bandit.labs.overthewire.org -p
 3ba3118a22e93127a4ed485be72ef5ea
 
level 27-28
mkdir /tmp/bandit-pass28
cd /tmp/bandit-pass28
git clone "ssh://bandit-git@localhost/home/bandit27-git/repo"
cd repo/
ls
cat README
0ef186ac70e04ea33b4c1853d2526fa2
exit


level 28-29
ssh bandit28@bandit.labs.overthewire.org -p 2220
0ef186ac70e04ea33b4c1853d2526fa2
mkdir /tmp/bandit-pass29
cd /tmp/bandit-pass29
git clone "ssh://bandit28-git@localhost/home/bandit28-git/respo"
ls
cd repo/
ls
cat README.md
git log 
git diff edd935d60906b33f0619605abd1689808ccdd5ee c086d11a00c0648d095d04c089786efef5e01264

bbc96594b4e001778eee9975372716b2
exit
level 29-30
ssh bandit29@bandit.labs.overthewire.org -p 2220
bbc96594b4e001778eee9975372716b2
mkdir /tmp/bandit-pass30
cd /tmp/bandit-pass30
git clone "ssh://bandit29-git@localhost/home/bandit29-git/repo"
cd repo/
ls
cat README.md
git log 
208f463b5b3992906eabf23c562eda3277fea912
18a6fd6d5ef7f0874bbdda2fa0d77b3b81fd63f7
git diff 208f463b5b3992906eabf23c562eda3277fea912 
18a6fd6d5ef7f0874bbdda2fa0d77b3b81fd63f7
git branch
git branch -a
git checkout remotes/origin/dev
git branch * master
git log 
bc833286fca18a3948aec989f7025e23ffc16c07
8e6c203f885bd4cd77602f8b9a9ea479929ffa57
208f463b5b3992906eabf23c562eda3277fea912
18a6fd6d5ef7f0874bbdda2fa0d77b3b81fd63f7
git show bc833286fca18a3948aec989f7025e23ffc16c07

 5b90576bedb2cc04c86a9e924ce42faf
 exit
level 30-31
ssh bandit30@bandit.labs.overthewire.org -p 2220
 5b90576bedb2cc04c86a9e924ce42faf
 mkdir /tmp/bandit-pass31
 cd /tmp/bandit-pass31
 git clone "ssh://bandit30-git@localhost/home/bandit30-git/repo"
 cd repo/
 ls
 cat READMEN.md
 git log
 3aefa229469b7ba1cc08203e5d8fa299354c496b
 git branch -a * master
 git show -ref
 git show f17132340e8ee6c159e0a4a6bc6f80e1da3b1aea
47e603bb428404d265f59c42920d81e5

level 31-32
ssh bandit31@bandit.labs.overthewire.org -p 2220
47e603bb428404d265f59c42920d81e5

mkdir /tmp/bandit-pass32
cd /tmp/bandit-pass32
git clone "ssh://bandit31-git@localhost/home/bandit31-git/repo"
ls repo/README.md
cat repo/README.md
cd repo/
git branch *master
vim key.txt
git add key.txt
cat .gitignore*.txt
git add -f key.txt
git commit -m "update key.txt file"
git push
56a9bf19c63d650ce78e6ec0354ee45e
exit

level 32-33
ssh bandit31@bandit.labs.overthewire.org -p 2220
56a9bf19c63d650ce78e6ec0354ee45e
ls
whoami
>> $0
$whoami
pwd
$ ls -al*
cat /etc/bandit_pass/bandit33
c9c3199ddf4121b10cf581a98d51caee

level 33-34
ls

cat README.txt
Congratulations on solving the last level of this game!

At this moment, there are no more levels to play in this game. However, we are constantly working
on new levels and will most likely expand this game with more levels soon.
Keep an eye out for an announcement on our usual communication channels!
In the meantime, you could play some of our other wargames.

If you have an idea for an awesome new level, please let us know!