Last login: Thu May 24 16:41:01 on ttys039
imac:~ gail01$ ssh mothra
Last login: Thu May 24 16:41:03 2018 from 10.91.17.183
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
	The /sc/orga/ file system is optimized for performance and
	capacity. It provides minimal redundancy and no backups.

	Data stored in /sc/orga/scratch/ is automatically purged after
	14 days.

	=== Follow us on Twitter @mssmhpc ===
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

***ANNOUNCEMENTS***

2018-2019 ALLOCATIONS
New and renewal allocation requests for the 2018-2019 allocation period 
must be made starting 1 May 2018 and ending 15 May 2018 on our allocation website
https://hpc.mssm.edu/hpc-admin/forms/allocation-request
gail01@login1: ~ $ module avail sratoolkit
utility.c(2245):ERROR:50: Cannot open file '/hpc/packages/minerva-common/modulefiles/rvtests/core.63535' for 'reading'

----------------------------------------------------- /hpc/packages/minerva-common/modulefiles ------------------------------------------------------
sratoolkit/2.4.2-1 sratoolkit/2.5.7   sratoolkit/2.8.0   sratoolkit/2.9.0
gail01@login1: ~ $ module load sratoolkit/2.9.0
gail01@login1: ~ $ vdb-config -i














     vdb-config                                                                                                                                      
                                                                                                                                                     
                                                                                                                                                     
   [X] Enable Remote Access (1)                                              [ Save (6) ]   [ Exit (7) ]                                             
                                                                                                                                                     
   [X] Enable Local File Caching (2)                                         [       Reload (8)        ]                                             
                                                                                                                                                     
                                                                             [  Standard Settings (9)  ]                                             
                                                                                                                                                     
   [ ] Use Proxy   [ Change ]                                                                                                                        
                                                                                                                                                     
   [ ] Prioritize Env. Variable 'http_proxy'                                                                                                         
                                                                                                                                                     
                                                                                                                                                     
                                                                                                                                                     
   [ Import Repository Key (4)  ]   [  Set Default Import Path (5)  ]                                                                                
                                                                                                                                                     
   Workspace Name                   Public                                                                                                           
                                                                                                                                                     
                                    [ Change ]   /sc/orga/scratch/gail01/sralocation                                                                 
                                                                                                                                                     
                                                                                                                                                     
                                                                                                                                                     
                                                                                                                                                     
                                                                                                                                                     
                                                                                                                                                     
                                                                                                                                                     
                                                                                                                                                     
                                                                                                                                                     
                                                                                                                                                     
                                                                                                                                                     
                                                                                                                                                     
                                                                                                                                                     
                                                                                                                                                     
                                                                                                                                                     
                                                                                                                                                     
   Press the number in (X) as a shortcut                                                                                                             
                                                                                                                                                     
                                                                                                                                                     
 Press SPACE | ENTER to exit vdb-config                                                                                                              
gail01@login1: ~ $ screen -U -S 2
gail01@login1: /sc/orga/packages/data_tem $ 
gail01@login1: /sc/orga/packages/data_tem $ 
gail01@login1: /sc/orga/packages/data_tem $ 
gail01@login1: /sc/orga/packages/data_tem $ 
gail01@login1: /sc/orga/packages/data_tem $ 
gail01@login1: /sc/orga/packages/data_tem $ sudo su -
[sudo] password for gail01: 
[root@login1 ~]# cd /sc/orga/packages/data_tem 
[root@login1 data_tem]# ls
log  SRR5444926_1.fastq  SRR5444926_2.fastq
[root@login1 data_tem]# cd /sc/orga/scratch/zhus02/
[root@login1 zhus02]# ls
bamForISMARA  code  forGang  GWAS_summary  Simulation  SRR  Transcripts  worm
[root@login1 zhus02]# cd SRR
[root@login1 SRR]# ls
log  SRR5444926.fastq
[root@login1 SRR]# cd ..
[root@login1 zhus02]# cd SRR
[root@login1 SRR]# ls
log  SRR5444926.fastq
[root@login1 SRR]# mkdir old
[root@login1 SRR]# cd old/
[root@login1 old]# mv ../* .
mv: cannot move `../old' to a subdirectory of itself, `./old'
[root@login1 old]# ls
log  SRR5444926.fastq
[root@login1 old]# cd ..
[root@login1 SRR]# ls
old
[root@login1 SRR]# cp /sc/orga/packages/data_tem/* .
[root@login1 SRR]# ls
log  old  SRR5444926_1.fastq  SRR5444926_2.fastq
[root@login1 SRR]# cd ..
[root@login1 zhus02]# ls -lt
total 0
drwxr-xr-x  3 zhus02 fangg03a 4096 May 30 09:06 SRR
drwxrwxr-x. 4 zhus02 fangg03a 4096 Apr 10 15:41 Simulation
drwxrwxr-x. 2 zhus02 fangg03a 4096 Jan 29 10:25 Transcripts
drwxrwxr-x. 5 zhus02 fangg03a 4096 Dec 21 10:25 GWAS_summary
drwxrwxr-x. 2 zhus02 fangg03a 4096 Oct 17  2017 worm
drwxrwxr-x. 2 zhus02 fangg03a 4096 Aug 14  2017 forGang
drwxrwxr-x. 3 zhus02 fangg03a 4096 May  5  2017 code
drwxrwxr-x. 4 zhus02 fangg03a 4096 Apr  2  2017 bamForISMARA
[root@login1 zhus02]# chown -R zhus02:fangg03a SRR
[root@login1 zhus02]# cd SRR
[root@login1 SRR]# ls
log  old  SRR5444926_1.fastq  SRR5444926_2.fastq
[root@login1 SRR]# ls -lt
total 262509312
-rw-r--r-- 1 zhus02 fangg03a 134404667652 May 30 09:08 SRR5444926_2.fastq
-rw-r--r-- 1 zhus02 fangg03a 134404667652 May 30 09:06 SRR5444926_1.fastq
-rw-r--r-- 1 zhus02 fangg03a          113 May 30 09:05 log
drwxr-xr-x 2 zhus02 fangg03a         4096 May 30 09:05 old
[root@login1 SRR]# cd
[root@login1 ~]# ssh mgmt1
Last login: Wed May 23 17:45:11 2018 from login1
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
	The /sc/orga/ file system is optimized for performance and
	capacity. It provides minimal redundancy and no backups.

	Data stored in /sc/orga/scratch/ is automatically purged after
	14 days.

	=== Follow us on Twitter @mssmhpc ===
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

***ANNOUNCEMENTS***

2018-2019 ALLOCATIONS
New and renewal allocation requests for the 2018-2019 allocation period 
must be made starting 1 May 2018 and ending 15 May 2018 on our allocation website
https://hpc.mssm.edu/hpc-admin/forms/allocation-request

[root@mgmt1 ~]# ssh minerva4
Last login: Thu May 31 10:02:09 2018 from mgmt2.mothra.hpc.mssm.edu
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
	The /sc/orga/ file system is optimized for performance and
	capacity. It provides minimal redundancy and no backups.

	Data stored in /sc/orga/scratch/ is automatically purged after
	14 days.

	=== Follow us on Twitter @mssmhpc ===
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

***ANNOUNCEMENTS***

2018-2019 ALLOCATIONS
New and renewal allocation requests for the 2018-2019 allocation period 
must be made starting 1 May 2018 and ending 15 May 2018 on our allocation website
https://hpc.mssm.edu/hpc-admin/forms/allocation-request
[root@minerva4 ~]# top -u perumd01

top - 11:17:38 up 70 days, 16:52, 198 users,  load average: 2.03, 2.05, 1.89
Tasks: 2135 total,   2 running, 2108 sleeping,  20 stopped,   5 zombie
Cpu(s):  6.0%us,  1.3%sy,  0.0%ni, 92.4%id,  0.1%wa,  0.0%hi,  0.2%si,  0.0%st
Mem:  132124792k total, 36710884k used, 95413908k free,   251272k buffers
Swap: 134365180k total,  2521076k used, 131844104k free, 12143660k cached

  PID USER      PR  NI  VIRT  RES  SHR S %CPU %MEM    TIME+  COMMAND                                                                              
18360 perumd01  20   0 33152 1544  856 S  0.0  0.0   0:00.00 screen                                                                                
18361 perumd01  20   0 22464 2116 1516 S  0.0  0.0   0:00.02 bash                                                                                  
18846 perumd01  20   0 33152 1544  856 S  0.0  0.0   0:00.00 screen                                                                                
18847 perumd01  20   0 22464 2116 1516 S  0.0  0.0   0:00.02 bash                                                                                  
18960 perumd01  20   0 33152 1544  856 S  0.0  0.0   0:00.00 screen                                                                                
18961 perumd01  20   0 22464 2116 1516 S  0.0  0.0   0:00.02 bash                                                                                  
19479 perumd01  20   0 33152 1544  856 S  0.0  0.0   0:00.00 screen                                                                                
19480 perumd01  20   0 22464 2116 1516 S  0.0  0.0   0:00.02 bash                                                                                  
20218 perumd01  20   0 33152 1548  856 S  0.0  0.0   0:00.00 screen                                                                                
20219 perumd01  20   0 22464 2112 1516 S  0.0  0.0   0:00.02 bash                                                                                  
21099 perumd01  20   0 33152  888  816 S  0.0  0.0   0:00.10 screen                                                                                
21100 perumd01  20   0 22464 1848 1508 S  0.0  0.0   0:00.05 bash                                                                                  
21151 perumd01  20   0 33152 1544  856 S  0.0  0.0   0:00.00 screen                                                                                
21152 perumd01  20   0 22464 2116 1516 S  0.0  0.0   0:00.02 bash                                                                                  
21249 perumd01  20   0 33152 1544  856 S  0.0  0.0   0:00.00 screen                                                                                
21250 perumd01  20   0 22464 2112 1516 S  0.0  0.0   0:00.02 bash                                                                                  
21308 perumd01  20   0 33152  928  808 S  0.0  0.0   0:01.59 screen                                                                                
21309 perumd01  20   0 22464 1936 1508 S  0.0  0.0   0:00.03 bash                                                                                  
21445 perumd01  20   0 33152 1548  856 S  0.0  0.0   0:00.00 screen                                                                                
21446 perumd01  20   0 22464 2116 1516 S  0.0  0.0   0:00.03 bash                                                                                  
21638 perumd01  20   0 33152 1544  856 S  0.0  0.0   0:00.00 screen                                                                                
21639 perumd01  20   0 22456 1984 1404 S  0.0  0.0   0:00.01 bash                                                                                  
22086 perumd01  20   0 22464 1604 1012 S  0.0  0.0   0:00.00 bash                                                                                  
22434 perumd01  20   0  117m 2192 1160 S  0.0  0.0   0:00.00 sshd                                                                                  
22435 perumd01  20   0  9328 1600 1184 S  0.0  0.0   0:00.00 bash                                                                                  
22653 perumd01  20   0 33152 1552  864 S  0.0  0.0   0:00.00 screen                                                                                
22654 perumd01  20   0 22324 1840 1404 S  0.0  0.0   0:00.00 bash                                                                                  
22681 perumd01  20   0 22464 1528 1016 S  0.0  0.0   0:00.00 bash                                                                                  
24474 perumd01  20   0  9332 1024  600 S  0.0  0.0   0:00.00 bash                                                                                  
24475 perumd01  20   0     0    0    0 Z  0.0  0.0   0:00.00 libc.so.6 <defunct>                                                                   
24476 perumd01  20   0     0    0    0 Z  0.0  0.0   0:00.00 grep <defunct>                                                                        
24477 perumd01  20   0     0    0    0 Z  0.0  0.0   0:00.00 gawk <defunct>                                                                        
24478 perumd01  20   0     0    0    0 Z  0.0  0.0   0:00.00 gawk <defunct>                                                                        
24479 perumd01  20   0     0    0    0 Z  0.0  0.0   0:00.00 gawk <defunct>                                                                        
29264 perumd01  20   0 33152 1504  808 S  0.0  0.0   0:00.22 screen                                                                                
29265 perumd01  20   0 22464 2108 1504 S  0.0  0.0   0:00.03 bash                                                                                  
[root@minerva4 ~]# ps x | ps -u perumd01
  PID TTY          TIME CMD
18360 ?        00:00:00 screen
18361 pts/409  00:00:00 bash
18846 ?        00:00:00 screen
18847 pts/410  00:00:00 bash
18960 ?        00:00:00 screen
18961 pts/412  00:00:00 bash
19479 ?        00:00:00 screen
19480 pts/413  00:00:00 bash
20218 ?        00:00:00 screen
20219 pts/414  00:00:00 bash
21099 ?        00:00:00 screen
21100 pts/280  00:00:00 bash
21151 ?        00:00:00 screen
21152 pts/415  00:00:00 bash
21249 ?        00:00:00 screen
21250 pts/416  00:00:00 bash
21308 ?        00:00:01 screen
21309 pts/290  00:00:00 bash
21445 ?        00:00:00 screen
21446 pts/417  00:00:00 bash
21638 ?        00:00:00 screen
21639 pts/152  00:00:00 bash
22086 pts/152  00:00:00 bash
22434 ?        00:00:00 sshd
22435 ?        00:00:00 bash
22653 ?        00:00:00 screen
22654 pts/171  00:00:00 bash
22681 pts/171  00:00:00 bash
25962 ?        00:00:00 bash
25963 ?        00:00:00 libc.so.6 <defunct>
25964 ?        00:00:00 grep <defunct>
25965 ?        00:00:00 gawk <defunct>
25966 ?        00:00:00 gawk <defunct>
25967 ?        00:00:00 gawk <defunct>
29264 ?        00:00:00 screen
29265 pts/299  00:00:00 bash
29359 ?        00:00:00 screen
29360 pts/302  00:00:00 bash
41029 ?        00:00:00 screen
41030 pts/383  00:00:00 bash
41860 ?        00:00:00 screen
41861 pts/385  00:00:00 bash
41977 ?        00:00:00 screen
41978 pts/386  00:00:00 bash
42018 ?        00:00:00 screen
42019 pts/30   00:00:00 bash
42295 ?        00:00:00 screen
42296 pts/387  00:00:00 bash
42845 ?        00:00:00 screen
42846 pts/388  00:00:00 bash
43217 ?        00:00:00 screen
43218 pts/389  00:00:00 bash
43410 ?        00:00:00 screen
43411 pts/390  00:00:00 bash
43546 ?        00:00:00 screen
43547 pts/391  00:00:00 bash
44105 ?        00:00:00 screen
44106 pts/392  00:00:00 bash
44205 ?        00:00:00 screen
44206 pts/393  00:00:00 bash
44351 ?        00:00:00 screen
44352 pts/394  00:00:00 bash
44466 ?        00:00:00 screen
44467 pts/395  00:00:00 bash
44619 ?        00:00:00 screen
44620 pts/396  00:00:00 bash
45157 ?        00:00:00 screen
45158 pts/397  00:00:00 bash
45265 ?        00:00:00 screen
45266 pts/398  00:00:00 bash
45376 ?        00:00:00 screen
45377 pts/399  00:00:00 bash
45525 ?        00:00:00 screen
45528 pts/357  00:00:00 bash
46129 ?        00:00:00 screen
46130 pts/400  00:00:00 bash
46242 ?        00:00:00 screen
46243 pts/368  00:00:00 bash
46761 ?        00:00:00 screen
46762 pts/401  00:00:00 bash
46886 ?        00:00:00 screen
46887 pts/402  00:00:00 bash
47040 ?        00:00:00 screen
47041 pts/403  00:00:00 bash
47163 ?        00:00:00 screen
47164 pts/404  00:00:00 bash
47797 ?        00:00:00 screen
47798 pts/405  00:00:00 bash
47917 ?        00:00:00 screen
47918 pts/406  00:00:00 bash
48063 ?        00:00:00 screen
48064 pts/407  00:00:00 bash
48100 pts/407  00:00:00 bash
48719 ?        00:00:00 screen
48720 pts/408  00:00:00 bash
48778 pts/408  00:00:00 bash
53479 ?        00:00:00 screen
53480 pts/257  00:00:00 bash
53541 ?        00:00:00 screen
53542 pts/172  00:00:00 bash
[root@minerva4 ~]# kill -9 24479
-bash: kill: (24479) - No such process
[root@minerva4 ~]# top -u 24479

top - 11:18:27 up 70 days, 16:53, 198 users,  load average: 2.54, 2.17, 1.94
Tasks: 2125 total,   5 running, 2100 sleeping,  20 stopped,   0 zombie
Cpu(s):  6.0%us,  1.3%sy,  0.0%ni, 92.4%id,  0.1%wa,  0.0%hi,  0.2%si,  0.0%st
Mem:  132124792k total, 37146800k used, 94977992k free,   251432k buffers
Swap: 134365180k total,  2521076k used, 131844104k free, 12591196k cached

  PID USER      PR  NI  VIRT  RES  SHR S %CPU %MEM    TIME+  COMMAND                                                                              




































[root@minerva4 ~]# top -u 24479

top - 11:18:33 up 70 days, 16:53, 198 users,  load average: 2.68, 2.21, 1.96
Tasks: 2124 total,   3 running, 2101 sleeping,  20 stopped,   0 zombie
Cpu(s):  6.0%us,  1.3%sy,  0.0%ni, 92.4%id,  0.1%wa,  0.0%hi,  0.2%si,  0.0%st
Mem:  132124792k total, 37203168k used, 94921624k free,   251436k buffers
Swap: 134365180k total,  2521076k used, 131844104k free, 12646940k cached

  PID USER      PR  NI  VIRT  RES  SHR S %CPU %MEM    TIME+  COMMAND                                                                              





























top - 11:18:54 up 70 days, 16:53, 198 users,  load average: 2.54, 2.21, 1.96
Tasks: 2125 total,   3 running, 2102 sleeping,  20 stopped,   0 zombie
Cpu(s):  5.9%us,  2.0%sy,  0.0%ni, 91.5%id,  0.0%wa,  0.0%hi,  0.6%si,  0.0%st
Mem:  132124792k total, 37403120k used, 94721672k free,   251444k buffers
Swap: 134365180k total,  2521076k used, 131844104k free, 12842976k cached

  PID USER      PR  NI  VIRT  RES  SHR S %CPU %MEM    TIME+  COMMAND                                                                                              
18360 perumd01  20   0 33152 1544  856 S  0.0  0.0   0:00.00 screen                                                                                                
18361 perumd01  20   0 22464 2116 1516 S  0.0  0.0   0:00.02 bash                                                                                                  
18846 perumd01  20   0 33152 1544  856 S  0.0  0.0   0:00.00 screen                                                                                                
18847 perumd01  20   0 22464 2116 1516 S  0.0  0.0   0:00.02 bash                                                                                                  
18960 perumd01  20   0 33152 1544  856 S  0.0  0.0   0:00.00 screen                                                                                                
18961 perumd01  20   0 22464 2116 1516 S  0.0  0.0   0:00.02 bash                                                                                                  
19479 perumd01  20   0 33152 1544  856 S  0.0  0.0   0:00.00 screen                                                                                                
19480 perumd01  20   0 22464 2116 1516 S  0.0  0.0   0:00.02 bash                                                                                                  
20218 perumd01  20   0 33152 1548  856 S  0.0  0.0   0:00.00 screen                                                                                                
20219 perumd01  20   0 22464 2112 1516 S  0.0  0.0   0:00.02 bash                                                                                                  
21099 perumd01  20   0 33152  888  816 S  0.0  0.0   0:00.10 screen                                                                                                
21100 perumd01  20   0 22464 1848 1508 S  0.0  0.0   0:00.05 bash                                                                                                  
21151 perumd01  20   0 33152 1544  856 S  0.0  0.0   0:00.00 screen                                                                                                
21152 perumd01  20   0 22464 2116 1516 S  0.0  0.0   0:00.02 bash                                                                                                  
21249 perumd01  20   0 33152 1544  856 S  0.0  0.0   0:00.00 screen                                                                                                
21250 perumd01  20   0 22464 2112 1516 S  0.0  0.0   0:00.02 bash                                                                                                  
21308 perumd01  20   0 33152  928  808 S  0.0  0.0   0:01.59 screen                                                                                                
21309 perumd01  20   0 22464 1936 1508 S  0.0  0.0   0:00.03 bash                                                                                                  
21445 perumd01  20   0 33152 1548  856 S  0.0  0.0   0:00.00 screen                                                                                                
21446 perumd01  20   0 22464 2116 1516 S  0.0  0.0   0:00.03 bash                                                                                                  
21638 perumd01  20   0 33152 1544  856 S  0.0  0.0   0:00.00 screen                                                                                                
21639 perumd01  20   0 22456 1984 1404 S  0.0  0.0   0:00.01 bash                                                                                                  
22086 perumd01  20   0 22464 1604 1012 S  0.0  0.0   0:00.00 bash                                                                                                  
22653 perumd01  20   0 33152 1552  864 S  0.0  0.0   0:00.00 screen                                                                                                
22654 perumd01  20   0 22324 1840 1404 S  0.0  0.0   0:00.00 bash                                                                                                  
22681 perumd01  20   0 22464 1528 1016 S  0.0  0.0   0:00.00 bash                                                                                                  
29264 perumd01  20   0 33152 1504  808 S  0.0  0.0   0:00.22 screen                                                                                                
29265 perumd01  20   0 22464 2108 1504 S  0.0  0.0   0:00.03 bash                                                                                                  
29359 perumd01  20   0 33152 1496  808 S  0.0  0.0   0:00.27 screen                                                                                                
29360 perumd01  20   0 22464 2104 1504 S  0.0  0.0   0:00.03 bash                                                                                                  
41029 perumd01  20   0 33152 1544  856 S  0.0  0.0   0:00.01 screen                                                                                                
41030 perumd01  20   0 22464 2116 1520 S  0.0  0.0   0:00.03 bash                                                                                                  
41860 perumd01  20   0 33152 1544  856 S  0.0  0.0   0:00.01 screen                                                                                                
41861 perumd01  20   0 22464 2116 1520 S  0.0  0.0   0:00.03 bash                                                                                                  
41977 perumd01  20   0 33152 1544  856 S  0.0  0.0   0:00.02 screen                                                                                                
41978 perumd01  20   0 22464 2116 1520 S  0.0  0.0   0:00.02 bash                                                                                                  
42018 perumd01  20   0 33152 1356  804 S  0.0  0.0   0:00.07 screen                                                                                                
42019 perumd01  20   0 22464 2084 1504 S  0.0  0.0   0:00.02 bash                                                                                                  
42295 perumd01  20   0 33152 1544  856 S  0.0  0.0   0:00.01 screen                                                                                                
42296 perumd01  20   0 22464 2120 1520 S  0.0  0.0   0:00.02 bash                                                                                                  
42845 perumd01  20   0 33152 1548  856 S  0.0  0.0   0:00.00 screen                                                                                                
42846 perumd01  20   0 22464 2124 1520 S  0.0  0.0   0:00.03 bash                                                                                                  
43217 perumd01  20   0 33152 1544  856 S  0.0  0.0   0:00.00 screen                                                                                                
43218 perumd01  20   0 22464 2120 1520 S  0.0  0.0   0:00.03 bash                                                                                                  
43410 perumd01  20   0 33152 1548  856 S  0.0  0.0   0:00.00 screen                                                                                                
[root@minerva4 ~]# su - perumd01
[perumd01@minerva4 ~]$       
[perumd01@minerva4 ~]$ 
[perumd01@minerva4 ~]$ exit
logout
[root@minerva4 ~]# exit
logout
Connection to minerva4 closed.
[root@mgmt1 ~]# exit
logout
Connection to mgmt1 closed.
[root@login1 ~]# su - perumd01
[perumd01@login1 ~]$ top

top - 11:20:12 up 136 days, 3 min, 59 users,  load average: 0.68, 0.57, 0.51
Tasks: 1288 total,   3 running, 1281 sleeping,   4 stopped,   0 zombie
Cpu(s):  2.3%us,  1.6%sy,  0.0%ni, 95.3%id,  0.3%wa,  0.0%hi,  0.4%si,  0.0%st
Mem:  264338188k total, 263637912k used,   700276k free,   206572k buffers
Swap:  4194300k total,  1712968k used,  2481332k free, 237948464k cached

  PID USER      PR  NI  VIRT  RES  SHR S %CPU %MEM    TIME+  COMMAND                                                                                              
 7898 biosoft   20   0  125m  18m  852 S 74.5  0.0  14:27.19 rsync                                                                                                 
 7901 biosoft   20   0 83228 2236  348 R 74.5  0.0  14:23.42 rsync                                                                                                 
 4035 root      20   0     0    0    0 S 13.2  0.0 170:48.91 rpciod/0                                                                                              
15696 root       0 -20 29.1g 9.0g 780m S  4.0  3.6   5660:00 mmfsd                                                                                                 
 8038 kapooa03  20   0  662m  33m  11m S  2.6  0.0   0:21.04 vmd_LINUXAMD64                                                                                        
 4122 root      20   0     0    0    0 S  2.0  0.0  53:01.55 nfsiod                                                                                                
  541 root      20   0     0    0    0 S  1.3  0.0  19:30.64 kswapd0                                                                                               
 8488 perumd01  20   0 26856 2468 1172 R  1.0  0.0   0:00.11 top                                                                                                   
  542 root      20   0     0    0    0 S  0.7  0.0  13:55.12 kswapd1                                                                                               
 3862 root      20   0 11176  840  428 S  0.3  0.0 243:27.69 irqbalance                                                                                            
 4036 root      20   0     0    0    0 R  0.3  0.0   4:30.26 rpciod/1                                                                                              
 4046 root      20   0     0    0    0 S  0.3  0.0   2:34.00 rpciod/11                                                                                             
 4056 root      20   0     0    0    0 S  0.3  0.0   1:27.54 rpciod/21                                                                                             
 8489 root      18  -2  106m 2232 1276 S  0.3  0.0   0:00.01 dhclient-script                                                                                       
 9383 root      18  -2  9112  976  468 S  0.3  0.0   0:08.72 dhclient                                                                                              
11269 preusm01  20   0 11112  936  428 S  0.3  0.0   5:03.92 irqbalance                                                                                            
    1 root      20   0 21428 1328 1104 S  0.0  0.0   0:13.01 init                                                                                                  
    2 root      20   0     0    0    0 S  0.0  0.0   0:00.89 kthreadd                                                                                              
    3 root      RT   0     0    0    0 S  0.0  0.0  22:02.26 migration/0                                                                                           
    4 root      20   0     0    0    0 S  0.0  0.0   8:06.99 ksoftirqd/0                                                                                           
    5 root      RT   0     0    0    0 S  0.0  0.0   0:00.00 stopper/0                                                                                             
    6 root      RT   0     0    0    0 S  0.0  0.0   0:22.98 watchdog/0                                                                                            
    7 root      RT   0     0    0    0 S  0.0  0.0   4:35.37 migration/1                                                                                           
    8 root      RT   0     0    0    0 S  0.0  0.0   0:00.00 stopper/1                                                                                             
    9 root      20   0     0    0    0 S  0.0  0.0   1:16.34 ksoftirqd/1                                                                                           
   10 root      RT   0     0    0    0 S  0.0  0.0   0:16.31 watchdog/1                                                                                            
   11 root      RT   0     0    0    0 S  0.0  0.0   3:07.33 migration/2                                                                                           
   12 root      RT   0     0    0    0 S  0.0  0.0   0:00.00 stopper/2                                                                                             
   13 root      20   0     0    0    0 S  0.0  0.0   0:42.72 ksoftirqd/2                                                                                           
   14 root      RT   0     0    0    0 S  0.0  0.0   0:15.65 watchdog/2                                                                                            
   15 root      RT   0     0    0    0 S  0.0  0.0   2:32.72 migration/3                                                                                           
   16 root      RT   0     0    0    0 S  0.0  0.0   0:00.00 stopper/3                                                                                             
   17 root      20   0     0    0    0 S  0.0  0.0   0:30.03 ksoftirqd/3                                                                                           
   18 root      RT   0     0    0    0 S  0.0  0.0   0:13.58 watchdog/3                                                                                            
   19 root      RT   0     0    0    0 S  0.0  0.0   2:09.86 migration/4                                                                                           
   20 root      RT   0     0    0    0 S  0.0  0.0   0:00.00 stopper/4                                                                                             
   21 root      20   0     0    0    0 S  0.0  0.0   0:22.92 ksoftirqd/4                                                                                           
   22 root      RT   0     0    0    0 S  0.0  0.0   0:11.65 watchdog/4                                                                                            
   23 root      RT   0     0    0    0 S  0.0  0.0   1:49.35 migration/5                                                                                           
   24 root      RT   0     0    0    0 S  0.0  0.0   0:00.00 stopper/5                                                                                             
   25 root      20   0     0    0    0 S  0.0  0.0   0:20.62 ksoftirqd/5                                                                                           
   26 root      RT   0     0    0    0 S  0.0  0.0   0:13.33 watchdog/5                                                                                            
   27 root      RT   0     0    0    0 S  0.0  0.0   1:43.26 migration/6                                                                                           
   28 root      RT   0     0    0    0 S  0.0  0.0   0:00.00 stopper/6                                                                                             
   29 root      20   0     0    0    0 S  0.0  0.0   0:19.74 ksoftirqd/6                                                                                           
[perumd01@login1 ~]$ top -u perumd01

top - 11:20:16 up 136 days, 3 min, 59 users,  load average: 0.79, 0.59, 0.51
Tasks: 1286 total,   2 running, 1280 sleeping,   4 stopped,   0 zombie
Cpu(s):  2.4%us,  0.5%sy,  0.0%ni, 96.9%id,  0.1%wa,  0.0%hi,  0.0%si,  0.0%st
Mem:  264338188k total, 263653568k used,   684620k free,   206572k buffers
Swap:  4194300k total,  1712968k used,  2481332k free, 237971940k cached

  PID USER      PR  NI  VIRT  RES  SHR S %CPU %MEM    TIME+  COMMAND                                                                                              
 8507 perumd01  20   0 26848 2336 1072 R  7.5  0.0   0:00.05 top                                                                                                   
 8401 perumd01  20   0  116m 2052 1564 S  0.0  0.0   0:00.01 bash                                                                                                  











































[perumd01@login1 ~]$ exit
logout
[root@login1 ~]# su - perumd01
[perumd01@login1 ~]$ exit
logout
[root@login1 ~]# Shared connection to mothra.hpc.mssm.edu closed.
imac:~ gail01$ ssh mothra
Last login: Wed Jun  6 10:05:44 2018 from 10.91.17.183
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
	The /sc/orga/ file system is optimized for performance and
	capacity. It provides minimal redundancy and no backups.

	Data stored in /sc/orga/scratch/ is automatically purged after
	14 days.

	=== Follow us on Twitter @mssmhpc ===
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

***ANNOUNCEMENTS***


2018/06/12, Tuesday, 8AM - 6PM: Minerva Full Maintenance

This PM is scheduled to perform the upgrade of the UPS that provides power 
to the datacenter in the Hess building. This upgrade is necessary to improve 
the safety and reliability of the switchgear while conducting maintenance to 
the UPS equipment. This work will cause a power outage to some equipment in 
the data center, hence for this reason Minerva will be completely shut down 
during this time, i.e., login nodes and file system will not be accessible 
and jobs will not be running.


gail01@login1: ~ $ top

top - 14:41:11 up 141 days,  3:24, 68 users,  load average: 1.53, 2.01, 2.49
Tasks: 1303 total,   2 running, 1299 sleeping,   2 stopped,   0 zombie
Cpu(s):  3.0%us,  1.1%sy,  0.0%ni, 95.8%id,  0.0%wa,  0.0%hi,  0.0%si,  0.0%st

  PID USER      PR  NI  VIRT  RES  SHR S %CPU %MEM    TIME+  COMMAND                                                                                                                                       
32758 fludee01  20   0  195m  93m  804 R 100.0  0.0 387:06.84 xz                                                                                                                                            
26433 preusm01  20   0  820m 340m  12m S 14.5  0.1   0:36.70 R                                                                                                                                              
32757 fludee01  20   0  126m 1308 1076 S  2.0  0.0   5:39.45 tar                                                                                                                                            
38278 gail01    20   0 26856 2496 1168 R  1.0  0.0   0:14.04 top                                                                                                                                            
  193 root      20   0     0    0    0 S  0.3  0.0   4:41.93 events/30                                                                                                                                      
 1754 root      20   0     0    0    0 S  0.3  0.0  28:57.85 mlx4_en                                                                                                                                        
 9231 preusm01  20   0  119m 3708 1088 S  0.3  0.0   0:11.10 sshd                                                                                                                                           
15696 root       0 -20 29.1g 9.0g 780m S  0.3  3.6   5842:16 mmfsd                                                                                                                                          
    1 root      20   0 21428 1328 1104 S  0.0  0.0   0:13.32 init                                                                                                                                           
    2 root      20   0     0    0    0 S  0.0  0.0   0:00.91 kthreadd                                                                                                                                       
    3 root      RT   0     0    0    0 S  0.0  0.0  27:36.47 migration/0                                                                                                                                    
    4 root      20   0     0    0    0 S  0.0  0.0   8:56.84 ksoftirqd/0                                                                                                                                    
    5 root      RT   0     0    0    0 S  0.0  0.0   0:00.00 stopper/0                                                                                                                                      
    6 root      RT   0     0    0    0 S  0.0  0.0   0:29.78 watchdog/0                                                                                                                                     
    7 root      RT   0     0    0    0 S  0.0  0.0   7:43.55 migration/1                                                                                                                                    
    8 root      RT   0     0    0    0 S  0.0  0.0   0:00.00 stopper/1                                                                                                                                      
    9 root      20   0     0    0    0 S  0.0  0.0   1:19.34 ksoftirqd/1                                                                                                                                    
   10 root      RT   0     0    0    0 S  0.0  0.0   0:22.09 watchdog/1                                                                                                                                     
   11 root      RT   0     0    0    0 S  0.0  0.0   4:37.70 migration/2                                                                                                                                    
   12 root      RT   0     0    0    0 S  0.0  0.0   0:00.00 stopper/2                                                                                                                                      
   13 root      20   0     0    0    0 S  0.0  0.0   0:44.15 ksoftirqd/2                                                                                                                                    
   14 root      RT   0     0    0    0 S  0.0  0.0   0:19.20 watchdog/2                                                                                                                                     
   15 root      RT   0     0    0    0 S  0.0  0.0   3:39.81 migration/3                                                                                                                                    
   16 root      RT   0     0    0    0 S  0.0  0.0   0:00.00 stopper/3                                                                                                                                      
   17 root      20   0     0    0    0 S  0.0  0.0   0:30.80 ksoftirqd/3                                                                                                                                    
   18 root      RT   0     0    0    0 S  0.0  0.0   0:17.15 watchdog/3                                                                                                                                     
   19 root      RT   0     0    0    0 S  0.0  0.0   3:06.36 migration/4                                                                                                                                    
   20 root      RT   0     0    0    0 S  0.0  0.0   0:00.00 stopper/4                                                                                                                                      
   21 root      20   0     0    0    0 S  0.0  0.0   0:23.42 ksoftirqd/4                                                                                                                                    
   22 root      RT   0     0    0    0 S  0.0  0.0   0:14.57 watchdog/4                                                                                                                                     
   23 root      RT   0     0    0    0 S  0.0  0.0   2:37.13 migration/5                                                                                                                                    
   24 root      RT   0     0    0    0 S  0.0  0.0   0:00.00 stopper/5                                                                                                                                      
   25 root      20   0     0    0    0 S  0.0  0.0   0:21.14 ksoftirqd/5                                                                                                                                    
   26 root      RT   0     0    0    0 S  0.0  0.0   0:16.27 watchdog/5                                                                                                                                     
   27 root      RT   0     0    0    0 S  0.0  0.0   2:24.42 migration/6                                                                                                                                    
   28 root      RT   0     0    0    0 S  0.0  0.0   0:00.00 stopper/6                                                                                                                                      
   29 root      20   0     0    0    0 S  0.0  0.0   0:20.01 ksoftirqd/6                                                                                                                                    
   30 root      RT   0     0    0    0 S  0.0  0.0   0:14.65 watchdog/6                                                                                                                                     
   31 root      RT   0     0    0    0 S  0.0  0.0   2:33.35 migration/7                                                                                                                                    
gail01@login1: ~ $ cd /hpc/packages/minerva-common/CPAN/5.10.1/lib/perl5/x86_64-linux-thread-multi
gail01@login1: /hpc/packages/minerva-common/CPAN/5.10.1/lib/perl5/x86_64-linux-thread-multi $ ls
Acme       Bio     Cairo     Convert    Data                DateTimePP.pm  dbixs_rev.pl  forks     List          Moose.pm  Params  perllocal.pod  Storable.pm  Template.pm  Time         Want.pm
Algorithm  Bit     Cairo.pm  Crypt      DateTime            DBD            Devel         forks.pm  Math          oose.pm   PDL     Proc           String       Test         version      Win32
Attribute  Bloom   Class     CryptX.pm  DateTime.pm         DBI            Digest        Inline    metaclass.pm  Package   PDL.pm  RNA.pm         Sub          Text         version.pm   YAML
auto       Bundle  Compress  Cwd.pm     DateTimePPExtra.pm  DBI.pm         File          IO        Moose         Parallel  PerlIO  Set            Template     threads      version.pod
gail01@login1: /hpc/packages/minerva-common/CPAN/5.10.1/lib/perl5/x86_64-linux-thread-multi $ cd auto/
gail01@login1: /hpc/packages/minerva-common/CPAN/5.10.1/lib/perl5/x86_64-linux-thread-multi/auto $ ls
cAcme       Astro    Chemistry   CPAN      DBIx    Exception  GD        HTML-TableExtract  JSON             LWP      Parallel  Pegex      POSIX       share        String    Test       UR
Algorithm  Bio      Class       CryptX    Devel   Exporter   Genome    HTTP               Lingua           Math     Params    Perl       PostScript  SOAP         Sub       Text       URI
Apache     Bit      Clone       Cwd       Digest  ExtUtils   Getopt    Ima                List             Module   parent    PerlIO     Probe       Sort         SUPER     Tie        version
App        Bloom    Compress    Data      Dist    File       Graph     Inline             local            Moose    Parse     PerlMol    Proc        Spreadsheet  SVG       Time       Want
AppConfig  Cairo    Config      DateTime  Encode  Filesys    Graphics  install            Locale           Net      Path      PkgConfig  Regexp      Statistics   Sys       Tree       WWW
Archive    Capture  Contextual  DBD       Env     Filter     GraphViz  IO                 Locale-Maketext  Number   PDF       Plack      RNA         Storable     Task      Try        XML
Array      Carp     Convert     DBI       Eval    forks      Hash      IPC                Log              Package  PDL       Pod        Set         Stream       Template  UNIVERSAL  YAML
gail01@login1: /hpc/packages/minerva-common/CPAN/5.10.1/lib/perl5/x86_64-linux-thread-multi/auto $ ls -lt
total 16
drwxrwsr-x  4 fludee01 hpcapps   34 Jun  6 15:55 Parallel
drwxrwsr-x 26 fludee01 hpcapps 4096 Feb 13 14:28 PDL
drwxrwsr-x  4 choh07   hpcapps   39 Jan 18 14:22 Spreadsheet
drwxr-sr-x  3 choh07   hpcapps   16 Jan 18 14:17 Archive
drwxrwsr-x 26 fludee01 hpcapps 4096 Jan 18 14:17 Test
drwxr-sr-x  2 choh07   hpcapps   22 Jan 18 14:17 SUPER
drwxrwsr-x  6 fludee01 hpcapps   61 Jan 18 14:17 Sub
drwxr-sr-x  2 choh07   hpcapps   38 Jan 18 13:47 CryptX
drwxr-sr-x  3 choh07   hpcapps   23 Jan 18 13:46 Graphics
drwxrwsr-x  4 fludee01 hpcapps   43 Nov 29  2017 Inline
drwxrwsr-x  4 choh07   hpcapps   36 Nov 29  2017 Proc
drwxrwsr-x  4 fludee01 hpcapps   27 Nov 29  2017 Digest
drwxrwsr-x 14 fludee01 hpcapps 4096 May 30  2017 Statistics
drwxrwsr-x 13 fludee01 hpcapps  155 May 30  2017 Math
drwxr-sr-x  3 choh07   hpcapps   19 May 30  2017 Contextual
drwxr-sr-x  2 choh07   hpcapps   36 May 30  2017 Want
drwxrwsr-x  7 fludee01 hpcapps   68 May 30  2017 Text
drwxrwsr-x  6 fludee01 hpcapps   50 Jan 20  2017 IPC
drwxr-sr-x  2 choh07   hpcapps   35 Dec 21  2016 RNA
drwxr-sr-x  3 choh07   hpcapps   17 Dec 16  2016 PDF
drwxrwsr-x 13 fludee01 hpcapps  139 Aug 25  2016 File
drwxrwsr-x 10 fludee01 hpcapps  109 Aug 16  2016 XML
drwxrwsr-x  4 fludee01 hpcapps   44 Aug 16  2016 Exporter
drwxrwsr-x  4 fludee01 hpcapps   30 Aug 16  2016 String
drwxrwsr-x  5 fludee01 hpcapps   44 Aug 16  2016 Number
drwxrwsr-x 11 fludee01 hpcapps  142 Jun 28  2016 Bio
drwxrwsr-x  3 gail01   hpcapps   22 Jun 28  2016 Graph
drwxrwsr-x  4 fludee01 hpcapps   32 Jun 28  2016 Array
drwxrwsr-x  5 fludee01 hpcapps   48 Jun 28  2016 PerlIO
drwxrwsr-x  3 gail01   hpcapps   17 Jun 28  2016 Env
drwxrwsr-x  2 gail01   hpcapps   37 Jun 16  2016 Cairo
drwxrwsr-x 10 fludee01 hpcapps  126 Jun 16  2016 ExtUtils
drwxrwsr-x  8 fludee01 hpcapps   93 May 18  2016 IO
drwxrwsr-x  2 choh07   hpcapps   22 Apr  6  2016 Pegex
drwxrwsr-x  4 fludee01 hpcapps   34 Apr  6  2016 Parse
drwxrwsr-x  4 fludee01 hpcapps   45 Apr  6  2016 YAML
drwxrwsr-x  3 fludee01 hpcapps   19 Oct  9  2015 Bloom
drwxrwsr-x  4 fludee01 hpcapps   30 Oct  6  2015 Time
drwxrwsr-x  2 fludee01 hpcapps   22 Aug  7  2015 PkgConfig
drwxrwsr-x  5 fludee01 hpcapps   52 Jun 15  2015 Set
drwxrwsr-x  3 fludee01 hpcapps   34 Jan 23  2015 Genome
drwxrwsr-x  2 fludee01 hpcapps   22 Jan 23  2015 UR
drwxrwsr-x  8 fludee01 hpcapps   97 Jan 23  2015 Data
drwxrwsr-x  2 fludee01 hpcapps   22 Jan 23  2015 Plack
drwxrwsr-x  3 fludee01 hpcapps   19 Jan 23  2015 Filesys
drwxrwsr-x  9 fludee01 hpcapps   96 Jan 23  2015 HTTP
drwxrwsr-x  3 fludee01 hpcapps   22 Jan 23  2015 Apache
drwxrwsr-x  3 fludee01 hpcapps   21 Jan 23  2015 POSIX
drwxrwsr-x  2 fludee01 hpcapps   22 Jan 23  2015 URI
drwxrwsr-x  3 fludee01 hpcapps   23 Jan 23  2015 Hash
drwxrwsr-x  3 fludee01 hpcapps   21 Jan 23  2015 Stream
drwxrwsr-x 11 fludee01 hpcapps  131 Jan 23  2015 Class
drwxrwsr-x  3 fludee01 hpcapps   15 Jan 23  2015 Clone
drwxrwsr-x  3 fludee01 hpcapps   15 Jan 23  2015 Lingua
drwxrwsr-x  3 fludee01 hpcapps   18 Jan 23  2015 Path
drwxrwsr-x  4 fludee01 hpcapps   32 Jan 23  2015 Getopt
drwxrwsr-x  3 fludee01 hpcapps   19 Jan 23  2015 Bit
drwxrwsr-x  2 fludee01 hpcapps   40 Jan 23  2015 Storable
drwxrwsr-x  3 fludee01 hpcapps   19 Jan 23  2015 Regexp
drwxrwsr-x  3 fludee01 hpcapps   17 Jan 23  2015 CPAN
drwxrwsr-x  4 fludee01 hpcapps   28 Jan 23  2015 Convert
drwxrwsr-x  7 fludee01 hpcapps   82 Jan 23  2015 Module
drwxrwsr-x  3 fludee01 hpcapps   17 Jan 23  2015 Astro
drwxrwsr-x  3 fludee01 hpcapps   19 Jan 23  2015 Filter
drwxrwsr-x  6 fludee01 hpcapps   76 Jan 23  2015 Devel
drwxrwsr-x  2 fludee01 hpcapps   22 Jan 20  2015 install
drwxrwsr-x  3 fludee01 hpcapps   16 Nov 21  2014 Ima
drwxrwsr-x  3 fludee01 hpcapps   28 Nov 21  2014 DBIx
drwxrwsr-x  3 fludee01 hpcapps   20 Nov 21  2014 UNIVERSAL
drwxrwsr-x  3 fludee01 hpcapps   21 Nov 18  2014 Log
drwxrwsr-x  2 fludee01 hpcapps   35 Nov 18  2014 Cwd
drwxrwsr-x  3 fludee01 hpcapps   21 Oct 29  2014 Params
drwxrwsr-x  4 fludee01 hpcapps   34 Oct  9  2014 Algorithm
drwxrwsr-x  5 fludee01 hpcapps   48 Oct  9  2014 Config
drwxrwsr-x  3 fludee01 hpcapps   19 Apr 10  2014 Tie
drwxrwsr-x  3 fludee01 hpcapps   22 Apr 10  2014 Sort
drwxrwsr-x  3 fludee01 hpcapps   18 Apr 10  2014 SVG
drwxrwsr-x  3 fludee01 hpcapps   17 Apr 10  2014 SOAP
drwxrwsr-x  3 fludee01 hpcapps   20 Apr 10  2014 PostScript
drwxrwsr-x  2 fludee01 hpcapps   22 Apr 10  2014 HTML-TableExtract
drwxrwsr-x  2 fludee01 hpcapps   22 Apr 10  2014 GraphViz
drwxrwsr-x  3 fludee01 hpcapps   39 Apr 10  2014 LWP
drwxrwsr-x  3 fludee01 hpcapps   23 Apr 10  2014 WWW
drwxrwsr-x  3 fludee01 hpcapps   17 Apr 10  2014 Net
drwxrwsr-x  3 fludee01 hpcapps   16 Apr 10  2014 Compress
drwxrwsr-x  3 fludee01 hpcapps   19 Apr 10  2014 Encode
drwxrwsr-x  3 fludee01 hpcapps   17 Apr 10  2014 Probe
drwxrwsr-x  2 fludee01 hpcapps   37 Apr 10  2014 Moose
drwxrwsr-x  3 fludee01 hpcapps   20 Apr 10  2014 Eval
drwxrwsr-x  2 fludee01 hpcapps   22 Apr 10  2014 parent
drwxrwsr-x  3 fludee01 hpcapps   19 Apr 10  2014 Task
drwxrwsr-x  4 fludee01 hpcapps   43 Apr 10  2014 Package
drwxrwsr-x  3 fludee01 hpcapps   18 Apr  9  2014 Exception
drwxrwsr-x  4 fludee01 hpcapps   29 Apr  9  2014 Acme
drwxrwsr-x  3 fludee01 hpcapps   21 Apr  9  2014 Locale
drwxrwsr-x  2 fludee01 hpcapps   22 Apr  9  2014 Locale-Maketext
drwxrwsr-x  2 fludee01 hpcapps   37 Apr  9  2014 forks
drwxrwsr-x  3 fludee01 hpcapps   21 Apr  9  2014 Tree
drwxrwsr-x  3 fludee01 hpcapps   34 Apr  9  2014 Template
drwxrwsr-x  3 fludee01 hpcapps   22 Apr  9  2014 Sys
drwxrwsr-x  3 fludee01 hpcapps   21 Apr  9  2014 Pod
drwxrwsr-x  2 fludee01 hpcapps   22 Apr  9  2014 PerlMol
drwxrwsr-x  4 fludee01 hpcapps   38 Apr  9  2014 List
drwxrwsr-x  2 fludee01 hpcapps   22 Apr  9  2014 JSON
drwxrwsr-x  4 fludee01 hpcapps   29 Apr  9  2014 GD
drwxrwsr-x  4 fludee01 hpcapps   86 Apr  9  2014 DateTime
drwxrwsr-x  3 fludee01 hpcapps   27 Apr  9  2014 Dist
drwxrwsr-x  3 fludee01 hpcapps   17 Apr  9  2014 Capture
drwxrwsr-x  3 fludee01 hpcapps   17 Apr  9  2014 Try
drwxrwsr-x  2 fludee01 hpcapps 4096 Apr  9  2014 DBI
drwxrwsr-x  3 fludee01 hpcapps   17 Apr  9  2014 share
drwxrwsr-x  3 fludee01 hpcapps   19 Apr  9  2014 DBD
drwxrwsr-x  3 fludee01 hpcapps   16 Apr  9  2014 Chemistry
drwxrwsr-x  2 fludee01 hpcapps   22 Apr  9  2014 Carp
drwxrwsr-x  2 fludee01 hpcapps   22 Apr  9  2014 AppConfig
drwxrwsr-x  3 fludee01 hpcapps   22 Apr  9  2014 App
drwxrwsr-x  3 fludee01 hpcapps   16 Apr  9  2014 local
drwxrwsr-x  3 fludee01 hpcapps   19 Apr  9  2014 Perl
drwxrwsr-x  3 fludee01 hpcapps   32 Apr  9  2014 version
gail01@login1: /hpc/packages/minerva-common/CPAN/5.10.1/lib/perl5/x86_64-linux-thread-multi/auto $ cd Para
Parallel/ Params/   
gail01@login1: /hpc/packages/minerva-common/CPAN/5.10.1/lib/perl5/x86_64-linux-thread-multi/auto $ cd Parallel/
gail01@login1: /hpc/packages/minerva-common/CPAN/5.10.1/lib/perl5/x86_64-linux-thread-multi/auto/Parallel $ ls
ForkManager  MPI
gail01@login1: /hpc/packages/minerva-common/CPAN/5.10.1/lib/perl5/x86_64-linux-thread-multi/auto/Parallel $ cd MPI/
gail01@login1: /hpc/packages/minerva-common/CPAN/5.10.1/lib/perl5/x86_64-linux-thread-multi/auto/Parallel/MPI $ ls
Simple
gail01@login1: /hpc/packages/minerva-common/CPAN/5.10.1/lib/perl5/x86_64-linux-thread-multi/auto/Parallel/MPI $ ls -lt
total 0
drwxr-sr-x 2 gail01 hpcapps 38 Jun  6 15:55 Simple
gail01@login1: /hpc/packages/minerva-common/CPAN/5.10.1/lib/perl5/x86_64-linux-thread-multi/auto/Parallel/MPI $ cd si
-bash: cd: si: No such file or directory
gail01@login1: /hpc/packages/minerva-common/CPAN/5.10.1/lib/perl5/x86_64-linux-thread-multi/auto/Parallel/MPI $ ls
Simple
gail01@login1: /hpc/packages/minerva-common/CPAN/5.10.1/lib/perl5/x86_64-linux-thread-multi/auto/Parallel/MPI $ cd Simple/
gail01@login1: /hpc/packages/minerva-common/CPAN/5.10.1/lib/perl5/x86_64-linux-thread-multi/auto/Parallel/MPI/Simple $ ls
Simple.so
gail01@login1: /hpc/packages/minerva-common/CPAN/5.10.1/lib/perl5/x86_64-linux-thread-multi/auto/Parallel/MPI/Simple $ ls -lt
total 104
-r-xr-xr-x 1 gail01 hpcapps 103595 Jun  6 15:55 Simple.so
gail01@login1: /hpc/packages/minerva-common/CPAN/5.10.1/lib/perl5/x86_64-linux-thread-multi/auto/Parallel/MPI/Simple $ ldd Simple.so 
	linux-vdso.so.1 =>  (0x00007ffd11f95000)
	libc.so.6 => /lib64/libc.so.6 (0x00007f0fdc488000)
	/lib64/ld-linux-x86-64.so.2 (0x0000003e66e00000)
gail01@login1: /hpc/packages/minerva-common/CPAN/5.10.1/lib/perl5/x86_64-linux-thread-multi/auto/Parallel/MPI/Simple $ cd 4
-bash: cd: 4: No such file or directory
gail01@login1: /hpc/packages/minerva-common/CPAN/5.10.1/lib/perl5/x86_64-linux-thread-multi/auto/Parallel/MPI/Simple $ cd4
gail01@login1: /hpc/packages/minerva-common/CPAN/5.10.1/lib/perl5/x86_64-linux-thread-multi $ ls -lt
total 964
-rw-rw-r--   1 fludee01 hpcapps  68271 Jun  6 15:55 perllocal.pod
drwxr-sr-x   3 gail01   hpcapps     16 Jun  6 15:55 Parallel
drwxrwsr-x  19 fludee01 hpcapps   4096 Feb 13 14:28 PDL
drwxrwsr-x 121 fludee01 hpcapps   4096 Jan 18 14:17 auto
drwxrwsr-x   2 fludee01 hpcapps     38 Jan 18 14:17 Sub
drwxr-sr-x  11 choh07   hpcapps   4096 Jan 18 13:47 Crypt
drwxrwsr-x   5 fludee01 hpcapps   4096 Jan 18 13:47 Math
-r--r--r--   1 choh07   hpcapps   4723 Dec 22 08:12 CryptX.pm
drwxrwsr-x   2 fludee01 hpcapps     84 Nov 29  2017 Inline
drwxr-sr-x   3 fludee01 hpcapps     98 Nov 29  2017 Proc
drwxrwsr-x   2 fludee01 hpcapps     33 Nov 29  2017 Digest
drwxrwsr-x   2 fludee01 hpcapps     22 Jun 22  2017 String
-r--r--r--   1 fludee01 hpcapps   6441 May 21  2017 PDL.pm
drwxrwsr-x   2 fludee01 hpcapps     57 Jun 28  2016 PerlIO
drwxrwsr-x   3 gail01   hpcapps     20 Jun 16  2016 Cairo
drwxrwsr-x   5 fludee01 hpcapps   4096 May 18  2016 DBD
drwxrwsr-x   3 choh07   hpcapps     75 Apr  6  2016 YAML
-r--r--r--   1 choh07   hpcapps  18344 Feb 25  2016 Want.pm
drwxrwsr-x   2 fludee01 hpcapps     22 Oct  9  2015 Bloom
drwxrwsr-x   2 fludee01 hpcapps     53 Oct  6  2015 Time
-r--rw-r--   1 gail01   hpcapps  27776 Sep 29  2015 Cairo.pm
drwxrwsr-x   2 fludee01 hpcapps     36 Aug  7  2015 Test
drwxrwsr-x   3 fludee01 hpcapps     42 Jun 15  2015 Set
drwxrwsr-x   2 fludee01 hpcapps     50 Jan 23  2015 Data
drwxrwsr-x   3 fludee01 hpcapps     52 Jan 23  2015 Bit
drwxrwsr-x   3 fludee01 hpcapps     41 Jan 23  2015 List
drwxrwsr-x   3 fludee01 hpcapps     64 Jan 23  2015 File
drwxrwsr-x   2 fludee01 hpcapps     22 Nov 12  2014 Text
drwxrwsr-x   3 fludee01 hpcapps     79 Oct 29  2014 Params
drwxrwsr-x   3 fludee01 hpcapps     19 Oct 29  2014 Attribute
drwxrwsr-x   3 fludee01 hpcapps     37 Oct  9  2014 Algorithm
-rw-rw-r--   1 fludee01 hpcapps  43139 Jun 14  2014 Storable.pm
-rw-rw-r--   1 fludee01 hpcapps  22398 May 23  2014 Cwd.pm
drwxrwsr-x   3 fludee01 hpcapps     15 Apr 10  2014 Bio
drwxrwsr-x   3 fludee01 hpcapps     30 Apr 10  2014 Compress
drwxrwsr-x   4 fludee01 hpcapps     38 Apr 10  2014 IO
drwxrwsr-x   3 fludee01 hpcapps     19 Apr 10  2014 Convert
drwxrwsr-x   8 fludee01 hpcapps   4096 Apr 10  2014 Moose
drwxrwsr-x   4 fludee01 hpcapps     40 Apr 10  2014 Class
drwxrwsr-x   3 fludee01 hpcapps     30 Apr 10  2014 Devel
drwxrwsr-x   4 fludee01 hpcapps     64 Apr  9  2014 forks
drwxrwsr-x   3 fludee01 hpcapps     19 Apr  9  2014 threads
drwxrwsr-x   8 fludee01 hpcapps   4096 Apr  9  2014 Template
drwxrwsr-x   2 fludee01 hpcapps     79 Apr  9  2014 DateTime
-rw-rw-r--   1 fludee01 hpcapps 119751 Apr  9  2014 DateTime.pm
-rw-rw-r--   1 fludee01 hpcapps   1365 Apr  9  2014 DateTimePPExtra.pm
-rw-rw-r--   1 fludee01 hpcapps   5245 Apr  9  2014 DateTimePP.pm
drwxrwsr-x   3 fludee01 hpcapps     18 Apr  9  2014 Package
drwxrwsr-x   2 fludee01 hpcapps     23 Apr  9  2014 Win32
drwxrwsr-x   2 fludee01 hpcapps     19 Apr  9  2014 Bundle
drwxrwsr-x   8 fludee01 hpcapps   4096 Apr  9  2014 DBI
drwxrwsr-x   2 fludee01 hpcapps     20 Apr  9  2014 Acme
drwxrwsr-x   2 fludee01 hpcapps     67 Apr  9  2014 version
-rw-rw-r--   1 fludee01 hpcapps   3459 Feb  6  2014 metaclass.pm
-rw-rw-r--   1 fludee01 hpcapps  38750 Feb  6  2014 Moose.pm
-rw-rw-r--   1 fludee01 hpcapps   2748 Feb  6  2014 oose.pm
-rw-rw-r--   1 fludee01 hpcapps   2923 Feb  3  2014 version.pm
-rw-rw-r--   1 fludee01 hpcapps 313719 Jan  8  2014 DBI.pm
-rw-rw-r--   1 fludee01 hpcapps   9852 Aug 16  2013 version.pod
-rw-rw-r--   1 fludee01 hpcapps  25038 Jul 24  2013 Template.pm
-rw-rw-r--   1 fludee01 hpcapps   1533 Apr  4  2013 dbixs_rev.pl
-rw-rw-r--   1 fludee01 hpcapps 157326 Jun 14  2010 forks.pm
-r--r--r--   1 choh07   hpcapps  37894 Jun 29  2009 RNA.pm
gail01@login1: /hpc/packages/minerva-common/CPAN/5.10.1/lib/perl5/x86_64-linux-thread-multi $ ls -lt |hea
-bash: hea: command not found
gail01@login1: /hpc/packages/minerva-common/CPAN/5.10.1/lib/perl5/x86_64-linux-thread-multi $ ls -lt |head
total 964
-rw-rw-r--   1 fludee01 hpcapps  68271 Jun  6 15:55 perllocal.pod
drwxr-sr-x   3 gail01   hpcapps     16 Jun  6 15:55 Parallel
drwxrwsr-x  19 fludee01 hpcapps   4096 Feb 13 14:28 PDL
drwxrwsr-x 121 fludee01 hpcapps   4096 Jan 18 14:17 auto
drwxrwsr-x   2 fludee01 hpcapps     38 Jan 18 14:17 Sub
drwxr-sr-x  11 choh07   hpcapps   4096 Jan 18 13:47 Crypt
drwxrwsr-x   5 fludee01 hpcapps   4096 Jan 18 13:47 Math
-r--r--r--   1 choh07   hpcapps   4723 Dec 22 08:12 CryptX.pm
drwxrwsr-x   2 fludee01 hpcapps     84 Nov 29  2017 Inline
gail01@login1: /hpc/packages/minerva-common/CPAN/5.10.1/lib/perl5/x86_64-linux-thread-multi $ cd auto/
gail01@login1: /hpc/packages/minerva-common/CPAN/5.10.1/lib/perl5/x86_64-linux-thread-multi/auto $ ls
Acme       Astro    Chemistry   CPAN      DBIx    Exception  GD        HTML-TableExtract  JSON             LWP      Parallel  Pegex      POSIX       share        String    Test       UR
Algorithm  Bio      Class       CryptX    Devel   Exporter   Genome    HTTP               Lingua           Math     Params    Perl       PostScript  SOAP         Sub       Text       URI
Apache     Bit      Clone       Cwd       Digest  ExtUtils   Getopt    Ima                List             Module   parent    PerlIO     Probe       Sort         SUPER     Tie        version
App        Bloom    Compress    Data      Dist    File       Graph     Inline             local            Moose    Parse     PerlMol    Proc        Spreadsheet  SVG       Time       Want
AppConfig  Cairo    Config      DateTime  Encode  Filesys    Graphics  install            Locale           Net      Path      PkgConfig  Regexp      Statistics   Sys       Tree       WWW
Archive    Capture  Contextual  DBD       Env     Filter     GraphViz  IO                 Locale-Maketext  Number   PDF       Plack      RNA         Storable     Task      Try        XML
Array      Carp     Convert     DBI       Eval    forks      Hash      IPC                Log              Package  PDL       Pod        Set         Stream       Template  UNIVERSAL  YAML
gail01@login1: /hpc/packages/minerva-common/CPAN/5.10.1/lib/perl5/x86_64-linux-thread-multi/auto $ ls -lt |head
total 16
drwxrwsr-x  4 fludee01 hpcapps   34 Jun  6 15:55 Parallel
drwxrwsr-x 26 fludee01 hpcapps 4096 Feb 13 14:28 PDL
drwxrwsr-x  4 choh07   hpcapps   39 Jan 18 14:22 Spreadsheet
drwxr-sr-x  3 choh07   hpcapps   16 Jan 18 14:17 Archive
drwxrwsr-x 26 fludee01 hpcapps 4096 Jan 18 14:17 Test
drwxr-sr-x  2 choh07   hpcapps   22 Jan 18 14:17 SUPER
drwxrwsr-x  6 fludee01 hpcapps   61 Jan 18 14:17 Sub
drwxr-sr-x  2 choh07   hpcapps   38 Jan 18 13:47 CryptX
drwxr-sr-x  3 choh07   hpcapps   23 Jan 18 13:46 Graphics
gail01@login1: /hpc/packages/minerva-common/CPAN/5.10.1/lib/perl5/x86_64-linux-thread-multi/auto $ mkdir baklili
gail01@login1: /hpc/packages/minerva-common/CPAN/5.10.1/lib/perl5/x86_64-linux-thread-multi/auto $ cd baklili
gail01@login1: /hpc/packages/minerva-common/CPAN/5.10.1/lib/perl5/x86_64-linux-thread-multi/auto/baklili $ mv ../Parallel .
gail01@login1: /hpc/packages/minerva-common/CPAN/5.10.1/lib/perl5/x86_64-linux-thread-multi/auto/baklili $ ls
Parallel
gail01@login1: /hpc/packages/minerva-common/CPAN/5.10.1/lib/perl5/x86_64-linux-thread-multi/auto/baklili $ cd ..
gail01@login1: /hpc/packages/minerva-common/CPAN/5.10.1/lib/perl5/x86_64-linux-thread-multi/auto $ ls -lt |head
total 16
drwxr-sr-x  3 gail01   hpcapps   21 Jun  6 16:11 baklili
drwxrwsr-x 26 fludee01 hpcapps 4096 Feb 13 14:28 PDL
drwxrwsr-x  4 choh07   hpcapps   39 Jan 18 14:22 Spreadsheet
drwxr-sr-x  3 choh07   hpcapps   16 Jan 18 14:17 Archive
drwxrwsr-x 26 fludee01 hpcapps 4096 Jan 18 14:17 Test
drwxr-sr-x  2 choh07   hpcapps   22 Jan 18 14:17 SUPER
drwxrwsr-x  6 fludee01 hpcapps   61 Jan 18 14:17 Sub
drwxr-sr-x  2 choh07   hpcapps   38 Jan 18 13:47 CryptX
drwxr-sr-x  3 choh07   hpcapps   23 Jan 18 13:46 Graphics
gail01@login1: /hpc/packages/minerva-common/CPAN/5.10.1/lib/perl5/x86_64-linux-thread-multi/auto $ cd ..
gail01@login1: /hpc/packages/minerva-common/CPAN/5.10.1/lib/perl5/x86_64-linux-thread-multi $ mkdir baklili
gail01@login1: /hpc/packages/minerva-common/CPAN/5.10.1/lib/perl5/x86_64-linux-thread-multi $ cd baklili/
gail01@login1: /hpc/packages/minerva-common/CPAN/5.10.1/lib/perl5/x86_64-linux-thread-multi/baklili $ mv ../Para
Parallel/ Params/   
gail01@login1: /hpc/packages/minerva-common/CPAN/5.10.1/lib/perl5/x86_64-linux-thread-multi/baklili $ cd ..
gail01@login1: /hpc/packages/minerva-common/CPAN/5.10.1/lib/perl5/x86_64-linux-thread-multi $ cd Parallel/
gail01@login1: /hpc/packages/minerva-common/CPAN/5.10.1/lib/perl5/x86_64-linux-thread-multi/Parallel $ ls
MPI
gail01@login1: /hpc/packages/minerva-common/CPAN/5.10.1/lib/perl5/x86_64-linux-thread-multi/Parallel $ ls -lt
total 0
drwxr-sr-x 2 gail01 hpcapps 34 Jun  6 15:55 MPI
gail01@login1: /hpc/packages/minerva-common/CPAN/5.10.1/lib/perl5/x86_64-linux-thread-multi/Parallel $ cd ..
gail01@login1: /hpc/packages/minerva-common/CPAN/5.10.1/lib/perl5/x86_64-linux-thread-multi $ cd baklili/
gail01@login1: /hpc/packages/minerva-common/CPAN/5.10.1/lib/perl5/x86_64-linux-thread-multi/baklili $ mv ../Parallel .
gail01@login1: /hpc/packages/minerva-common/CPAN/5.10.1/lib/perl5/x86_64-linux-thread-multi/baklili $ cd ..
gail01@login1: /hpc/packages/minerva-common/CPAN/5.10.1/lib/perl5/x86_64-linux-thread-multi $ ls -lt |head
total 964
drwxr-sr-x   3 gail01   hpcapps     21 Jun  6 16:11 baklili
drwxrwsr-x 121 fludee01 hpcapps   4096 Jun  6 16:11 auto
-rw-rw-r--   1 fludee01 hpcapps  68271 Jun  6 15:55 perllocal.pod
drwxrwsr-x  19 fludee01 hpcapps   4096 Feb 13 14:28 PDL
drwxrwsr-x   2 fludee01 hpcapps     38 Jan 18 14:17 Sub
drwxr-sr-x  11 choh07   hpcapps   4096 Jan 18 13:47 Crypt
drwxrwsr-x   5 fludee01 hpcapps   4096 Jan 18 13:47 Math
-r--r--r--   1 choh07   hpcapps   4723 Dec 22 08:12 CryptX.pm
drwxrwsr-x   2 fludee01 hpcapps     84 Nov 29  2017 Inline
gail01@login1: /hpc/packages/minerva-common/CPAN/5.10.1/lib/perl5/x86_64-linux-thread-multi $ cd baklili/
gail01@login1: /hpc/packages/minerva-common/CPAN/5.10.1/lib/perl5/x86_64-linux-thread-multi/baklili $ mv ../perllocal.pod .
gail01@login1: /hpc/packages/minerva-common/CPAN/5.10.1/lib/perl5/x86_64-linux-thread-multi/baklili $ ls
Parallel  perllocal.pod
gail01@login1: /hpc/packages/minerva-common/CPAN/5.10.1/lib/perl5/x86_64-linux-thread-multi/baklili $ cd ..
gail01@login1: /hpc/packages/minerva-common/CPAN/5.10.1/lib/perl5/x86_64-linux-thread-multi $ ls -lt
total 896
drwxr-sr-x   3 gail01   hpcapps     41 Jun  6 16:12 baklili
drwxrwsr-x 121 fludee01 hpcapps   4096 Jun  6 16:11 auto
drwxrwsr-x  19 fludee01 hpcapps   4096 Feb 13 14:28 PDL
drwxrwsr-x   2 fludee01 hpcapps     38 Jan 18 14:17 Sub
drwxr-sr-x  11 choh07   hpcapps   4096 Jan 18 13:47 Crypt
drwxrwsr-x   5 fludee01 hpcapps   4096 Jan 18 13:47 Math
-r--r--r--   1 choh07   hpcapps   4723 Dec 22 08:12 CryptX.pm
drwxrwsr-x   2 fludee01 hpcapps     84 Nov 29  2017 Inline
drwxr-sr-x   3 fludee01 hpcapps     98 Nov 29  2017 Proc
drwxrwsr-x   2 fludee01 hpcapps     33 Nov 29  2017 Digest
drwxrwsr-x   2 fludee01 hpcapps     22 Jun 22  2017 String
-r--r--r--   1 fludee01 hpcapps   6441 May 21  2017 PDL.pm
drwxrwsr-x   2 fludee01 hpcapps     57 Jun 28  2016 PerlIO
drwxrwsr-x   3 gail01   hpcapps     20 Jun 16  2016 Cairo
drwxrwsr-x   5 fludee01 hpcapps   4096 May 18  2016 DBD
drwxrwsr-x   3 choh07   hpcapps     75 Apr  6  2016 YAML
-r--r--r--   1 choh07   hpcapps  18344 Feb 25  2016 Want.pm
drwxrwsr-x   2 fludee01 hpcapps     22 Oct  9  2015 Bloom
drwxrwsr-x   2 fludee01 hpcapps     53 Oct  6  2015 Time
-r--rw-r--   1 gail01   hpcapps  27776 Sep 29  2015 Cairo.pm
drwxrwsr-x   2 fludee01 hpcapps     36 Aug  7  2015 Test
drwxrwsr-x   3 fludee01 hpcapps     42 Jun 15  2015 Set
drwxrwsr-x   2 fludee01 hpcapps     50 Jan 23  2015 Data
drwxrwsr-x   3 fludee01 hpcapps     52 Jan 23  2015 Bit
drwxrwsr-x   3 fludee01 hpcapps     41 Jan 23  2015 List
drwxrwsr-x   3 fludee01 hpcapps     64 Jan 23  2015 File
drwxrwsr-x   2 fludee01 hpcapps     22 Nov 12  2014 Text
drwxrwsr-x   3 fludee01 hpcapps     79 Oct 29  2014 Params
drwxrwsr-x   3 fludee01 hpcapps     19 Oct 29  2014 Attribute
drwxrwsr-x   3 fludee01 hpcapps     37 Oct  9  2014 Algorithm
-rw-rw-r--   1 fludee01 hpcapps  43139 Jun 14  2014 Storable.pm
-rw-rw-r--   1 fludee01 hpcapps  22398 May 23  2014 Cwd.pm
drwxrwsr-x   3 fludee01 hpcapps     15 Apr 10  2014 Bio
drwxrwsr-x   3 fludee01 hpcapps     30 Apr 10  2014 Compress
drwxrwsr-x   4 fludee01 hpcapps     38 Apr 10  2014 IO
drwxrwsr-x   3 fludee01 hpcapps     19 Apr 10  2014 Convert
drwxrwsr-x   8 fludee01 hpcapps   4096 Apr 10  2014 Moose
drwxrwsr-x   4 fludee01 hpcapps     40 Apr 10  2014 Class
drwxrwsr-x   3 fludee01 hpcapps     30 Apr 10  2014 Devel
drwxrwsr-x   4 fludee01 hpcapps     64 Apr  9  2014 forks
drwxrwsr-x   3 fludee01 hpcapps     19 Apr  9  2014 threads
drwxrwsr-x   8 fludee01 hpcapps   4096 Apr  9  2014 Template
drwxrwsr-x   2 fludee01 hpcapps     79 Apr  9  2014 DateTime
-rw-rw-r--   1 fludee01 hpcapps 119751 Apr  9  2014 DateTime.pm
-rw-rw-r--   1 fludee01 hpcapps   1365 Apr  9  2014 DateTimePPExtra.pm
-rw-rw-r--   1 fludee01 hpcapps   5245 Apr  9  2014 DateTimePP.pm
drwxrwsr-x   3 fludee01 hpcapps     18 Apr  9  2014 Package
drwxrwsr-x   2 fludee01 hpcapps     23 Apr  9  2014 Win32
drwxrwsr-x   2 fludee01 hpcapps     19 Apr  9  2014 Bundle
drwxrwsr-x   8 fludee01 hpcapps   4096 Apr  9  2014 DBI
drwxrwsr-x   2 fludee01 hpcapps     20 Apr  9  2014 Acme
drwxrwsr-x   2 fludee01 hpcapps     67 Apr  9  2014 version
-rw-rw-r--   1 fludee01 hpcapps   3459 Feb  6  2014 metaclass.pm
-rw-rw-r--   1 fludee01 hpcapps  38750 Feb  6  2014 Moose.pm
-rw-rw-r--   1 fludee01 hpcapps   2748 Feb  6  2014 oose.pm
-rw-rw-r--   1 fludee01 hpcapps   2923 Feb  3  2014 version.pm
-rw-rw-r--   1 fludee01 hpcapps 313719 Jan  8  2014 DBI.pm
-rw-rw-r--   1 fludee01 hpcapps   9852 Aug 16  2013 version.pod
-rw-rw-r--   1 fludee01 hpcapps  25038 Jul 24  2013 Template.pm
-rw-rw-r--   1 fludee01 hpcapps   1533 Apr  4  2013 dbixs_rev.pl
-rw-rw-r--   1 fludee01 hpcapps 157326 Jun 14  2010 forks.pm
-r--r--r--   1 choh07   hpcapps  37894 Jun 29  2009 RNA.pm
gail01@login1: /hpc/packages/minerva-common/CPAN/5.10.1/lib/perl5/x86_64-linux-thread-multi $ ls -lt |head
total 896
drwxrwsr-x 121 fludee01 hpcapps   4096 Jun  6 16:11 auto
drwxrwsr-x  19 fludee01 hpcapps   4096 Feb 13 14:28 PDL
drwxrwsr-x   2 fludee01 hpcapps     38 Jan 18 14:17 Sub
drwxr-sr-x  11 choh07   hpcapps   4096 Jan 18 13:47 Crypt
drwxrwsr-x   5 fludee01 hpcapps   4096 Jan 18 13:47 Math
-r--r--r--   1 choh07   hpcapps   4723 Dec 22 08:12 CryptX.pm
drwxrwsr-x   2 fludee01 hpcapps     84 Nov 29  2017 Inline
drwxr-sr-x   3 fludee01 hpcapps     98 Nov 29  2017 Proc
drwxrwsr-x   2 fludee01 hpcapps     33 Nov 29  2017 Digest
gail01@login1: /hpc/packages/minerva-common/CPAN/5.10.1/lib/perl5/x86_64-linux-thread-multi $ cd auto/
gail01@login1: /hpc/packages/minerva-common/CPAN/5.10.1/lib/perl5/x86_64-linux-thread-multi/auto $ ls
Acme       Astro    Carp        Convert   DBI     Eval       forks     Hash               IPC              Log     Package  Pegex      POSIX       share        String    Test       UR
Algorithm  baklili  Chemistry   CPAN      DBIx    Exception  GD        HTML-TableExtract  JSON             LWP     Params   Perl       PostScript  SOAP         Sub       Text       URI
Apache     Bio      Class       CryptX    Devel   Exporter   Genome    HTTP               Lingua           Math    parent   PerlIO     Probe       Sort         SUPER     Tie        version
App        Bit      Clone       Cwd       Digest  ExtUtils   Getopt    Ima                List             Module  Parse    PerlMol    Proc        Spreadsheet  SVG       Time       Want
AppConfig  Bloom    Compress    Data      Dist    File       Graph     Inline             local            Moose   Path     PkgConfig  Regexp      Statistics   Sys       Tree       WWW
Archive    Cairo    Config      DateTime  Encode  Filesys    Graphics  install            Locale           Net     PDF      Plack      RNA         Storable     Task      Try        XML
Array      Capture  Contextual  DBD       Env     Filter     GraphViz  IO                 Locale-Maketext  Number  PDL      Pod        Set         Stream       Template  UNIVERSAL  YAML
gail01@login1: /hpc/packages/minerva-common/CPAN/5.10.1/lib/perl5/x86_64-linux-thread-multi/auto $ ls -lt |head
total 16
drwxr-sr-x  3 gail01   hpcapps   21 Jun  6 16:11 baklili
drwxrwsr-x 26 fludee01 hpcapps 4096 Feb 13 14:28 PDL
drwxrwsr-x  4 choh07   hpcapps   39 Jan 18 14:22 Spreadsheet
drwxr-sr-x  3 choh07   hpcapps   16 Jan 18 14:17 Archive
drwxrwsr-x 26 fludee01 hpcapps 4096 Jan 18 14:17 Test
drwxr-sr-x  2 choh07   hpcapps   22 Jan 18 14:17 SUPER
drwxrwsr-x  6 fludee01 hpcapps   61 Jan 18 14:17 Sub
drwxr-sr-x  2 choh07   hpcapps   38 Jan 18 13:47 CryptX
drwxr-sr-x  3 choh07   hpcapps   23 Jan 18 13:46 Graphics
gail01@login1: /hpc/packages/minerva-common/CPAN/5.10.1/lib/perl5/x86_64-linux-thread-multi/auto $ cd ..
gail01@login1: /hpc/packages/minerva-common/CPAN/5.10.1/lib/perl5/x86_64-linux-thread-multi $ ls -lt |head
total 896
drwxrwsr-x 121 fludee01 hpcapps   4096 Jun  6 16:11 auto
drwxrwsr-x  19 fludee01 hpcapps   4096 Feb 13 14:28 PDL
drwxrwsr-x   2 fludee01 hpcapps     38 Jan 18 14:17 Sub
drwxr-sr-x  11 choh07   hpcapps   4096 Jan 18 13:47 Crypt
drwxrwsr-x   5 fludee01 hpcapps   4096 Jan 18 13:47 Math
-r--r--r--   1 choh07   hpcapps   4723 Dec 22 08:12 CryptX.pm
drwxrwsr-x   2 fludee01 hpcapps     84 Nov 29  2017 Inline
drwxr-sr-x   3 fludee01 hpcapps     98 Nov 29  2017 Proc
drwxrwsr-x   2 fludee01 hpcapps     33 Nov 29  2017 Digest
gail01@login1: /hpc/packages/minerva-common/CPAN/5.10.1/lib/perl5/x86_64-linux-thread-multi $ cd ..
gail01@login1: /hpc/packages/minerva-common/CPAN/5.10.1/lib/perl5 $ ls -lt |head
total 684
drwxrwsr-x 45 fludee01 hpcapps  4096 Jun  6 16:16 x86_64-linux-thread-multi
drwxrwsr-x  4 fludee01 hpcapps    68 Feb 13 09:43 App
drwxrwsr-x  5 choh07   hpcapps   103 Jan 18 14:22 Spreadsheet
drwxr-sr-x  3 choh07   hpcapps    29 Jan 18 14:17 Archive
drwxrwsr-x 12 fludee01 hpcapps  4096 Jan 18 14:17 Test
-r--r--r--  1 choh07   hpcapps  6757 Jan 18 14:17 SUPER.pm
drwxr-sr-x  2 choh07   hpcapps    26 Jan 18 13:46 Graphics
drwxrwsr-x  4 fludee01 hpcapps  4096 Aug 25  2017 Module
drwxrwsr-x  2 fludee01 hpcapps    19 Aug 24  2017 local
gail01@login1: /hpc/packages/minerva-common/CPAN/5.10.1/lib/perl5 $ cd ..
gail01@login1: /hpc/packages/minerva-common/CPAN/5.10.1/lib $ ls
perl5
gail01@login1: /hpc/packages/minerva-common/CPAN/5.10.1/lib $ cd ..
gail01@login1: /hpc/packages/minerva-common/CPAN/5.10.1 $ ls -lt |head
total 27096
drwxrwsr-x 2 fludee01 hpcapps     8192 Feb 13 09:54 bin
drwxrwsr-x 4 fludee01 hpcapps       50 May 30  2017 src
drwxrwsr-x 6 fludee01 hpcapps     4096 Jan 29  2016 build
-rw-rw-r-- 1 fludee01 hpcapps      110 Jan 29  2016 histfile
-rw-rw-r-- 1 fludee01 hpcapps     2341 Jan 29  2016 FTPstats.yml
drwxrwsr-x 2 fludee01 hpcapps        6 Jan 29  2016 prefs
-rw-rw-r-- 1 fludee01 hpcapps 27720761 Jan 29  2016 Metadata
drwxrwsr-x 4 fludee01 hpcapps       34 Jan 29  2016 sources
drwxrwsr-x 4 fludee01 hpcapps       28 Apr  9  2014 man
gail01@login1: /hpc/packages/minerva-common/CPAN/5.10.1 $ cd bin
gail01@login1: /hpc/packages/minerva-common/CPAN/5.10.1/bin $ ls -lt |head
total 3556
-r-xr-xr-x 1 fludee01 hpcapps  40399 Feb 13 09:53 perldl
-r-xr-xr-x 1 fludee01 hpcapps 305334 Feb 13 09:43 cpanm
-r-xr-xr-x 1 choh07   hpcapps   1043 Jan 18 14:17 crc32
-r-xr-xr-x 1 fludee01 hpcapps   7138 Aug 25  2017 config_data
lrwxrwxrwx 1 choh07   hpcapps     19 Aug 11  2017 bp_pg_bulk_load_gff.pl -> bp_bulk_load_gff.pl
-r-xr-xr-x 1 choh07   hpcapps   2809 Aug 11  2017 bp_aacomp.pl
-r-xr-xr-x 1 choh07   hpcapps  15347 Aug 11  2017 bp_biblio.pl
-r-xr-xr-x 1 choh07   hpcapps   8313 Aug 11  2017 bp_biofetch_genbank_proxy.pl
-r-xr-xr-x 1 choh07   hpcapps   3674 Aug 11  2017 bp_bioflat_index.pl
gail01@login1: /hpc/packages/minerva-common/CPAN/5.10.1/bin $ Shared connection to mothra.hpc.mssm.edu closed.
imac:~ gail01$ ssh
  [Restored Nov 19, 2018, 9:36:36 AM]
Last login: Mon Nov 19 09:36:36 on ttys081
Restored session: Mon Nov 19 09:33:48 EST 2018
imac:~ gail01$ 
  [Restored Dec 11, 2018, 9:12:09 AM]
Last login: Tue Dec 11 09:12:09 on ttys086
imac:~ gail01$ 
  [Restored Dec 12, 2018, 9:19:11 AM]
Last login: Wed Dec 12 09:19:11 on ttys068
imac:~ gail01$ 
  [Restored Jan 4, 2019, 9:21:07 AM]
Last login: Fri Jan  4 09:21:07 on ttys068
imac:~ gail01$ ccccccgghrhkeukrgvegduuvfbkduddifrkfucekndnl
-bash: ccccccgghrhkeukrgvegduuvfbkduddifrkfucekndnl: command not found
imac:~ gail01$ ccccccgghrhkgdngllgibnkbiekidvtiugbdgdkurrjk
-bash: ccccccgghrhkgdngllgibnkbiekidvtiugbdgdkurrjk: command not found
imac:~ gail01$ ccccccgghrhkgdngllgibnkbiekidvtiugbdgdkurrjk
-bash: ccccccgghrhkgdngllgibnkbiekidvtiugbdgdkurrjk: command not found
imac:~ gail01$ ssh mothra
Last login: Thu Jan 10 13:04:06 2019 from imac.1425mad.mssm.edu
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
	The /sc/orga/ file system is optimized for performance and
	capacity. It provides minimal redundancy and no backups.

	Data stored in /sc/orga/scratch/ is automatically purged after
	14 days.

	===    Follow us on Twitter @mssmhpc    ===
    === Send ticket to hpchelp@hpc.mssm.edu ===
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

cgail01@login1: ~ $ cd /sc/orga/packages/lili_tem/R/3.5.
3.5.1/ 3.5.2/ 
gail01@login1: ~ $ cd /sc/orga/packages/lili_tem/R/3.5.2
gail01@login1: /sc/orga/packages/lili_tem/R/3.5.2 $ ls
bin  lib64  new  R-3.5.2  R-3.5.2.tar.gz  share
gail01@login1: /sc/orga/packages/lili_tem/R/3.5.2 $ cd2
gail01@login1: /sc/orga/packages/lili_tem $ s
-bash: s: command not found
gail01@login1: /sc/orga/packages/lili_tem $ ls
ana-test  blcr_make  lmod  my-rdkit-env  pkg     R         rosetta                                 rosetta_bin_linux_3.9_bundle.tgz  temp           used
backup    ebtest     lua   pei           prokka  rgi_card  rosetta_bin_linux_2018.09.60072_bundle  seuratprj                         t_modulefiles  usertest
gail01@login1: /sc/orga/packages/lili_tem $ cd t_modulefiles/
gail01@login1: /sc/orga/packages/lili_tem/t_modulefiles $ ls
fsl  R
gail01@login1: /sc/orga/packages/lili_tem/t_modulefiles $ cd R
gail01@login1: /sc/orga/packages/lili_tem/t_modulefiles/R $ ls
3.5.2  t_3.3.0  t_3.5.2
gail01@login1: /sc/orga/packages/lili_tem/t_modulefiles/R $ vi 3.5.2
gail01@login1: /sc/orga/packages/lili_tem/t_modulefiles/R $ vi 3.5.2
gail01@login1: /sc/orga/packages/lili_tem/t_modulefiles/R $ ls
3.5.2  t_3.3.0  t_3.5.2
gail01@login1: /sc/orga/packages/lili_tem/t_modulefiles/R $ cd ..
gail01@login1: /sc/orga/packages/lili_tem/t_modulefiles $ ls
fsl  R
gail01@login1: /sc/orga/packages/lili_tem/t_modulefiles $ cd fsl
gail01@login1: /sc/orga/packages/lili_tem/t_modulefiles/fsl $ ls
6
gail01@login1: /sc/orga/packages/lili_tem/t_modulefiles/fsl $ vi 6 
gail01@login1: /sc/orga/packages/lili_tem/t_modulefiles/fsl $ rpm -qa | grep libX11
libX11-1.6.4-3.el6.x86_64
libX11-devel-1.6.4-3.el6.x86_64
libX11-common-1.6.4-3.el6.noarch
libX11-1.6.4-3.el6.i686
gail01@login1: /sc/orga/packages/lili_tem/t_modulefiles/fsl $ rpm -qa | grep libX11
libX11-1.6.4-3.el6.x86_64
libX11-devel-1.6.4-3.el6.x86_64
libX11-common-1.6.4-3.el6.noarch
libX11-1.6.4-3.el6.i686
gail01@login1: /sc/orga/packages/lili_tem/t_modulefiles/fsl $ ssh node7-1
Last login: Fri Jan 11 10:45:38 2019 from 172.29.39.3
gail01@node7-1: ~ $ cd /hpc/packages/minerva-centos7/python/3.7.1/src/Python-3.7.1
gail01@node7-1: /hpc/packages/minerva-centos7/python/3.7.1/src/Python-3.7.1 $ module load gcc/7.3.0
gail01@node7-1: /hpc/packages/minerva-centos7/python/3.7.1/src/Python-3.7.1 $ ./configure --prefix=/hpc/packages/minerva-centos7/python/3.7.1 --enable-shared --with-lto --with-ensurepip=install --enable-optimizations
checking build system type... x86_64-pc-linux-gnu
checking host system type... x86_64-pc-linux-gnu
checking for python3.7... no
checking for python3... no
checking for python... python
checking for --enable-universalsdk... no
checking for --with-universal-archs... no
checking MACHDEP... checking for --without-gcc... no
checking for --with-icc... no
checking for gcc... gcc
checking whether the C compiler works... yes
checking for C compiler default output file name... a.out
checking for suffix of executables... 
checking whether we are cross compiling... no
checking for suffix of object files... o
checking whether we are using the GNU C compiler... yes
checking whether gcc accepts -g... yes
checking for gcc option to accept ISO C89... none needed
checking how to run the C preprocessor... gcc -E
checking for grep that handles long lines and -e... /usr/bin/grep
checking for a sed that does not truncate output... /usr/bin/sed
checking for --with-cxx-main=<compiler>... no
checking for g++... no
configure:

  By default, distutils will build C++ extension modules with "g++".
  If this is not intended, then set CXX on the configure command line.
  
checking for the platform triplet based on compiler characteristics... x86_64-linux-gnu
checking for -Wl,--no-as-needed... yes
checking for egrep... /usr/bin/grep -E
checking for ANSI C header files... yes
checking for sys/types.h... yes
checking for sys/stat.h... yes
checking for stdlib.h... yes
checking for string.h... yes
checking for memory.h... yes
checking for strings.h... yes
checking for inttypes.h... yes
checking for stdint.h... yes
checking for unistd.h... yes
checking minix/config.h usability... no
checking minix/config.h presence... no
checking for minix/config.h... no
checking whether it is safe to define __EXTENSIONS__... yes
checking for the Android API level... not Android
checking for --with-suffix... 
checking for case-insensitive build directory... no
checking LIBRARY... libpython$(VERSION)$(ABIFLAGS).a
checking LINKCC... $(PURIFY) $(MAINCC)
checking for GNU ld... yes
checking for --enable-shared... yes
checking for --enable-profiling... no
checking LDLIBRARY... libpython$(LDVERSION).so
checking for ar... ar
checking for readelf... readelf
checking for a BSD-compatible install... /usr/bin/install -c
checking for a thread-safe mkdir -p... /usr/bin/mkdir -p
checking for --with-pydebug... no
checking for --with-assertions... no
checking for --enable-optimizations... yes
checking for --with-lto... yes
checking target system type... x86_64-pc-linux-gnu
checking for -llvm-profdata... no
checking for llvm-profdata... ''
checking for -Wextra... yes
checking whether gcc accepts and needs -fno-strict-aliasing... no
checking if we can turn off gcc unused result warning... yes
checking if we can turn off gcc unused parameter warning... yes
checking if we can turn off gcc missing field initializers warning... yes
checking if we can turn off gcc invalid function cast warning... no
checking if we can turn on gcc mixed sign comparison warning... yes
checking if we can turn on gcc unreachable code warning... no
checking if we can turn on gcc strict-prototypes warning... no
checking if we can make implicit function declaration an error in gcc... yes
checking whether pthreads are available without options... no
checking whether gcc accepts -Kpthread... no
checking whether gcc accepts -Kthread... no
checking whether gcc accepts -pthread... no
checking whether g++ also accepts flags for thread support... no
checking for ANSI C header files... (cached) yes
checking asm/types.h usability... yes
checking asm/types.h presence... yes
checking for asm/types.h... yes
checking crypt.h usability... yes
checking crypt.h presence... yes
checking for crypt.h... yes
checking conio.h usability... no
checking conio.h presence... no
checking for conio.h... no
checking direct.h usability... no
checking direct.h presence... no
checking for direct.h... no
checking dlfcn.h usability... yes
checking dlfcn.h presence... yes
checking for dlfcn.h... yes
checking errno.h usability... yes
checking errno.h presence... yes
checking for errno.h... yes
checking fcntl.h usability... yes
checking fcntl.h presence... yes
checking for fcntl.h... yes
checking grp.h usability... yes
checking grp.h presence... yes
checking for grp.h... yes
checking ieeefp.h usability... no
checking ieeefp.h presence... no
checking for ieeefp.h... no
checking io.h usability... no
checking io.h presence... no
checking for io.h... no
checking langinfo.h usability... yes
checking langinfo.h presence... yes
checking for langinfo.h... yes
checking libintl.h usability... yes
checking libintl.h presence... yes
checking for libintl.h... yes
checking process.h usability... no
checking process.h presence... no
checking for process.h... no
checking pthread.h usability... yes
checking pthread.h presence... yes
checking for pthread.h... yes
checking sched.h usability... yes
checking sched.h presence... yes
checking for sched.h... yes
checking shadow.h usability... yes
checking shadow.h presence... yes
checking for shadow.h... yes
checking signal.h usability... yes
checking signal.h presence... yes
checking for signal.h... yes
checking stropts.h usability... no
checking stropts.h presence... no
checking for stropts.h... no
checking termios.h usability... yes
checking termios.h presence... yes
checking for termios.h... yes
checking for unistd.h... (cached) yes
checking utime.h usability... yes
checking utime.h presence... yes
checking for utime.h... yes
checking poll.h usability... yes
checking poll.h presence... yes
checking for poll.h... yes
checking sys/devpoll.h usability... no
checking sys/devpoll.h presence... no
checking for sys/devpoll.h... no
checking sys/epoll.h usability... yes
checking sys/epoll.h presence... yes
checking for sys/epoll.h... yes
checking sys/poll.h usability... yes
checking sys/poll.h presence... yes
checking for sys/poll.h... yes
checking sys/audioio.h usability... no
checking sys/audioio.h presence... no
checking for sys/audioio.h... no
checking sys/xattr.h usability... yes
checking sys/xattr.h presence... yes
checking for sys/xattr.h... yes
checking sys/bsdtty.h usability... no
checking sys/bsdtty.h presence... no
checking for sys/bsdtty.h... no
checking sys/event.h usability... no
checking sys/event.h presence... no
checking for sys/event.h... no
checking sys/file.h usability... yes
checking sys/file.h presence... yes
checking for sys/file.h... yes
checking sys/ioctl.h usability... yes
checking sys/ioctl.h presence... yes
checking for sys/ioctl.h... yes
checking sys/kern_control.h usability... no
checking sys/kern_control.h presence... no
checking for sys/kern_control.h... no
checking sys/loadavg.h usability... no
checking sys/loadavg.h presence... no
checking for sys/loadavg.h... no
checking sys/lock.h usability... no
checking sys/lock.h presence... no
checking for sys/lock.h... no
checking sys/mkdev.h usability... no
checking sys/mkdev.h presence... no
checking for sys/mkdev.h... no
checking sys/modem.h usability... no
checking sys/modem.h presence... no
checking for sys/modem.h... no
checking sys/param.h usability... yes
checking sys/param.h presence... yes
checking for sys/param.h... yes
checking sys/random.h usability... no
checking sys/random.h presence... no
checking for sys/random.h... no
checking sys/select.h usability... yes
checking sys/select.h presence... yes
checking for sys/select.h... yes
checking sys/sendfile.h usability... yes
checking sys/sendfile.h presence... yes
checking for sys/sendfile.h... yes
checking sys/socket.h usability... yes
checking sys/socket.h presence... yes
checking for sys/socket.h... yes
checking sys/statvfs.h usability... yes
checking sys/statvfs.h presence... yes
checking for sys/statvfs.h... yes
checking for sys/stat.h... (cached) yes
checking sys/syscall.h usability... yes
checking sys/syscall.h presence... yes
checking for sys/syscall.h... yes
checking sys/sys_domain.h usability... no
checking sys/sys_domain.h presence... no
checking for sys/sys_domain.h... no
checking sys/termio.h usability... no
checking sys/termio.h presence... no
checking for sys/termio.h... no
checking sys/time.h usability... yes
checking sys/time.h presence... yes
checking for sys/time.h... yes
checking sys/times.h usability... yes
checking sys/times.h presence... yes
checking for sys/times.h... yes
checking for sys/types.h... (cached) yes
checking sys/uio.h usability... yes
checking sys/uio.h presence... yes
checking for sys/uio.h... yes
checking sys/un.h usability... yes
checking sys/un.h presence... yes
checking for sys/un.h... yes
checking sys/utsname.h usability... yes
checking sys/utsname.h presence... yes
checking for sys/utsname.h... yes
checking sys/wait.h usability... yes
checking sys/wait.h presence... yes
checking for sys/wait.h... yes
checking pty.h usability... yes
checking pty.h presence... yes
checking for pty.h... yes
checking libutil.h usability... no
checking libutil.h presence... no
checking for libutil.h... no
checking sys/resource.h usability... yes
checking sys/resource.h presence... yes
checking for sys/resource.h... yes
checking netpacket/packet.h usability... yes
checking netpacket/packet.h presence... yes
checking for netpacket/packet.h... yes
checking sysexits.h usability... yes
checking sysexits.h presence... yes
checking for sysexits.h... yes
checking bluetooth.h usability... no
checking bluetooth.h presence... no
checking for bluetooth.h... no
checking linux/tipc.h usability... yes
checking linux/tipc.h presence... yes
checking for linux/tipc.h... yes
checking linux/random.h usability... yes
checking linux/random.h presence... yes
checking for linux/random.h... yes
checking spawn.h usability... yes
checking spawn.h presence... yes
checking for spawn.h... yes
checking util.h usability... no
checking util.h presence... no
checking for util.h... no
checking alloca.h usability... yes
checking alloca.h presence... yes
checking for alloca.h... yes
checking endian.h usability... yes
checking endian.h presence... yes
checking for endian.h... yes
checking sys/endian.h usability... no
checking sys/endian.h presence... no
checking for sys/endian.h... no
checking sys/sysmacros.h usability... yes
checking sys/sysmacros.h presence... yes
checking for sys/sysmacros.h... yes
checking for dirent.h that defines DIR... yes
checking for library containing opendir... no
checking whether sys/types.h defines makedev... no
checking for sys/mkdev.h... (cached) no
checking for sys/sysmacros.h... (cached) yes
checking bluetooth/bluetooth.h usability... no
checking bluetooth/bluetooth.h presence... no
checking for bluetooth/bluetooth.h... no
checking for net/if.h... yes
checking for linux/netlink.h... yes
checking for linux/vm_sockets.h... yes
checking for linux/can.h... yes
checking for linux/can/raw.h... yes
checking for linux/can/bcm.h... yes
checking for clock_t in time.h... yes
checking for makedev... no
checking for le64toh... no
checking for mode_t... yes
checking for off_t... yes
checking for pid_t... yes
checking for size_t... yes
checking for uid_t in sys/types.h... yes
checking for ssize_t... yes
checking for __uint128_t... yes
checking size of int... 0
checking size of long... 0
checking size of long long... 0
checking size of void *... 0
checking size of short... 0
checking size of float... 0
checking size of double... 0
checking size of fpos_t... 0
checking size of size_t... configure: error: in `/hpc/packages/minerva-centos7/python/3.7.1/src/Python-3.7.1':
configure: error: cannot compute sizeof (size_t)
See `config.log' for more details
gail01@node7-1: /hpc/packages/minerva-centos7/python/3.7.1/src/Python-3.7.1 $ cd /hpc/packages/minerva-common/samtools/1.1
gail01@node7-1: /hpc/packages/minerva-common/samtools/1.1 $ ls
bin  include  lib  lib64  misc  share  src
gail01@node7-1: /hpc/packages/minerva-common/samtools/1.1 $ cd src
gail01@node7-1: /hpc/packages/minerva-common/samtools/1.1/src $ ls
samtools-1.1  samtools-1.1.tar.bz2
gail01@node7-1: /hpc/packages/minerva-common/samtools/1.1/src $ cd samtools-1.1
gail01@node7-1: /hpc/packages/minerva-common/samtools/1.1/src/samtools-1.1 $ ls
AUTHORS         bam.c            bam2depth.o   bam_flags.o    bam_mate.o      bam_reheader.o  bam_stat.c          bamshuf.c     cut_target.o  kaln.h       padding.o     sam_view.c  stats.o
ChangeLog.old   bam.h            bam_aux.c     bam_import.c   bam_md.c        bam_rmdup.c     bam_stat.o          bamshuf.o     errmod.c      kaln.o       phase.c       sam_view.o  stats_isize.c
INSTALL         bam.o            bam_aux.o     bam_import.o   bam_md.o        bam_rmdup.o     bam_tview.c         bamtk.c       errmod.h      kprobaln.c   phase.o       sample.c    stats_isize.h
LICENSE         bam2bcf.c        bam_cat.c     bam_index.c    bam_plbuf.c     bam_rmdupse.c   bam_tview.h         bamtk.o       errmod.o      kprobaln.h   sam.c         sample.h    stats_isize.o
Makefile        bam2bcf.h        bam_cat.o     bam_index.o    bam_plbuf.h     bam_rmdupse.o   bam_tview.o         bedcov.c      examples      kprobaln.o   sam.h         sample.o    test
Makefile.mingw  bam2bcf.o        bam_color.c   bam_lpileup.c  bam_plbuf.o     bam_sort.c      bam_tview_curses.c  bedcov.o      faidx.c       libbam.a     sam.o         samtools    version.h
NEWS            bam2bcf_indel.c  bam_color.o   bam_lpileup.h  bam_plcmd.c     bam_sort.o      bam_tview_curses.o  bedidx.c      faidx.o       libbam.so.1  sam_header.c  samtools.1  win32
README          bam2bcf_indel.o  bam_endian.h  bam_lpileup.o  bam_plcmd.o     bam_split.c     bam_tview_html.c    bedidx.o      htslib-1.1    misc         sam_header.h  samtools.h
What            bam2depth.c      bam_flags.c   bam_mate.c     bam_reheader.c  bam_split.o     bam_tview_html.o    cut_target.c  kaln.c        padding.c    sam_header.o  stats.c
gail01@node7-1: /hpc/packages/minerva-common/samtools/1.1/src/samtools-1.1 $ vi What 
gail01@node7-1: /hpc/packages/minerva-common/samtools/1.1/src/samtools-1.1 $ cd htslib-1.1/
gail01@node7-1: /hpc/packages/minerva-common/samtools/1.1/src/samtools-1.1/htslib-1.1 $ ls
INSTALL   bgzf.o     config.h  faidx.pico        hfile_net.c     hts.pico        kfunc.c     knetfile.pico  libhts.so    sam.pico                tabix.1  tbx.pico  vcf.pico        vcfutils.o
LICENSE   bgzf.pico  cram      hfile.c           hfile_net.o     htslib          kfunc.o     kstring.c      libhts.so.1  synced_bcf_reader.c     tabix.c  test      vcf_sweep.c     vcfutils.pico
Makefile  bgzip      faidx.5   hfile.o           hfile_net.pico  htslib.mk       kfunc.pico  kstring.o      sam.5        synced_bcf_reader.o     tabix.o  vcf.5     vcf_sweep.o     version.h
README    bgzip.c    faidx.c   hfile.pico        hts.c           htslib.pc.in    knetfile.c  kstring.pico   sam.c        synced_bcf_reader.pico  tbx.c    vcf.c     vcf_sweep.pico
bgzf.c    bgzip.o    faidx.o   hfile_internal.h  hts.o           htslib_vars.mk  knetfile.o  libhts.a       sam.o        tabix                   tbx.o    vcf.o     vcfutils.c
gail01@node7-1: /hpc/packages/minerva-common/samtools/1.1/src/samtools-1.1/htslib-1.1 $ cd hts
-bash: cd: hts: No such file or directory
gail01@node7-1: /hpc/packages/minerva-common/samtools/1.1/src/samtools-1.1/htslib-1.1 $ cd htslib
gail01@node7-1: /hpc/packages/minerva-common/samtools/1.1/src/samtools-1.1/htslib-1.1/htslib $ ls
bgzf.h  faidx.h  hfile.h  hts.h  hts_defs.h  kfunc.h  khash.h  khash_str2int.h  klist.h  knetfile.h  kseq.h  ksort.h  kstring.h  sam.h  synced_bcf_reader.h  tbx.h  vcf.h  vcf_sweep.h  vcfutils.h
gail01@node7-1: /hpc/packages/minerva-common/samtools/1.1/src/samtools-1.1/htslib-1.1/htslib $ cd ..
gail01@node7-1: /hpc/packages/minerva-common/samtools/1.1/src/samtools-1.1/htslib-1.1 $ ls libhts.a
libhts.a
gail01@node7-1: /hpc/packages/minerva-common/samtools/1.1/src/samtools-1.1/htslib-1.1 $ cd /sc/orga/packages/lili_tem/
gail01@node7-1: /sc/orga/packages/lili_tem $ ls
R         backup     ebtest  lua           pei  prokka    rosetta                                 rosetta_bin_linux_3.9_bundle.tgz  t_modulefiles  used
ana-test  blcr_make  lmod    my-rdkit-env  pkg  rgi_card  rosetta_bin_linux_2018.09.60072_bundle  seuratprj                         temp           usertest
gail01@node7-1: /sc/orga/packages/lili_tem $       
gail01@node7-1: /sc/orga/packages/lili_tem $ cd pkg/
gail01@node7-1: /sc/orga/packages/lili_tem/pkg $ ls
python  t_fsl  t_libffi  t_macs2  t_rfmix  t_sing  t_spython  t_susie
gail01@node7-1: /sc/orga/packages/lili_tem/pkg $ cd python/
gail01@node7-1: /sc/orga/packages/lili_tem/pkg/python $ ls
src
gail01@node7-1: /sc/orga/packages/lili_tem/pkg/python $ cd src
gail01@node7-1: /sc/orga/packages/lili_tem/pkg/python/src $ ls
Python-3.7.2  Python-3.7.2.tar.xz
gail01@node7-1: /sc/orga/packages/lili_tem/pkg/python/src $ cd Python-3.7.2
gail01@node7-1: /sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2 $ ls
CODE_OF_CONDUCT.rst  Grammar  LICENSE  Mac       Makefile.pre     Misc     Objects  PCbuild  Programs  README.rst  aclocal.m4    config.log     config.sub  configure.ac  m4          pyconfig.h.in
Doc                  Include  Lib      Makefile  Makefile.pre.in  Modules  PC       Parser   Python    Tools       config.guess  config.status  configure   install-sh    pyconfig.h  setup.py
gail01@node7-1: /sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2 $ exit
logout
Connection to node7-1 closed.
gail01@login1: /sc/orga/packages/lili_tem/t_modulefiles/fsl $ cd /sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2
gail01@login1: /sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2 $ ls
aclocal.m4           config.guess  config.status  configure     Doc      Include     Lib      m4   Makefile      Makefile.pre.in  Modules  Parser  PCbuild   pyconfig.h     Python      setup.py
CODE_OF_CONDUCT.rst  config.log    config.sub     configure.ac  Grammar  install-sh  LICENSE  Mac  Makefile.pre  Misc             Objects  PC      Programs  pyconfig.h.in  README.rst  Tools
gail01@login1: /sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2 $ 
gail01@login1: /sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2 $ history | grep config
  254  vi configureHomer.pl 
  482  ./configure --help
  483  ./configure --help | grep parallel
  485  ./configure --with-blas="-lmkl_gf_lp64 -lmkl_gnu_thread -lmkl_core -liomp5 -lpthread" --with-lapack --enable-R-shlib --prefix="/sc/orga/packages/lili_tem/R/3.5.2" FFLAGS="-O3 -fopenmp" FCFLAGS="-O3 -fopenmp" CFLAGS="-O3 -fopenmp" CXXFLAGS="-O3 -fopenmp" F77=gfortran FFLAGS="-O3 -fopenmp"
  490  ./configure --with-blas="-lmkl_gf_lp64 -lmkl_gnu_thread -lmkl_core -liomp5 -lpthread" --with-lapack --enable-R-shlib --prefix="/sc/orga/packages/lili_tem/R/3.5.2" FFLAGS="-O2 -fopenmp" FCFLAGS="-O2 -fopenmp" CFLAGS="-O2 -fopenmp" CXXFLAGS="-O2 -fopenmp" F77=gfortran FFLAGS="-O2 -fopenmp"
  755  ./configure --with-blas="-lmkl_gf_lp64 -lmkl_gnu_thread -lmkl_core -liomp5 -lpthread" --with-lapack --enable-R-shlib --with-libtiff --prefix="/sc/orga/packages/lili_tem/R/3.5.2” FFLAGS="-O3 -fopenmp" FCFLAGS="-O3 -fopenmp" CFLAGS="-O3 -fopenmp" CXXFLAGS="-O3 -fopenmp" F77=gfortran FFLAGS="-O3 -fopenmp"
  756  ./configure --with-blas="-lmkl_gf_lp64 -lmkl_gnu_thread -lmkl_core -liomp5 -lpthread" --with-lapack --enable-R-shlib --with-libtiff --prefix="/sc/orga/packages/lili_tem/R/3.5.2" FFLAGS="-O3 -fopenmp" FCFLAGS="-O3 -fopenmp" CFLAGS="-O3 -fopenmp" CXXFLAGS="-O3 -fopenmp" F77=gfortran FFLAGS="-O3 -fopenmp"
  760  ./configure --with-blas="-lmkl_gf_lp64 -lmkl_gnu_thread -lmkl_core -liomp5 -lpthread" --with-lapack --enable-R-shlib --with-libtiff --prefix="/sc/orga/packages/lili_tem/R/3.5.2" FFLAGS="-O3 -fopenmp" FCFLAGS="-O3 -fopenmp" CFLAGS="-O3 -fopenmp" CXXFLAGS="-O3 -fopenmp" F77=gfortran FFLAGS="-O3 -fopenmp"
  764  ./configure --with-blas="-lmkl_gf_lp64 -lmkl_gnu_thread -lmkl_core -liomp5 -lpthread" --with-lapack --enable-R-shlib --with-libtiff --prefix="/sc/orga/packages/lili_tem/R/3.5.2" FFLAGS="-O3 -fopenmp" FCFLAGS="-O3 -fopenmp" CFLAGS="-O3 -fopenmp" CXXFLAGS="-O3 -fopenmp" F77=gfortran FFLAGS="-O3 -fopenmp" --with-readline=no
  765  ./configure --with-blas="-lmkl_gf_lp64 -lmkl_gnu_thread -lmkl_core -liomp5 -lpthread" --with-lapack --enable-R-shlib --with-libtiff --prefix="/sc/orga/packages/lili_tem/R/3.5.2" FFLAGS="-O3 -fopenmp" FCFLAGS="-O3 -fopenmp" CFLAGS="-O3 -fopenmp" CXXFLAGS="-O3 -fopenmp" F77=gfortran FFLAGS="-O3 -fopenmp" --with-readline=no --with-x=no
  817  vi config.log 
  818  ./configure --with-blas=-lmkl_gf_lp64 -lmkl_gnu_thread -lmkl_core -liomp5 -lpthread --with-lapack --prefix=/sc/orga/packages/lili_tem/R/3.5.2 FFLAGS=-O2 -fopenmp FCFLAGS=-O2 -fopenmp CFLAGS=-O2 -fopenmp CXXFLAGS=-O2 -fopenmp F77=gfortran FFLAGS=-O2 -fopenmp
  819  vi config.log 
  821  ./configure --with-blas=-lmkl_gf_lp64 -lmkl_gnu_thread -lmkl_core -liomp5 -lpthread --with-lapack --prefix=/sc/orga/packages/lili_tem/R/3.5.2 FFLAGS=-O2 -fopenmp FCFLAGS=-O2 -fopenmp CFLAGS=-O2 -fopenmp CXXFLAGS=-O2 -fopenmp F77=gfortran FFLAGS=-O2 -fopenmp
  822  ./configure --help | grep mkl
  823  ./configure --help | lmkl
  824  ./configure --help
  825  vi config.log 
  826  ./configure --with-blas=-lmkl_gf_lp64 -lmkl_gnu_thread -lmkl_core -liomp5 -lpthread --with-lapack --enable-R-shlib --prefix=/sc/orga/packages/lili_tem/R/3.5.2 FFLAGS=-O2 -fopenmp FCFLAGS=-O2 -fopenmp CFLAGS=-O2 -fopenmp CXXFLAGS=-O2 -fopenmp F77=gfortran FFLAGS=-O2 -fopenmp
  829  ./configure --with-blas="-lmkl_gf_lp64 -lmkl_gnu_thread -lmkl_core -liomp5 -lpthread" --with-lapack --enable-R-shlib --prefix="/sc/orga/packages/lili_tem/R/3.5.2" FFLAGS="-O3 -fopenmp" FCFLAGS="-O3 -fopenmp" CFLAGS="-O3 -fopenmp" CXXFLAGS="-O3 -fopenmp" F77=gfortran FFLAGS="-O3 -fopenmp"
  830  ./configure --with-blas="-lmkl_gf_lp64 -lmkl_gnu_thread -lmkl_core -liomp5 -lpthread" --with-lapack --prefix="/sc/orga/packages/lili_tem/R/3.5.2" FFLAGS="-O3 -fopenmp" FCFLAGS="-O3 -fopenmp" CFLAGS="-O3 -fopenmp" CXXFLAGS="-O3 -fopenmp" F77=gfortran FFLAGS="-O3 -fopenmp"
  839  vi config.log 
  841  vi config.log 
  843  vi config.log 
  846  ./configure --with-blas=-lmkl_gf_lp64 -lmkl_gnu_thread -lmkl_core -liomp5 -lpthread --with-lapack --enable-R-shlib --with-libtiff --prefix=/sc/orga/packages/lili_tem/R/3.5.1 FFLAGS=-O3 -fopenmp FCFLAGS=-O3 -fopenmp CFLAGS=-O3 -fopenmp CXXFLAGS=-O3 -fopenmp F77=gfortran FFLAGS=-O3 -fopenmp
  847  ./configure --with-blas="-lmkl_gf_lp64 -lmkl_gnu_thread -lmkl_core -liomp5 -lpthread" --with-lapack --enable-R-shlib --prefix="/sc/orga/packages/lili_tem/R/3.5.2" FFLAGS="-O3 -fopenmp" FCFLAGS="-O3 -fopenmp" CFLAGS="-O3 -fopenmp" CXXFLAGS="-O3 -fopenmp" F77=gfortran FFLAGS="-O3 -fopenmp"
  850  vi config.log 
  860  ./configure --with-blas="-lmkl_gf_lp64 -lmkl_gnu_thread -lmkl_core -liomp5 -lpthread" --with-lapack --enable-R-shlib --with-libtiff --prefix="/sc/orga/packages/lili_tem/R/3.5.1" FFLAGS="-O3 -fopenmp" FCFLAGS="-O3 -fopenmp" CFLAGS="-O3 -fopenmp" CXXFLAGS="-O3 -fopenmp" F77=gfortran FFLAGS="-O3 -fopenmp"
  865  ./configure --with-blas="-lmkl_gf_lp64 -lmkl_gnu_thread -lmkl_core -liomp5 -lpthread" --with-lapack --enable-R-shlib --with-libtiff --prefix="/sc/orga/packages/lili_tem/R/3.5.1" FFLAGS="-O3 -fopenmp" FCFLAGS="-O3 -fopenmp" CFLAGS="-O3 -fopenmp" CXXFLAGS="-O3 -fopenmp" F77=gfortran FFLAGS="-O3 -fopenmp"
  870  ./configure --with-blas="-lmkl_gf_lp64 -lmkl_gnu_thread -lmkl_core -liomp5 -lpthread" --with-lapack --enable-R-shlib --with-libtiff --prefix="/sc/orga/packages/lili_tem/R/3.5.1" FFLAGS="-O3 -fopenmp" FCFLAGS="-O3 -fopenmp" CFLAGS="-O3 -fopenmp" CXXFLAGS="-O3 -fopenmp" F77=gfortran FFLAGS="-O3 -fopenmp"
  882  ./configure --with-blas="-lmkl_gf_lp64 -lmkl_gnu_thread -lmkl_core -liomp5 -lpthread" --with-lapack --enable-R-shlib --with-libtiff --prefix="/sc/orga/packages/lili_tem/R/3.5.1" FFLAGS="-O3 -fopenmp" FCFLAGS="-O3 -fopenmp" CFLAGS="-O3 -fopenmp" CXXFLAGS="-O3 -fopenmp" F77=gfortran FFLAGS="-O3 -fopenmp"
  893  ./configure --with-blas="-lmkl_gf_lp64 -lmkl_gnu_thread -lmkl_core -liomp5 -lpthread" --with-lapack --enable-R-shlib --with-libtiff --prefix="/sc/orga/packages/lili_tem/R/3.5.1" FFLAGS="-O3 -fopenmp" FCFLAGS="-O3 -fopenmp" CFLAGS="-O3 -fopenmp" CXXFLAGS="-O3 -fopenmp" F77=gfortran FFLAGS="-O3 -fopenmp"
  909  ./configure --with-blas="-lmkl_gf_lp64 -lmkl_gnu_thread -lmkl_core -liomp5 -lpthread" --with-lapack --enable-R-shlib --prefix="/sc/orga/packages/lili_tem/R/3.3.0/new“ FFLAGS="-O3 -fopenmp" FCFLAGS="-O3 -fopenmp" CFLAGS="-O3 -fopenmp" CXXFLAGS="-O3 -fopenmp" F77=gfortran FFLAGS="-O3 -fopenmp"
  910  ./configure --with-blas="-lmkl_gf_lp64 -lmkl_gnu_thread -lmkl_core -liomp5 -lpthread" --with-lapack --enable-R-shlib --prefix="/sc/orga/packages/lili_tem/R/3.3.0/new" FFLAGS="-O3 -fopenmp" FCFLAGS="-O3 -fopenmp" CFLAGS="-O3 -fopenmp" CXXFLAGS="-O3 -fopenmp" F77=gfortran FFLAGS="-O3 -fopenmp"
  928  ./configure --with-blas="-lmkl_gf_lp64 -lmkl_gnu_thread -lmkl_core -liomp5 -lpthread" --with-lapack --with-libtiff --prefix="/sc/orga/packages/lili_tem/R/3.5.1” FFLAGS="-O3 -fopenmp" FCFLAGS="-O3 -fopenmp" CFLAGS="-O3 -fopenmp" CXXFLAGS="-O3 -fopenmp" F77=gfortran FFLAGS="-O3 -fopenmp"
  929  ./configure --with-blas="-lmkl_gf_lp64 -lmkl_gnu_thread -lmkl_core -liomp5 -lpthread" --with-lapack --with-libtiff --prefix="/sc/orga/packages/lili_tem/R/3.5.1" FFLAGS="-O3 -fopenmp" FCFLAGS="-O3 -fopenmp" CFLAGS="-O3 -fopenmp" CXXFLAGS="-O3 -fopenmp" F77=gfortran FFLAGS="-O3 -fopenmp"
  932  ./configure --with-blas="-lmkl_gf_lp64 -lmkl_gnu_thread -lmkl_core -liomp5 -lpthread" --with-lapack --with-libtiff --prefix="/sc/orga/packages/lili_tem/R/3.5.1" FFLAGS="-O3 -fopenmp" FCFLAGS="-O3 -fopenmp" CFLAGS="-O3 -fopenmp" CXXFLAGS="-O3 -fopenmp" F77=gfortran FFLAGS="-O3 -fopenmp"
  938  ./configure --with-blas="-lmkl_gf_lp64 -lmkl_gnu_thread -lmkl_core -liomp5 -lpthread" --with-lapack --with-libtiff --prefix="/sc/orga/packages/lili_tem/R/3.5.1" FFLAGS="-O3 -fopenmp" FCFLAGS="-O3 -fopenmp" CFLAGS="-O3 -fopenmp" CXXFLAGS="-O3 -fopenmp" F77=gfortran FFLAGS="-O3 -fopenmp"
  980  ./configure --with-blas="-lmkl_gf_lp64 -lmkl_gnu_thread -lmkl_core -liomp5 -lpthread" --with-lapack --enable-R-shlib --prefix="/hpc/packages/minerva-common/R/3.5.0" FFLAGS="-O2 -fopenmp" FCFLAGS="-O2 -fopenmp" CFLAGS="-O2 -fopenmp" CXXFLAGS="-O2 -fopenmp" F77=gfortran FFLAGS="-O2 -fopenmp"
  981  ./configure --with-blas="-lmkl_gf_lp64 -lmkl_gnu_thread -lmkl_core -liomp5 -lpthread" --with-lapack --enable-R-shlib --prefix="/h/sc/orga/packages/lili_tem/R/3.5.1/R-3.5.1" FFLAGS="-O2 -fopenmp" FCFLAGS="-O2 -fopenmp" CFLAGS="-O2 -fopenmp" CXXFLAGS="-O2 -fopenmp" F77=gfortran FFLAGS="-O2 -fopenmp"
  985  ./configure --with-blas="-lmkl_gf_lp64 -lmkl_gnu_thread -lmkl_core -liomp5 -lpthread" --with-lapack --enable-R-shlib --prefix="/h/sc/orga/packages/lili_tem/R/3.5.1/R-3.5.1" FFLAGS="-O2 -fopenmp" FCFLAGS="-O2 -fopenmp" CFLAGS="-O2 -fopenmp" CXXFLAGS="-O2 -fopenmp" F77=gfortran FFLAGS="-O2 -fopenmp"
  987  ./configure --with-blas="-lmkl_gf_lp64 -lmkl_gnu_thread -lmkl_core -liomp5 -lpthread" --with-lapack --enable-R-shlib --prefix="/h/sc/orga/packages/lili_tem/R/3.5.1/R-3.5.1" FFLAGS="-O2 -fopenmp" FCFLAGS="-O2 -fopenmp" CFLAGS="-O2 -fopenmp" CXXFLAGS="-O2 -fopenmp" F77=gfortran FFLAGS="-O2 -fopenmp"
  990  ./configure --with-blas="-lmkl_gf_lp64 -lmkl_gnu_thread -lmkl_core -liomp5 -lpthread" --with-lapack --enable-R-shlib --prefix="/h/sc/orga/packages/lili_tem/R/3.5.1/R-3.5.1" FFLAGS="-O2 -fopenmp" FCFLAGS="-O2 -fopenmp" CFLAGS="-O2 -fopenmp" CXXFLAGS="-O2 -fopenmp" F77=gfortran FFLAGS="-O2 -fopenmp"
  993  ./configure --with-blas="-lmkl_gf_lp64 -lmkl_gnu_thread -lmkl_core -liomp5 -lpthread" --with-lapack --enable-R-shlib --prefix="/h/sc/orga/packages/lili_tem/R/3.5.1/R-3.5.1" FFLAGS="-O2 -fopenmp" FCFLAGS="-O2 -fopenmp" CFLAGS="-O2 -fopenmp" CXXFLAGS="-O2 -fopenmp" F77=gfortran FFLAGS="-O2 -fopenmp"
 1021  history | grep config
gail01@login1: /sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2 $ module purge
gail01@login1: /sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2 $ module load gcc
gail01@login1: /sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2 $ ./configure --prefix=/sc/orga/packages/lili_tem/pkg/python --enable-shared --with-ensurepip=install --enable-optimizations
checking build system type... x86_64-pc-linux-gnu
checking host system type... x86_64-pc-linux-gnu
checking for python3.7... no
checking for python3... no
checking for python... python
checking for --enable-universalsdk... no
checking for --with-universal-archs... no
checking MACHDEP... checking for --without-gcc... no
checking for --with-icc... no
checking for gcc... gcc
checking whether the C compiler works... yes
checking for C compiler default output file name... a.out
checking for suffix of executables... 
checking whether we are cross compiling... no
checking for suffix of object files... o
checking whether we are using the GNU C compiler... yes
checking whether gcc accepts -g... yes
checking for gcc option to accept ISO C89... none needed
checking how to run the C preprocessor... gcc -E
checking for grep that handles long lines and -e... /bin/grep
checking for a sed that does not truncate output... /bin/sed
checking for --with-cxx-main=<compiler>... no
checking for g++... no
configure:

  By default, distutils will build C++ extension modules with "g++".
  If this is not intended, then set CXX on the configure command line.
  
checking for the platform triplet based on compiler characteristics... x86_64-linux-gnu
checking for -Wl,--no-as-needed... yes
checking for egrep... /bin/grep -E
checking for ANSI C header files... yes
checking for sys/types.h... yes
checking for sys/stat.h... yes
checking for stdlib.h... yes
checking for string.h... yes
checking for memory.h... yes
checking for strings.h... yes
checking for inttypes.h... yes
checking for stdint.h... yes
checking for unistd.h... yes
checking minix/config.h usability... no
checking minix/config.h presence... no
checking for minix/config.h... no
checking whether it is safe to define __EXTENSIONS__... yes
checking for the Android API level... not Android
checking for --with-suffix... 
checking for case-insensitive build directory... no
checking LIBRARY... libpython$(VERSION)$(ABIFLAGS).a
checking LINKCC... $(PURIFY) $(MAINCC)
checking for GNU ld... yes
checking for --enable-shared... yes
checking for --enable-profiling... no
checking LDLIBRARY... libpython$(LDVERSION).so
checking for ar... ar
checking for readelf... readelf
checking for a BSD-compatible install... /usr/bin/install -c
checking for a thread-safe mkdir -p... /bin/mkdir -p
checking for --with-pydebug... no
checking for --with-assertions... no
checking for --enable-optimizations... yes
checking for --with-lto... no
checking for -llvm-profdata... no
checking for -Wextra... yes
checking whether gcc accepts and needs -fno-strict-aliasing... no
checking if we can turn off gcc unused result warning... yes
checking if we can turn off gcc unused parameter warning... yes
checking if we can turn off gcc missing field initializers warning... yes
checking if we can turn off gcc invalid function cast warning... no
checking if we can turn on gcc mixed sign comparison warning... yes
checking if we can turn on gcc unreachable code warning... no
checking if we can turn on gcc strict-prototypes warning... no
checking if we can make implicit function declaration an error in gcc... yes
checking whether pthreads are available without options... no
checking whether gcc accepts -Kpthread... no
checking whether gcc accepts -Kthread... no
checking whether gcc accepts -pthread... yes
checking whether g++ also accepts flags for thread support... yes
checking for ANSI C header files... (cached) yes
checking asm/types.h usability... yes
checking asm/types.h presence... yes
checking for asm/types.h... yes
checking crypt.h usability... yes
checking crypt.h presence... yes
checking for crypt.h... yes
checking conio.h usability... no
checking conio.h presence... no
checking for conio.h... no
checking direct.h usability... no
checking direct.h presence... no
checking for direct.h... no
checking dlfcn.h usability... yes
checking dlfcn.h presence... yes
checking for dlfcn.h... yes
checking errno.h usability... yes
checking errno.h presence... yes
checking for errno.h... yes
checking fcntl.h usability... yes
checking fcntl.h presence... yes
checking for fcntl.h... yes
checking grp.h usability... yes
checking grp.h presence... yes
checking for grp.h... yes
checking ieeefp.h usability... no
checking ieeefp.h presence... no
checking for ieeefp.h... no
checking io.h usability... no
checking io.h presence... no
checking for io.h... no
checking langinfo.h usability... yes
checking langinfo.h presence... yes
checking for langinfo.h... yes
checking libintl.h usability... yes
checking libintl.h presence... yes
checking for libintl.h... yes
checking process.h usability... no
checking process.h presence... no
checking for process.h... no
checking pthread.h usability... yes
checking pthread.h presence... yes
checking for pthread.h... yes
checking sched.h usability... yes
checking sched.h presence... yes
checking for sched.h... yes
checking shadow.h usability... yes
checking shadow.h presence... yes
checking for shadow.h... yes
checking signal.h usability... yes
checking signal.h presence... yes
checking for signal.h... yes
checking stropts.h usability... no
checking stropts.h presence... no
checking for stropts.h... no
checking termios.h usability... yes
checking termios.h presence... yes
checking for termios.h... yes
checking for unistd.h... (cached) yes
checking utime.h usability... yes
checking utime.h presence... yes
checking for utime.h... yes
checking poll.h usability... yes
checking poll.h presence... yes
checking for poll.h... yes
checking sys/devpoll.h usability... no
checking sys/devpoll.h presence... no
checking for sys/devpoll.h... no
checking sys/epoll.h usability... yes
checking sys/epoll.h presence... yes
checking for sys/epoll.h... yes
checking sys/poll.h usability... yes
checking sys/poll.h presence... yes
checking for sys/poll.h... yes
checking sys/audioio.h usability... no
checking sys/audioio.h presence... no
checking for sys/audioio.h... no
checking sys/xattr.h usability... yes
checking sys/xattr.h presence... yes
checking for sys/xattr.h... yes
checking sys/bsdtty.h usability... no
checking sys/bsdtty.h presence... no
checking for sys/bsdtty.h... no
checking sys/event.h usability... no
checking sys/event.h presence... no
checking for sys/event.h... no
checking sys/file.h usability... yes
checking sys/file.h presence... yes
checking for sys/file.h... yes
checking sys/ioctl.h usability... yes
checking sys/ioctl.h presence... yes
checking for sys/ioctl.h... yes
checking sys/kern_control.h usability... no
checking sys/kern_control.h presence... no
checking for sys/kern_control.h... no
checking sys/loadavg.h usability... no
checking sys/loadavg.h presence... no
checking for sys/loadavg.h... no
checking sys/lock.h usability... no
checking sys/lock.h presence... no
checking for sys/lock.h... no
checking sys/mkdev.h usability... no
checking sys/mkdev.h presence... no
checking for sys/mkdev.h... no
checking sys/modem.h usability... no
checking sys/modem.h presence... no
checking for sys/modem.h... no
checking sys/param.h usability... yes
checking sys/param.h presence... yes
checking for sys/param.h... yes
checking sys/random.h usability... no
checking sys/random.h presence... no
checking for sys/random.h... no
checking sys/select.h usability... yes
checking sys/select.h presence... yes
checking for sys/select.h... yes
checking sys/sendfile.h usability... yes
checking sys/sendfile.h presence... yes
checking for sys/sendfile.h... yes
checking sys/socket.h usability... yes
checking sys/socket.h presence... yes
checking for sys/socket.h... yes
checking sys/statvfs.h usability... yes
checking sys/statvfs.h presence... yes
checking for sys/statvfs.h... yes
checking for sys/stat.h... (cached) yes
checking sys/syscall.h usability... yes
checking sys/syscall.h presence... yes
checking for sys/syscall.h... yes
checking sys/sys_domain.h usability... no
checking sys/sys_domain.h presence... no
checking for sys/sys_domain.h... no
checking sys/termio.h usability... no
checking sys/termio.h presence... no
checking for sys/termio.h... no
checking sys/time.h usability... yes
checking sys/time.h presence... yes
checking for sys/time.h... yes
checking sys/times.h usability... yes
checking sys/times.h presence... yes
checking for sys/times.h... yes
checking for sys/types.h... (cached) yes
checking sys/uio.h usability... yes
checking sys/uio.h presence... yes
checking for sys/uio.h... yes
checking sys/un.h usability... yes
checking sys/un.h presence... yes
checking for sys/un.h... yes
checking sys/utsname.h usability... yes
checking sys/utsname.h presence... yes
checking for sys/utsname.h... yes
checking sys/wait.h usability... yes
checking sys/wait.h presence... yes
checking for sys/wait.h... yes
checking pty.h usability... yes
checking pty.h presence... yes
checking for pty.h... yes
checking libutil.h usability... no
checking libutil.h presence... no
checking for libutil.h... no
checking sys/resource.h usability... yes
checking sys/resource.h presence... yes
checking for sys/resource.h... yes
checking netpacket/packet.h usability... yes
checking netpacket/packet.h presence... yes
checking for netpacket/packet.h... yes
checking sysexits.h usability... yes
checking sysexits.h presence... yes
checking for sysexits.h... yes
checking bluetooth.h usability... no
checking bluetooth.h presence... no
checking for bluetooth.h... no
checking linux/tipc.h usability... yes
checking linux/tipc.h presence... yes
checking for linux/tipc.h... yes
checking linux/random.h usability... yes
checking linux/random.h presence... yes
checking for linux/random.h... yes
checking spawn.h usability... yes
checking spawn.h presence... yes
checking for spawn.h... yes
checking util.h usability... yes
checking util.h presence... yes
checking for util.h... yes
checking alloca.h usability... yes
checking alloca.h presence... yes
checking for alloca.h... yes
checking endian.h usability... yes
checking endian.h presence... yes
checking for endian.h... yes
checking sys/endian.h usability... no
checking sys/endian.h presence... no
checking for sys/endian.h... no
checking sys/sysmacros.h usability... yes
checking sys/sysmacros.h presence... yes
checking for sys/sysmacros.h... yes
checking for dirent.h that defines DIR... yes
checking for library containing opendir... none required
checking whether sys/types.h defines makedev... yes
checking bluetooth/bluetooth.h usability... no
checking bluetooth/bluetooth.h presence... no
checking for bluetooth/bluetooth.h... no
checking for net/if.h... yes
checking for linux/netlink.h... yes
checking for linux/vm_sockets.h... no
checking for linux/can.h... yes
checking for linux/can/raw.h... yes
checking for linux/can/bcm.h... no
checking for clock_t in time.h... yes
checking for makedev... yes
checking for le64toh... yes
checking for mode_t... yes
checking for off_t... yes
checking for pid_t... yes
checking for size_t... yes
checking for uid_t in sys/types.h... yes
checking for ssize_t... yes
checking for __uint128_t... yes
checking size of int... 4
checking size of long... 8
checking size of long long... 8
checking size of void *... 8
checking size of short... 2
checking size of float... 4
checking size of double... 8
checking size of fpos_t... 16
checking size of size_t... 8
checking size of pid_t... 4
checking size of uintptr_t... 8
checking for long double support... yes
checking size of long double... 16
checking size of _Bool... 1
checking size of off_t... 8
checking whether to enable large file support... no
checking size of time_t... 8
checking for pthread_t... yes
checking size of pthread_t... 8
checking size of pthread_key_t... 4
checking whether pthread_key_t is compatible with int... yes
checking for --enable-framework... no
checking for dyld... no
checking the extension of shared libraries... .so
checking LDSHARED... $(CC) -shared
checking CCSHARED... -fPIC
checking LINKFORSHARED... -Xlinker -export-dynamic
checking CFLAGSFORSHARED... $(CCSHARED)
checking SHLIBS... $(LIBS)
checking for sendfile in -lsendfile... no
checking for dlopen in -ldl... yes
checking for shl_load in -ldld... no
checking uuid/uuid.h usability... yes
checking uuid/uuid.h presence... yes
checking for uuid/uuid.h... yes
checking uuid.h usability... no
checking uuid.h presence... no
checking for uuid.h... no
checking for uuid_generate_time_safe... yes
checking for uuid_create... no
checking for uuid_enc_be... no
checking for library containing sem_init... -lpthread
checking for textdomain in -lintl... no
checking aligned memory access is required... no
checking for --with-hash-algorithm... default
checking for --with-address-sanitizer... no
checking for --with-memory-sanitizer... no
checking for --with-undefined-behavior-sanitizer... no
checking for t_open in -lnsl... no
checking for socket in -lsocket... no
checking for --with-libs... no
checking for pkg-config... /usr/bin/pkg-config
checking pkg-config is at least version 0.9.0... yes
checking for --with-system-expat... no
checking for --with-system-ffi... yes
checking for --with-system-libmpdec... no
checking for --enable-loadable-sqlite-extensions... no
checking for --with-tcltk-includes... default
checking for --with-tcltk-libs... default
checking for --with-dbmliborder... 
checking if PTHREAD_SCOPE_SYSTEM is supported... yes
checking for pthread_sigmask... yes
checking for pthread_getcpuclockid... yes
checking if --enable-ipv6 is specified... yes
checking if RFC2553 API is available... yes
checking ipv6 stack type... linux-glibc
checking for CAN_RAW_FD_FRAMES... no
checking for --with-doc-strings... yes
checking for --with-pymalloc... yes
checking for --with-c-locale-coercion... yes
checking for --with-valgrind... no
checking for --with-dtrace... no
checking for dlopen... yes
checking DYNLOADFILE... dynload_shlib.o
checking MACHDEP_OBJS... none
checking for alarm... yes
checking for accept4... yes
checking for setitimer... yes
checking for getitimer... yes
checking for bind_textdomain_codeset... yes
checking for chown... yes
checking for clock... yes
checking for confstr... yes
checking for ctermid... yes
checking for dup3... yes
checking for execv... yes
checking for faccessat... yes
checking for fchmod... yes
checking for fchmodat... yes
checking for fchown... yes
checking for fchownat... yes
checking for fexecve... yes
checking for fdopendir... yes
checking for fork... yes
checking for fpathconf... yes
checking for fstatat... yes
checking for ftime... yes
checking for ftruncate... yes
checking for futimesat... yes
checking for futimens... yes
checking for futimes... yes
checking for gai_strerror... yes
checking for getentropy... no
checking for getgrouplist... yes
checking for getgroups... yes
checking for getlogin... yes
checking for getloadavg... yes
checking for getpeername... yes
checking for getpgid... yes
checking for getpid... yes
checking for getpriority... yes
checking for getresuid... yes
checking for getresgid... yes
checking for getpwent... yes
checking for getspnam... yes
checking for getspent... yes
checking for getsid... yes
checking for getwd... yes
checking for if_nameindex... yes
checking for initgroups... yes
checking for kill... yes
checking for killpg... yes
checking for lchown... yes
checking for lockf... yes
checking for linkat... yes
checking for lstat... yes
checking for lutimes... yes
checking for mmap... yes
checking for memrchr... yes
checking for mbrtowc... yes
checking for mkdirat... yes
checking for mkfifo... yes
checking for mkfifoat... yes
checking for mknod... yes
checking for mknodat... yes
checking for mktime... yes
checking for mremap... yes
checking for nice... yes
checking for openat... yes
checking for pathconf... yes
checking for pause... yes
checking for pipe2... yes
checking for plock... no
checking for poll... yes
checking for posix_fallocate... yes
checking for posix_fadvise... yes
checking for posix_spawn... yes
checking for pread... yes
checking for preadv... yes
checking for preadv2... no
checking for pthread_init... no
checking for pthread_kill... yes
checking for putenv... yes
checking for pwrite... yes
checking for pwritev... yes
checking for pwritev2... no
checking for readlink... yes
checking for readlinkat... yes
checking for readv... yes
checking for realpath... yes
checking for renameat... yes
checking for sem_open... yes
checking for sem_timedwait... yes
checking for sem_getvalue... yes
checking for sem_unlink... yes
checking for sendfile... yes
checking for setegid... yes
checking for seteuid... yes
checking for setgid... yes
checking for sethostname... yes
checking for setlocale... yes
checking for setregid... yes
checking for setreuid... yes
checking for setresuid... yes
checking for setresgid... yes
checking for setsid... yes
checking for setpgid... yes
checking for setpgrp... yes
checking for setpriority... yes
checking for setuid... yes
checking for setvbuf... yes
checking for sched_get_priority_max... yes
checking for sched_setaffinity... yes
checking for sched_setscheduler... yes
checking for sched_setparam... yes
checking for sched_rr_get_interval... yes
checking for sigaction... yes
checking for sigaltstack... yes
checking for siginterrupt... yes
checking for sigpending... yes
checking for sigrelse... yes
checking for sigtimedwait... yes
checking for sigwait... yes
checking for sigwaitinfo... yes
checking for snprintf... yes
checking for strftime... yes
checking for strlcpy... no
checking for symlinkat... yes
checking for sync... yes
checking for sysconf... yes
checking for tcgetpgrp... yes
checking for tcsetpgrp... yes
checking for tempnam... yes
checking for timegm... yes
checking for times... yes
checking for tmpfile... yes
checking for tmpnam... yes
checking for tmpnam_r... yes
checking for truncate... yes
checking for uname... yes
checking for unlinkat... yes
checking for unsetenv... yes
checking for utimensat... yes
checking for utimes... yes
checking for waitid... yes
checking for waitpid... yes
checking for wait3... yes
checking for wait4... yes
checking for wcscoll... yes
checking for wcsftime... yes
checking for wcsxfrm... yes
checking for wmemcmp... yes
checking for writev... yes
checking for _getpty... no
checking whether dirfd is declared... yes
checking for chroot... yes
checking for link... yes
checking for symlink... yes
checking for fchdir... yes
checking for fsync... yes
checking for fdatasync... yes
checking for epoll... yes
checking for epoll_create1... yes
checking for kqueue... no
checking for prlimit... no
checking for ctermid_r... no
checking for flock declaration... yes
checking for flock... yes
checking for getpagesize... yes
checking for broken unsetenv... no
checking for true... true
checking for inet_aton in -lc... yes
checking for chflags... no
checking for lchflags... no
checking for inflateCopy in -lz... yes
checking for hstrerror... yes
checking for inet_aton... yes
checking for inet_pton... yes
checking for setgroups... yes
checking for openpty... no
checking for openpty in -lutil... yes
checking for forkpty... yes
checking for fseek64... no
checking for fseeko... yes
checking for fstatvfs... yes
checking for ftell64... no
checking for ftello... yes
checking for statvfs... yes
checking for dup2... yes
checking for strdup... yes
checking for getpgrp... yes
checking for setpgrp... (cached) yes
checking for gettimeofday... yes
checking for clock_gettime... no
checking for clock_gettime in -lrt... yes
checking for clock_getres... yes
checking for clock_settime... yes
checking for major... yes
checking for getaddrinfo... yes
checking getaddrinfo bug... no
checking for getnameinfo... yes
checking whether time.h and sys/time.h may both be included... yes
checking whether struct tm is in sys/time.h or time.h... time.h
checking for struct tm.tm_zone... yes
checking for struct stat.st_rdev... yes
checking for struct stat.st_blksize... yes
checking for struct stat.st_flags... no
checking for struct stat.st_gen... no
checking for struct stat.st_birthtime... no
checking for struct stat.st_blocks... yes
checking for struct passwd.pw_gecos... yes
checking for struct passwd.pw_passwd... yes
checking for siginfo_t.si_band... yes
checking for time.h that defines altzone... no
checking whether sys/select.h and sys/time.h may both be included... yes
checking for addrinfo... yes
checking for sockaddr_storage... yes
checking for sockaddr_alg... no
checking whether char is unsigned... no
checking for an ANSI C-conforming const... yes
checking for working signed char... yes
checking for prototypes... yes
checking for variable length prototypes and stdarg.h... yes
checking for socketpair... yes
checking if sockaddr has sa_len member... no
checking for gethostbyname_r... yes
checking gethostbyname_r with 6 args... yes
checking for __fpu_control... yes
checking for --with-libm=STRING... default LIBM="-lm"
checking for --with-libc=STRING... default LIBC=""
checking for x64 gcc inline assembler... yes
checking whether C doubles are little-endian IEEE 754 binary64... yes
checking whether C doubles are big-endian IEEE 754 binary64... no
checking whether C doubles are ARM mixed-endian IEEE 754 binary64... no
checking whether we can use gcc inline assembler to get and set x87 control word... yes
checking whether we can use gcc inline assembler to get and set mc68881 fpcr... no
checking for x87-style double rounding... no
checking for acosh... yes
checking for asinh... yes
checking for atanh... yes
checking for copysign... yes
checking for erf... yes
checking for erfc... yes
checking for expm1... yes
checking for finite... yes
checking for gamma... yes
checking for hypot... yes
checking for lgamma... yes
checking for log1p... yes
checking for log2... yes
checking for round... yes
checking for tgamma... yes
checking whether isinf is declared... yes
checking whether isnan is declared... yes
checking whether isfinite is declared... yes
checking whether tanh preserves the sign of zero... yes
checking whether log1p drops the sign of negative zero... no
checking whether POSIX semaphores are enabled... yes
checking for broken sem_getvalue... no
checking whether RTLD_LAZY is declared... yes
checking whether RTLD_NOW is declared... yes
checking whether RTLD_GLOBAL is declared... yes
checking whether RTLD_LOCAL is declared... yes
checking whether RTLD_NODELETE is declared... yes
checking whether RTLD_NOLOAD is declared... yes
checking whether RTLD_DEEPBIND is declared... yes
checking whether RTLD_MEMBER is declared... no
checking digit size for Python's longs... no value specified
checking wchar.h usability... yes
checking wchar.h presence... yes
checking for wchar.h... yes
checking size of wchar_t... 4
checking for UCS-4 tcl... no
checking whether wchar_t is signed... yes
checking whether wchar_t is usable... no
checking whether byte ordering is bigendian... no
checking ABIFLAGS... m
checking SOABI... cpython-37m-x86_64-linux-gnu
checking LDVERSION... $(VERSION)$(ABIFLAGS)
checking whether right shift extends the sign bit... yes
checking for getc_unlocked() and friends... yes
checking how to link readline libs... -lreadline
checking for rl_pre_input_hook in -lreadline... yes
checking for rl_completion_display_matches_hook in -lreadline... yes
checking for rl_resize_terminal in -lreadline... yes
checking for rl_completion_matches in -lreadline... yes
checking for append_history in -lreadline... yes
checking for broken nice()... no
checking for broken poll()... no
checking for working tzset()... yes
checking for tv_nsec in struct stat... yes
checking for tv_nsec2 in struct stat... no
checking curses.h usability... yes
checking curses.h presence... yes
checking for curses.h... yes
checking ncurses.h usability... yes
checking ncurses.h presence... yes
checking for ncurses.h... yes
checking for term.h... yes
checking whether mvwdelch is an expression... yes
checking whether WINDOW has _flags... yes
checking for is_pad... no
checking for is_term_resized... yes
checking for resize_term... yes
checking for resizeterm... yes
checking for immedok... yes
checking for syncok... yes
checking for wchgat... yes
checking for filter... yes
checking for has_key... yes
checking for typeahead... yes
checking for use_env... yes
configure: checking for device files
checking for /dev/ptmx... yes
checking for /dev/ptc... no
checking for %zd printf() format support... yes
checking for socklen_t... yes
checking for broken mbstowcs... no
checking for --with-computed-gotos... no value specified
checking whether gcc -pthread supports computed gotos... yes
checking for build directories... done
checking for -O2... yes
checking for glibc _FORTIFY_SOURCE/memmove bug... no
checking for gcc ipa-pure-const bug... no
checking for stdatomic.h... no
checking for GCC >= 4.7 __atomic builtins... yes
checking for ensurepip... install
checking if the dirent structure of a d_type field... yes
checking for the Linux getrandom() syscall... no
checking for the getrandom() function... no
checking for pkg-config... /usr/bin/pkg-config
checking whether compiling and linking against OpenSSL works... yes
checking for X509_VERIFY_PARAM_set1_host in libssl... no
checking for --with-ssl-default-suites... python
configure: creating ./config.status
config.status: creating Makefile.pre
config.status: creating Misc/python.pc
config.status: creating Misc/python-config.sh
config.status: creating Modules/ld_so_aix
config.status: creating pyconfig.h
creating Modules/Setup
creating Modules/Setup.local
creating Makefile
gail01@login1: /sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2 $ make -j 8
Running code to generate profile data (this can take a while):
# First, we need to create a clean build with profile generation
# enabled.
make profile-gen-stamp
make[1]: Entering directory `/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2'
make clean profile-removal
make[2]: Entering directory `/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2'
find . -depth -name '__pycache__' -exec rm -rf {} ';'
find . -name '*.gc??' -exec rm -f {} ';'
find . -name '*.py[co]' -exec rm -f {} ';'
find . -name '*.profclang?' -exec rm -f {} ';'
find . -name '*.[oa]' -exec rm -f {} ';'
find . -name '*.dyn' -exec rm -f {} ';'
rm -f /sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/coverage.info
find . -name '*.s[ol]' -exec rm -f {} ';'
rm -rf /sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/lcov-report
rm -f profile-run-stamp
find . -name '*.so.[0-9]*.[0-9]*' -exec rm -f {} ';'
find build -name 'fficonfig.h' -exec rm -f {} ';' || true
find: `build': No such file or directory
find build -name '*.py' -exec rm -f {} ';' || true
find: `build': No such file or directory
find build -name '*.py[co]' -exec rm -f {} ';' || true
find: `build': No such file or directory
rm -f pybuilddir.txt
rm -f Lib/lib2to3/*Grammar*.pickle
rm -f Programs/_testembed Programs/_freeze_importlib
find build -type f -a ! -name '*.gc??' -exec rm -f {} ';'
find: `build': No such file or directory
make[2]: [clean] Error 1 (ignored)
rm -f Include/pydtrace_probes.h
rm -f profile-gen-stamp
make[2]: Leaving directory `/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2'
touch profile-clean-stamp
Building with support for profile generation:
make build_all_generate_profile
make[2]: Entering directory `/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2'
make build_all CFLAGS_NODIST=" -fprofile-generate" LDFLAGS_NODIST=" -fprofile-generate" LIBS="-lpthread -ldl  -lutil -lrt"
make[3]: Entering directory `/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2'
gcc -pthread -c -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall    -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-generate  -I. -I./Include   -fPIC -DPy_BUILD_CORE -o Programs/python.o ./Programs/python.c
gcc -pthread -c -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall    -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-generate  -I. -I./Include   -fPIC -DPy_BUILD_CORE -o Parser/acceler.o Parser/acceler.c
gcc -pthread -c -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall    -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-generate  -I. -I./Include   -fPIC -DPy_BUILD_CORE -o Parser/grammar1.o Parser/grammar1.c
gcc -pthread -c -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall    -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-generate  -I. -I./Include   -fPIC -DPy_BUILD_CORE -o Parser/listnode.o Parser/listnode.c
gcc -pthread -c -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall    -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-generate  -I. -I./Include   -fPIC -DPy_BUILD_CORE -o Parser/node.o Parser/node.c
gcc -pthread -c -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall    -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-generate  -I. -I./Include   -fPIC -DPy_BUILD_CORE -o Parser/parser.o Parser/parser.c
gcc -pthread -c -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall    -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-generate  -I. -I./Include   -fPIC -DPy_BUILD_CORE -o Parser/bitset.o Parser/bitset.c
gcc -pthread -c -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall    -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-generate  -I. -I./Include   -fPIC -DPy_BUILD_CORE -o Parser/metagrammar.o Parser/metagrammar.c
gcc -pthread -c -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall    -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-generate  -I. -I./Include   -fPIC -DPy_BUILD_CORE -o Parser/firstsets.o Parser/firstsets.c
gcc -pthread -c -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall    -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-generate  -I. -I./Include   -fPIC -DPy_BUILD_CORE -o Parser/grammar.o Parser/grammar.c
gcc -pthread -c -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall    -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-generate  -I. -I./Include   -fPIC -DPy_BUILD_CORE -o Parser/pgen.o Parser/pgen.c
gcc -pthread -c -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall    -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-generate  -I. -I./Include   -fPIC -DPy_BUILD_CORE -o Parser/myreadline.o Parser/myreadline.c
gcc -pthread -c -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall    -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-generate  -I. -I./Include   -fPIC -DPy_BUILD_CORE -o Parser/parsetok.o Parser/parsetok.c
gcc -pthread -c -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall    -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-generate  -I. -I./Include   -fPIC -DPy_BUILD_CORE -o Parser/tokenizer.o Parser/tokenizer.c
gcc -pthread -c -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall    -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-generate  -I. -I./Include   -fPIC -DPy_BUILD_CORE -o Objects/abstract.o Objects/abstract.c
gcc -pthread -c -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall    -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-generate  -I. -I./Include   -fPIC -DPy_BUILD_CORE -o Objects/accu.o Objects/accu.c
gcc -pthread -c -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall    -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-generate  -I. -I./Include   -fPIC -DPy_BUILD_CORE -o Objects/boolobject.o Objects/boolobject.c
gcc -pthread -c -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall    -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-generate  -I. -I./Include   -fPIC -DPy_BUILD_CORE -o Objects/bytes_methods.o Objects/bytes_methods.c
gcc -pthread -c -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall    -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-generate  -I. -I./Include   -fPIC -DPy_BUILD_CORE -o Objects/bytearrayobject.o Objects/bytearrayobject.c
gcc -pthread -c -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall    -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-generate  -I. -I./Include   -fPIC -DPy_BUILD_CORE -o Objects/bytesobject.o Objects/bytesobject.c
gcc -pthread -c -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall    -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-generate  -I. -I./Include   -fPIC -DPy_BUILD_CORE -o Objects/call.o Objects/call.c
gcc -pthread -c -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall    -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-generate  -I. -I./Include   -fPIC -DPy_BUILD_CORE -o Objects/cellobject.o Objects/cellobject.c
gcc -pthread -c -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall    -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-generate  -I. -I./Include   -fPIC -DPy_BUILD_CORE -o Objects/classobject.o Objects/classobject.c
gcc -pthread -c -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall    -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-generate  -I. -I./Include   -fPIC -DPy_BUILD_CORE -o Objects/codeobject.o Objects/codeobject.c
gcc -pthread -c -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall    -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-generate  -I. -I./Include   -fPIC -DPy_BUILD_CORE -o Objects/complexobject.o Objects/complexobject.c
gcc -pthread -c -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall    -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-generate  -I. -I./Include   -fPIC -DPy_BUILD_CORE -o Objects/descrobject.o Objects/descrobject.c
gcc -pthread -c -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall    -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-generate  -I. -I./Include   -fPIC -DPy_BUILD_CORE -o Objects/enumobject.o Objects/enumobject.c
gcc -pthread -c -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall    -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-generate  -I. -I./Include   -fPIC -DPy_BUILD_CORE -o Objects/exceptions.o Objects/exceptions.c
gcc -pthread -c -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall    -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-generate  -I. -I./Include   -fPIC -DPy_BUILD_CORE -o Objects/genobject.o Objects/genobject.c
gcc -pthread -c -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall    -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-generate  -I. -I./Include   -fPIC -DPy_BUILD_CORE -o Objects/fileobject.o Objects/fileobject.c
gcc -pthread -c -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall    -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-generate  -I. -I./Include   -fPIC -DPy_BUILD_CORE -o Objects/floatobject.o Objects/floatobject.c
gcc -pthread -c -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall    -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-generate  -I. -I./Include   -fPIC -DPy_BUILD_CORE -o Objects/frameobject.o Objects/frameobject.c
gcc -pthread -c -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall    -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-generate  -I. -I./Include   -fPIC -DPy_BUILD_CORE -o Objects/funcobject.o Objects/funcobject.c
gcc -pthread -c -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall    -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-generate  -I. -I./Include   -fPIC -DPy_BUILD_CORE -o Objects/iterobject.o Objects/iterobject.c
gcc -pthread -c -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall    -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-generate  -I. -I./Include   -fPIC -DPy_BUILD_CORE -o Objects/listobject.o Objects/listobject.c
gcc -pthread -c -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall    -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-generate  -I. -I./Include   -fPIC -DPy_BUILD_CORE -o Objects/longobject.o Objects/longobject.c
gcc -pthread -c -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall    -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-generate  -I. -I./Include   -fPIC -DPy_BUILD_CORE -o Objects/dictobject.o Objects/dictobject.c
gcc -pthread -c -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall    -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-generate  -I. -I./Include   -fPIC -DPy_BUILD_CORE -o Objects/odictobject.o Objects/odictobject.c
gcc -pthread -c -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall    -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-generate  -I. -I./Include   -fPIC -DPy_BUILD_CORE -o Objects/memoryobject.o Objects/memoryobject.c
gcc -pthread -c -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall    -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-generate  -I. -I./Include   -fPIC -DPy_BUILD_CORE -o Objects/methodobject.o Objects/methodobject.c
gcc -pthread -c -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall    -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-generate  -I. -I./Include   -fPIC -DPy_BUILD_CORE -o Objects/moduleobject.o Objects/moduleobject.c
gcc -pthread -c -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall    -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-generate  -I. -I./Include   -fPIC -DPy_BUILD_CORE -o Objects/namespaceobject.o Objects/namespaceobject.c
gcc -pthread -c -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall    -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-generate  -I. -I./Include   -fPIC -DPy_BUILD_CORE -o Objects/object.o Objects/object.c
gcc -pthread -c -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall    -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-generate  -I. -I./Include   -fPIC -DPy_BUILD_CORE -o Objects/obmalloc.o Objects/obmalloc.c
Objects/obmalloc.c:1351:1: warning: ‘no_sanitize_thread’ attribute directive ignored [-Wattributes]
 {
 ^
gcc -pthread -c -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall    -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-generate  -I. -I./Include   -fPIC -DPy_BUILD_CORE -o Objects/capsule.o Objects/capsule.c
gcc -pthread -c -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall    -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-generate  -I. -I./Include   -fPIC -DPy_BUILD_CORE -o Objects/rangeobject.o Objects/rangeobject.c
gcc -pthread -c -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall    -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-generate  -I. -I./Include   -fPIC -DPy_BUILD_CORE -o Objects/setobject.o Objects/setobject.c
gcc -pthread -c -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall    -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-generate  -I. -I./Include   -fPIC -DPy_BUILD_CORE -o Objects/sliceobject.o Objects/sliceobject.c
gcc -pthread -c -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall    -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-generate  -I. -I./Include   -fPIC -DPy_BUILD_CORE -o Objects/structseq.o Objects/structseq.c
gcc -pthread -c -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall    -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-generate  -I. -I./Include   -fPIC -DPy_BUILD_CORE -o Objects/tupleobject.o Objects/tupleobject.c
gcc -pthread -c -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall    -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-generate  -I. -I./Include   -fPIC -DPy_BUILD_CORE -o Objects/typeobject.o Objects/typeobject.c
gcc -pthread -c -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall    -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-generate  -I. -I./Include   -fPIC -DPy_BUILD_CORE -o Objects/unicodeobject.o Objects/unicodeobject.c
gcc -pthread -c -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall    -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-generate  -I. -I./Include   -fPIC -DPy_BUILD_CORE -o Objects/unicodectype.o Objects/unicodectype.c
gcc -pthread -c -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall    -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-generate  -I. -I./Include   -fPIC -DPy_BUILD_CORE -o Objects/weakrefobject.o Objects/weakrefobject.c
gcc -pthread -c -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall    -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-generate  -I. -I./Include   -fPIC -DPy_BUILD_CORE -o Python/_warnings.o Python/_warnings.c
gcc -pthread -c -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall    -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-generate  -I. -I./Include   -fPIC -DPy_BUILD_CORE -o Python/Python-ast.o Python/Python-ast.c
gcc -pthread -c -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall    -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-generate  -I. -I./Include   -fPIC -DPy_BUILD_CORE -o Python/asdl.o Python/asdl.c
gcc -pthread -c -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall    -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-generate  -I. -I./Include   -fPIC -DPy_BUILD_CORE -o Python/ast.o Python/ast.c
gcc -pthread -c -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall    -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-generate  -I. -I./Include   -fPIC -DPy_BUILD_CORE -o Python/ast_opt.o Python/ast_opt.c
gcc -pthread -c -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall    -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-generate  -I. -I./Include   -fPIC -DPy_BUILD_CORE -o Python/ast_unparse.o Python/ast_unparse.c
gcc -pthread -c -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall    -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-generate  -I. -I./Include   -fPIC -DPy_BUILD_CORE -o Python/bltinmodule.o Python/bltinmodule.c
gcc -pthread -c -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall    -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-generate  -I. -I./Include   -fPIC -DPy_BUILD_CORE -o Python/ceval.o Python/ceval.c
gcc -pthread -c -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall    -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-generate  -I. -I./Include   -fPIC -DPy_BUILD_CORE -o Python/compile.o Python/compile.c
gcc -pthread -c -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall    -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-generate  -I. -I./Include   -fPIC -DPy_BUILD_CORE -o Python/codecs.o Python/codecs.c
gcc -pthread -c -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall    -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-generate  -I. -I./Include   -fPIC -DPy_BUILD_CORE -o Python/dynamic_annotations.o Python/dynamic_annotations.c
gcc -pthread -c -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall    -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-generate  -I. -I./Include   -fPIC -DPy_BUILD_CORE -o Python/errors.o Python/errors.c
gcc -pthread -c -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall    -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-generate  -I. -I./Include   -fPIC -DPy_BUILD_CORE -o Python/frozenmain.o Python/frozenmain.c
gcc -pthread -c -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall    -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-generate  -I. -I./Include   -fPIC -DPy_BUILD_CORE -o Python/future.o Python/future.c
gcc -pthread -c -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall    -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-generate  -I. -I./Include   -fPIC -DPy_BUILD_CORE -o Python/getargs.o Python/getargs.c
gcc -pthread -c -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall    -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-generate  -I. -I./Include   -fPIC -DPy_BUILD_CORE -o Python/getcompiler.o Python/getcompiler.c
gcc -pthread -c -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall    -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-generate  -I. -I./Include   -fPIC -DPy_BUILD_CORE -o Python/getcopyright.o Python/getcopyright.c
gcc -pthread -c -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall    -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-generate  -I. -I./Include   -fPIC -DPy_BUILD_CORE -DPLATFORM='"linux"' -o Python/getplatform.o ./Python/getplatform.c
gcc -pthread -c -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall    -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-generate  -I. -I./Include   -fPIC -DPy_BUILD_CORE -o Python/getversion.o Python/getversion.c
gcc -pthread -c -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall    -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-generate  -I. -I./Include   -fPIC -DPy_BUILD_CORE -o Python/graminit.o Python/graminit.c
gcc -pthread -c -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall    -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-generate  -I. -I./Include   -fPIC -DPy_BUILD_CORE -o Python/import.o Python/import.c
gcc -pthread -c -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall    -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-generate  -I. -I./Include   -fPIC -DPy_BUILD_CORE -I. -o Python/importdl.o ./Python/importdl.c
gcc -pthread -c -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall    -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-generate  -I. -I./Include   -fPIC -DPy_BUILD_CORE -o Python/marshal.o Python/marshal.c
gcc -pthread -c -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall    -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-generate  -I. -I./Include   -fPIC -DPy_BUILD_CORE -o Python/modsupport.o Python/modsupport.c
gcc -pthread -c -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall    -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-generate  -I. -I./Include   -fPIC -DPy_BUILD_CORE -o Python/mysnprintf.o Python/mysnprintf.c
gcc -pthread -c -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall    -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-generate  -I. -I./Include   -fPIC -DPy_BUILD_CORE -o Python/mystrtoul.o Python/mystrtoul.c
gcc -pthread -c -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall    -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-generate  -I. -I./Include   -fPIC -DPy_BUILD_CORE -o Python/pathconfig.o Python/pathconfig.c
gcc -pthread -c -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall    -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-generate  -I. -I./Include   -fPIC -DPy_BUILD_CORE -o Python/peephole.o Python/peephole.c
gcc -pthread -c -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall    -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-generate  -I. -I./Include   -fPIC -DPy_BUILD_CORE -o Python/pyarena.o Python/pyarena.c
gcc -pthread -c -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall    -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-generate  -I. -I./Include   -fPIC -DPy_BUILD_CORE -o Python/pyctype.o Python/pyctype.c
gcc -pthread -c -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall    -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-generate  -I. -I./Include   -fPIC -DPy_BUILD_CORE -o Python/pyfpe.o Python/pyfpe.c
gcc -pthread -c -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall    -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-generate  -I. -I./Include   -fPIC -DPy_BUILD_CORE -o Python/pyhash.o Python/pyhash.c
gcc -pthread -c -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall    -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-generate  -I. -I./Include   -fPIC -DPy_BUILD_CORE -o Python/pylifecycle.o Python/pylifecycle.c
gcc -pthread -c -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall    -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-generate  -I. -I./Include   -fPIC -DPy_BUILD_CORE -o Python/pymath.o Python/pymath.c
gcc -pthread -c -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall    -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-generate  -I. -I./Include   -fPIC -DPy_BUILD_CORE -o Python/pystate.o Python/pystate.c
gcc -pthread -c -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall    -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-generate  -I. -I./Include   -fPIC -DPy_BUILD_CORE -o Python/context.o Python/context.c
gcc -pthread -c -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall    -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-generate  -I. -I./Include   -fPIC -DPy_BUILD_CORE -o Python/hamt.o Python/hamt.c
gcc -pthread -c -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall    -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-generate  -I. -I./Include   -fPIC -DPy_BUILD_CORE -o Python/pythonrun.o Python/pythonrun.c
gcc -pthread -c -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall    -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-generate  -I. -I./Include   -fPIC -DPy_BUILD_CORE -o Python/pytime.o Python/pytime.c
gcc -pthread -c -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall    -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-generate  -I. -I./Include   -fPIC -DPy_BUILD_CORE -o Python/bootstrap_hash.o Python/bootstrap_hash.c
gcc -pthread -c -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall    -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-generate  -I. -I./Include   -fPIC -DPy_BUILD_CORE -o Python/structmember.o Python/structmember.c
gcc -pthread -c -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall    -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-generate  -I. -I./Include   -fPIC -DPy_BUILD_CORE -o Python/symtable.o Python/symtable.c
gcc -pthread -c -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall    -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-generate  -I. -I./Include   -fPIC -DPy_BUILD_CORE \
		-DABIFLAGS='"m"' \
		-DMULTIARCH=\"x86_64-linux-gnu\" \
		-o Python/sysmodule.o ./Python/sysmodule.c
gcc -pthread -c -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall    -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-generate  -I. -I./Include   -fPIC -DPy_BUILD_CORE -o Python/thread.o Python/thread.c
gcc -pthread -c -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall    -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-generate  -I. -I./Include   -fPIC -DPy_BUILD_CORE -o Python/traceback.o Python/traceback.c
gcc -pthread -c -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall    -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-generate  -I. -I./Include   -fPIC -DPy_BUILD_CORE -o Python/getopt.o Python/getopt.c
gcc -pthread -c -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall    -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-generate  -I. -I./Include   -fPIC -DPy_BUILD_CORE -o Python/pystrcmp.o Python/pystrcmp.c
gcc -pthread -c -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall    -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-generate  -I. -I./Include   -fPIC -DPy_BUILD_CORE -o Python/pystrtod.o Python/pystrtod.c
gcc -pthread -c -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall    -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-generate  -I. -I./Include   -fPIC -DPy_BUILD_CORE -o Python/pystrhex.o Python/pystrhex.c
gcc -pthread -c -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall    -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-generate  -I. -I./Include   -fPIC -DPy_BUILD_CORE  -o Python/dtoa.o Python/dtoa.c
gcc -pthread -c -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall    -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-generate  -I. -I./Include   -fPIC -DPy_BUILD_CORE -o Python/formatter_unicode.o Python/formatter_unicode.c
gcc -pthread -c -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall    -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-generate  -I. -I./Include   -fPIC -DPy_BUILD_CORE -o Python/fileutils.o Python/fileutils.c
gcc -pthread -c -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall    -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-generate  -I. -I./Include   -fPIC -DPy_BUILD_CORE \
		-DSOABI='"cpython-37m-x86_64-linux-gnu"' \
		-o Python/dynload_shlib.o ./Python/dynload_shlib.c
gcc -pthread -c -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall    -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-generate  -I. -I./Include   -fPIC -DPy_BUILD_CORE -o Modules/config.o Modules/config.c
gcc -pthread -c -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall    -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-generate  -I. -I./Include   -fPIC -DPy_BUILD_CORE -DPYTHONPATH='""' \
		-DPREFIX='"/sc/orga/packages/lili_tem/pkg/python"' \
		-DEXEC_PREFIX='"/sc/orga/packages/lili_tem/pkg/python"' \
		-DVERSION='"3.7"' \
		-DVPATH='""' \
		-o Modules/getpath.o ./Modules/getpath.c
gcc -pthread -c -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall    -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-generate  -I. -I./Include   -fPIC -DPy_BUILD_CORE -o Modules/main.o Modules/main.c
gcc -pthread -c -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall    -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-generate  -I. -I./Include   -fPIC -DPy_BUILD_CORE -o Modules/gcmodule.o Modules/gcmodule.c
gcc -pthread -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall    -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-generate  -I. -I./Include   -fPIC -DPy_BUILD_CORE_BUILTIN  -DPy_BUILD_CORE -c ./Modules/posixmodule.c -o Modules/posixmodule.o
gcc -pthread -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall    -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-generate  -I. -I./Include   -fPIC -DPy_BUILD_CORE_BUILTIN  -c ./Modules/errnomodule.c -o Modules/errnomodule.o
gcc -pthread -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall    -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-generate  -I. -I./Include   -fPIC -DPy_BUILD_CORE_BUILTIN  -c ./Modules/pwdmodule.c -o Modules/pwdmodule.o
gcc -pthread -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall    -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-generate  -I. -I./Include   -fPIC -DPy_BUILD_CORE_BUILTIN  -c ./Modules/_sre.c -o Modules/_sre.o
gcc -pthread -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall    -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-generate  -I. -I./Include   -fPIC -DPy_BUILD_CORE_BUILTIN  -c ./Modules/_codecsmodule.c -o Modules/_codecsmodule.o
gcc -pthread -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall    -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-generate  -I. -I./Include   -fPIC -DPy_BUILD_CORE_BUILTIN  -c ./Modules/_weakref.c -o Modules/_weakref.o
gcc -pthread -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall    -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-generate  -I. -I./Include   -fPIC -DPy_BUILD_CORE_BUILTIN  -DPy_BUILD_CORE -c ./Modules/_functoolsmodule.c -o Modules/_functoolsmodule.o
gcc -pthread -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall    -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-generate  -I. -I./Include   -fPIC -DPy_BUILD_CORE_BUILTIN  -c ./Modules/_operator.c -o Modules/_operator.o
gcc -pthread -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall    -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-generate  -I. -I./Include   -fPIC -DPy_BUILD_CORE_BUILTIN  -c ./Modules/_collectionsmodule.c -o Modules/_collectionsmodule.o
gcc -pthread -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall    -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-generate  -I. -I./Include   -fPIC -DPy_BUILD_CORE_BUILTIN  -c ./Modules/_abc.c -o Modules/_abc.o
gcc -pthread -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall    -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-generate  -I. -I./Include   -fPIC -DPy_BUILD_CORE_BUILTIN  -c ./Modules/itertoolsmodule.c -o Modules/itertoolsmodule.o
gcc -pthread -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall    -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-generate  -I. -I./Include   -fPIC -DPy_BUILD_CORE_BUILTIN  -c ./Modules/atexitmodule.c -o Modules/atexitmodule.o
gcc -pthread -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall    -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-generate  -I. -I./Include   -fPIC -DPy_BUILD_CORE_BUILTIN  -DPy_BUILD_CORE -c ./Modules/signalmodule.c -o Modules/signalmodule.o
gcc -pthread -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall    -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-generate  -I. -I./Include   -fPIC -DPy_BUILD_CORE_BUILTIN  -c ./Modules/_stat.c -o Modules/_stat.o
gcc -pthread -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall    -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-generate  -I. -I./Include   -fPIC -DPy_BUILD_CORE_BUILTIN  -DPy_BUILD_CORE -c ./Modules/timemodule.c -o Modules/timemodule.o
gcc -pthread -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall    -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-generate  -I. -I./Include   -fPIC -DPy_BUILD_CORE_BUILTIN  -DPy_BUILD_CORE -c ./Modules/_threadmodule.c -o Modules/_threadmodule.o
gcc -pthread -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall    -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-generate  -I. -I./Include   -fPIC -DPy_BUILD_CORE_BUILTIN  -c ./Modules/_localemodule.c -o Modules/_localemodule.o
gcc -pthread -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall    -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-generate  -I. -I./Include   -fPIC -DPy_BUILD_CORE_BUILTIN  -DPy_BUILD_CORE -I./Modules/_io -c ./Modules/_io/_iomodule.c -o Modules/_iomodule.o
gcc -pthread -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall    -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-generate  -I. -I./Include   -fPIC -DPy_BUILD_CORE_BUILTIN  -DPy_BUILD_CORE -I./Modules/_io -c ./Modules/_io/iobase.c -o Modules/iobase.o
gcc -pthread -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall    -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-generate  -I. -I./Include   -fPIC -DPy_BUILD_CORE_BUILTIN  -DPy_BUILD_CORE -I./Modules/_io -c ./Modules/_io/fileio.c -o Modules/fileio.o
gcc -pthread -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall    -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-generate  -I. -I./Include   -fPIC -DPy_BUILD_CORE_BUILTIN  -DPy_BUILD_CORE -I./Modules/_io -c ./Modules/_io/bytesio.c -o Modules/bytesio.o
gcc -pthread -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall    -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-generate  -I. -I./Include   -fPIC -DPy_BUILD_CORE_BUILTIN  -DPy_BUILD_CORE -I./Modules/_io -c ./Modules/_io/bufferedio.c -o Modules/bufferedio.o
gcc -pthread -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall    -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-generate  -I. -I./Include   -fPIC -DPy_BUILD_CORE_BUILTIN  -DPy_BUILD_CORE -I./Modules/_io -c ./Modules/_io/textio.c -o Modules/textio.o
gcc -pthread -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall    -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-generate  -I. -I./Include   -fPIC -DPy_BUILD_CORE_BUILTIN  -DPy_BUILD_CORE -I./Modules/_io -c ./Modules/_io/stringio.c -o Modules/stringio.o
gcc -pthread -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall    -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-generate  -I. -I./Include   -fPIC -DPy_BUILD_CORE_BUILTIN  -DPy_BUILD_CORE -c ./Modules/zipimport.c -o Modules/zipimport.o
gcc -pthread -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall    -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-generate  -I. -I./Include   -fPIC -DPy_BUILD_CORE_BUILTIN  -c ./Modules/faulthandler.c -o Modules/faulthandler.o
gcc -pthread -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall    -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-generate  -I. -I./Include   -fPIC -DPy_BUILD_CORE_BUILTIN  -c ./Modules/_tracemalloc.c -o Modules/_tracemalloc.o
gcc -pthread -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall    -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-generate  -I. -I./Include   -fPIC -DPy_BUILD_CORE_BUILTIN  -c ./Modules/hashtable.c -o Modules/hashtable.o
gcc -pthread -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall    -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-generate  -I. -I./Include   -fPIC -DPy_BUILD_CORE_BUILTIN  -c ./Modules/symtablemodule.c -o Modules/symtablemodule.o
gcc -pthread -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall    -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-generate  -I. -I./Include   -fPIC -DPy_BUILD_CORE_BUILTIN  -c ./Modules/xxsubtype.c -o Modules/xxsubtype.o
gcc -pthread -c -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall    -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-generate  -I. -I./Include   -fPIC -DPy_BUILD_CORE -o Python/frozen.o Python/frozen.c
gcc -pthread -c -fPIC -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall    -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-generate  -I. -I./Include   -fPIC -DPy_BUILD_CORE -o Modules/_math.o Modules/_math.c
/usr/bin/install -c -m 644 ./Tools/gdb/libpython.py python-gdb.py
gcc -pthread -c -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall    -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-generate  -I. -I./Include   -fPIC -DPy_BUILD_CORE -o Programs/_testembed.o ./Programs/_testembed.c
sed -e "s,@EXENAME@,/sc/orga/packages/lili_tem/pkg/python/bin/python3.7m," < ./Misc/python-config.in >python-config.py
LC_ALL=C sed -e 's,\$(\([A-Za-z0-9_]*\)),\$\{\1\},g' < Misc/python-config.sh >python-config
gcc -pthread -c -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall    -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-generate  -I. -I./Include   -fPIC -DPy_BUILD_CORE \
	      -DGITVERSION="\"`LC_ALL=C `\"" \
	      -DGITTAG="\"`LC_ALL=C `\"" \
	      -DGITBRANCH="\"`LC_ALL=C `\"" \
	      -o Modules/getbuildinfo.o ./Modules/getbuildinfo.c
rm -f libpython3.7m.a
if test libpython3.7m.so.1.0 != libpython3.7m.so; then \
		gcc -pthread -shared    -fprofile-generate -Wl,-hlibpython3.7m.so.1.0 -o libpython3.7m.so.1.0 Modules/getbuildinfo.o Parser/acceler.o Parser/grammar1.o Parser/listnode.o Parser/node.o Parser/parser.o Parser/bitset.o Parser/metagrammar.o Parser/firstsets.o Parser/grammar.o Parser/pgen.o Parser/myreadline.o Parser/parsetok.o Parser/tokenizer.o Objects/abstract.o Objects/accu.o Objects/boolobject.o Objects/bytes_methods.o Objects/bytearrayobject.o Objects/bytesobject.o Objects/call.o Objects/cellobject.o Objects/classobject.o Objects/codeobject.o Objects/complexobject.o Objects/descrobject.o Objects/enumobject.o Objects/exceptions.o Objects/genobject.o Objects/fileobject.o Objects/floatobject.o Objects/frameobject.o Objects/funcobject.o Objects/iterobject.o Objects/listobject.o Objects/longobject.o Objects/dictobject.o Objects/odictobject.o Objects/memoryobject.o Objects/methodobject.o Objects/moduleobject.o Objects/namespaceobject.o Objects/object.o Objects/obmalloc.o Objects/capsule.o Objects/rangeobject.o Objects/setobject.o Objects/sliceobject.o Objects/structseq.o Objects/tupleobject.o Objects/typeobject.o Objects/unicodeobject.o Objects/unicodectype.o Objects/weakrefobject.o Python/_warnings.o Python/Python-ast.o Python/asdl.o Python/ast.o Python/ast_opt.o Python/ast_unparse.o Python/bltinmodule.o Python/ceval.o Python/compile.o Python/codecs.o Python/dynamic_annotations.o Python/errors.o Python/frozenmain.o Python/future.o Python/getargs.o Python/getcompiler.o Python/getcopyright.o Python/getplatform.o Python/getversion.o Python/graminit.o Python/import.o Python/importdl.o Python/marshal.o Python/modsupport.o Python/mysnprintf.o Python/mystrtoul.o Python/pathconfig.o Python/peephole.o Python/pyarena.o Python/pyctype.o Python/pyfpe.o Python/pyhash.o Python/pylifecycle.o Python/pymath.o Python/pystate.o Python/context.o Python/hamt.o Python/pythonrun.o Python/pytime.o Python/bootstrap_hash.o Python/structmember.o Python/symtable.o Python/sysmodule.o Python/thread.o Python/traceback.o Python/getopt.o Python/pystrcmp.o Python/pystrtod.o Python/pystrhex.o Python/dtoa.o Python/formatter_unicode.o Python/fileutils.o Python/dynload_shlib.o    Modules/config.o Modules/getpath.o Modules/main.o Modules/gcmodule.o Modules/posixmodule.o  Modules/errnomodule.o  Modules/pwdmodule.o  Modules/_sre.o  Modules/_codecsmodule.o  Modules/_weakref.o  Modules/_functoolsmodule.o  Modules/_operator.o  Modules/_collectionsmodule.o  Modules/_abc.o  Modules/itertoolsmodule.o  Modules/atexitmodule.o  Modules/signalmodule.o  Modules/_stat.o  Modules/timemodule.o  Modules/_threadmodule.o  Modules/_localemodule.o  Modules/_iomodule.o Modules/iobase.o Modules/fileio.o Modules/bytesio.o Modules/bufferedio.o Modules/textio.o Modules/stringio.o  Modules/zipimport.o  Modules/faulthandler.o  Modules/_tracemalloc.o Modules/hashtable.o  Modules/symtablemodule.o  Modules/xxsubtype.o Python/frozen.o   -lpthread -ldl  -lutil -lrt  -lm ; \
		ln -f libpython3.7m.so.1.0 libpython3.7m.so; \
	else \
		gcc -pthread -shared    -fprofile-generate -o libpython3.7m.so Modules/getbuildinfo.o Parser/acceler.o Parser/grammar1.o Parser/listnode.o Parser/node.o Parser/parser.o Parser/bitset.o Parser/metagrammar.o Parser/firstsets.o Parser/grammar.o Parser/pgen.o Parser/myreadline.o Parser/parsetok.o Parser/tokenizer.o Objects/abstract.o Objects/accu.o Objects/boolobject.o Objects/bytes_methods.o Objects/bytearrayobject.o Objects/bytesobject.o Objects/call.o Objects/cellobject.o Objects/classobject.o Objects/codeobject.o Objects/complexobject.o Objects/descrobject.o Objects/enumobject.o Objects/exceptions.o Objects/genobject.o Objects/fileobject.o Objects/floatobject.o Objects/frameobject.o Objects/funcobject.o Objects/iterobject.o Objects/listobject.o Objects/longobject.o Objects/dictobject.o Objects/odictobject.o Objects/memoryobject.o Objects/methodobject.o Objects/moduleobject.o Objects/namespaceobject.o Objects/object.o Objects/obmalloc.o Objects/capsule.o Objects/rangeobject.o Objects/setobject.o Objects/sliceobject.o Objects/structseq.o Objects/tupleobject.o Objects/typeobject.o Objects/unicodeobject.o Objects/unicodectype.o Objects/weakrefobject.o Python/_warnings.o Python/Python-ast.o Python/asdl.o Python/ast.o Python/ast_opt.o Python/ast_unparse.o Python/bltinmodule.o Python/ceval.o Python/compile.o Python/codecs.o Python/dynamic_annotations.o Python/errors.o Python/frozenmain.o Python/future.o Python/getargs.o Python/getcompiler.o Python/getcopyright.o Python/getplatform.o Python/getversion.o Python/graminit.o Python/import.o Python/importdl.o Python/marshal.o Python/modsupport.o Python/mysnprintf.o Python/mystrtoul.o Python/pathconfig.o Python/peephole.o Python/pyarena.o Python/pyctype.o Python/pyfpe.o Python/pyhash.o Python/pylifecycle.o Python/pymath.o Python/pystate.o Python/context.o Python/hamt.o Python/pythonrun.o Python/pytime.o Python/bootstrap_hash.o Python/structmember.o Python/symtable.o Python/sysmodule.o Python/thread.o Python/traceback.o Python/getopt.o Python/pystrcmp.o Python/pystrtod.o Python/pystrhex.o Python/dtoa.o Python/formatter_unicode.o Python/fileutils.o Python/dynload_shlib.o    Modules/config.o Modules/getpath.o Modules/main.o Modules/gcmodule.o Modules/posixmodule.o  Modules/errnomodule.o  Modules/pwdmodule.o  Modules/_sre.o  Modules/_codecsmodule.o  Modules/_weakref.o  Modules/_functoolsmodule.o  Modules/_operator.o  Modules/_collectionsmodule.o  Modules/_abc.o  Modules/itertoolsmodule.o  Modules/atexitmodule.o  Modules/signalmodule.o  Modules/_stat.o  Modules/timemodule.o  Modules/_threadmodule.o  Modules/_localemodule.o  Modules/_iomodule.o Modules/iobase.o Modules/fileio.o Modules/bytesio.o Modules/bufferedio.o Modules/textio.o Modules/stringio.o  Modules/zipimport.o  Modules/faulthandler.o  Modules/_tracemalloc.o Modules/hashtable.o  Modules/symtablemodule.o  Modules/xxsubtype.o Python/frozen.o   -lpthread -ldl  -lutil -lrt  -lm ; \
	fi
ar rcs libpython3.7m.a Modules/getbuildinfo.o Parser/acceler.o Parser/grammar1.o Parser/listnode.o Parser/node.o Parser/parser.o Parser/bitset.o Parser/metagrammar.o Parser/firstsets.o Parser/grammar.o Parser/pgen.o Parser/myreadline.o Parser/parsetok.o Parser/tokenizer.o Objects/abstract.o Objects/accu.o Objects/boolobject.o Objects/bytes_methods.o Objects/bytearrayobject.o Objects/bytesobject.o Objects/call.o Objects/cellobject.o Objects/classobject.o Objects/codeobject.o Objects/complexobject.o Objects/descrobject.o Objects/enumobject.o Objects/exceptions.o Objects/genobject.o Objects/fileobject.o Objects/floatobject.o Objects/frameobject.o Objects/funcobject.o Objects/iterobject.o Objects/listobject.o Objects/longobject.o Objects/dictobject.o Objects/odictobject.o Objects/memoryobject.o Objects/methodobject.o Objects/moduleobject.o Objects/namespaceobject.o Objects/object.o Objects/obmalloc.o Objects/capsule.o Objects/rangeobject.o Objects/setobject.o Objects/sliceobject.o Objects/structseq.o Objects/tupleobject.o Objects/typeobject.o Objects/unicodeobject.o Objects/unicodectype.o Objects/weakrefobject.o Python/_warnings.o Python/Python-ast.o Python/asdl.o Python/ast.o Python/ast_opt.o Python/ast_unparse.o Python/bltinmodule.o Python/ceval.o Python/compile.o Python/codecs.o Python/dynamic_annotations.o Python/errors.o Python/frozenmain.o Python/future.o Python/getargs.o Python/getcompiler.o Python/getcopyright.o Python/getplatform.o Python/getversion.o Python/graminit.o Python/import.o Python/importdl.o Python/marshal.o Python/modsupport.o Python/mysnprintf.o Python/mystrtoul.o Python/pathconfig.o Python/peephole.o Python/pyarena.o Python/pyctype.o Python/pyfpe.o Python/pyhash.o Python/pylifecycle.o Python/pymath.o Python/pystate.o Python/context.o Python/hamt.o Python/pythonrun.o Python/pytime.o Python/bootstrap_hash.o Python/structmember.o Python/symtable.o Python/sysmodule.o Python/thread.o Python/traceback.o Python/getopt.o Python/pystrcmp.o Python/pystrtod.o Python/pystrhex.o Python/dtoa.o Python/formatter_unicode.o Python/fileutils.o Python/dynload_shlib.o    Modules/config.o Modules/getpath.o Modules/main.o Modules/gcmodule.o Modules/posixmodule.o  Modules/errnomodule.o  Modules/pwdmodule.o  Modules/_sre.o  Modules/_codecsmodule.o  Modules/_weakref.o  Modules/_functoolsmodule.o  Modules/_operator.o  Modules/_collectionsmodule.o  Modules/_abc.o  Modules/itertoolsmodule.o  Modules/atexitmodule.o  Modules/signalmodule.o  Modules/_stat.o  Modules/timemodule.o  Modules/_threadmodule.o  Modules/_localemodule.o  Modules/_iomodule.o Modules/iobase.o Modules/fileio.o Modules/bytesio.o Modules/bufferedio.o Modules/textio.o Modules/stringio.o  Modules/zipimport.o  Modules/faulthandler.o  Modules/_tracemalloc.o Modules/hashtable.o  Modules/symtablemodule.o  Modules/xxsubtype.o Python/frozen.o
gcc -pthread -shared    -fprofile-generate -Wl,--no-as-needed -o libpython3.so -Wl,-hlibpython3.so libpython3.7m.so
gcc -pthread    -fprofile-generate -Xlinker -export-dynamic -o python Programs/python.o -L. -lpython3.7m -lpthread -ldl  -lutil -lrt   -lm  
gcc -pthread    -fprofile-generate -Xlinker -export-dynamic -o Programs/_testembed Programs/_testembed.o -L. -lpython3.7m -lpthread -ldl  -lutil -lrt   -lm  
LD_LIBRARY_PATH=/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2:/hpc/packages/minerva-common/gcc/4.8.2/lib64:/hpc/packages/minerva-common/gcc/4.8.2/lib:/hpc/packages/minerva-common/mpc/1.0.2/lib:/hpc/packages/minerva-common/mpc/1.0.2/lib64:/hpc/packages/minerva-common/mpfr/3.1.2/lib:/hpc/packages/minerva-common/gmp/5.1.3/lib64:/hpc/packages/minerva-common/gmp/5.1.3/lib:/hpc/lsf/9.1/linux2.6-glibc2.3-x86_64/lib ./python -E -S -m sysconfig --generate-posix-vars ;\
	if test $? -ne 0 ; then \
		echo "generate-posix-vars failed" ; \
		rm -f ./pybuilddir.txt ; \
		exit 1 ; \
	fi
LD_LIBRARY_PATH=/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2:/hpc/packages/minerva-common/gcc/4.8.2/lib64:/hpc/packages/minerva-common/gcc/4.8.2/lib:/hpc/packages/minerva-common/mpc/1.0.2/lib:/hpc/packages/minerva-common/mpc/1.0.2/lib64:/hpc/packages/minerva-common/mpfr/3.1.2/lib:/hpc/packages/minerva-common/gmp/5.1.3/lib64:/hpc/packages/minerva-common/gmp/5.1.3/lib:/hpc/lsf/9.1/linux2.6-glibc2.3-x86_64/lib CC='gcc -pthread' LDSHARED='gcc -pthread -shared    -fprofile-generate' OPT='-DNDEBUG -g -fwrapv -O3 -Wall' 	_TCLTK_INCLUDES='' _TCLTK_LIBS='' 	./python -E ./setup.py  build
running build
running build_ext
building '_struct' extension
creating build/temp.linux-x86_64-3.7/sc
creating build/temp.linux-x86_64-3.7/sc/orga
creating build/temp.linux-x86_64-3.7/sc/orga/packages
creating build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem
creating build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg
creating build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python
creating build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src
creating build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2
creating build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules
gcc -pthread -fPIC -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-generate -I./Include -I. -I/usr/local/include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2 -c /sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_struct.c -o build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_struct.o
gcc -pthread -shared -fprofile-generate build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_struct.o -L. -L/usr/local/lib -lpython3.7m -o build/lib.linux-x86_64-3.7/_struct.cpython-37m-x86_64-linux-gnu.so
building '_ctypes_test' extension
creating build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_ctypes
gcc -pthread -fPIC -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-generate -I./Include -I. -I/usr/local/include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2 -c /sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_ctypes/_ctypes_test.c -o build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_ctypes/_ctypes_test.o
gcc -pthread -shared -fprofile-generate build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_ctypes/_ctypes_test.o -L. -L/usr/local/lib -lm -lpython3.7m -o build/lib.linux-x86_64-3.7/_ctypes_test.cpython-37m-x86_64-linux-gnu.so
building 'array' extension
gcc -pthread -fPIC -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-generate -I./Include -I. -I/usr/local/include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2 -c /sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/arraymodule.c -o build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/arraymodule.o
gcc -pthread -shared -fprofile-generate build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/arraymodule.o -L. -L/usr/local/lib -lpython3.7m -o build/lib.linux-x86_64-3.7/array.cpython-37m-x86_64-linux-gnu.so
building '_contextvars' extension
gcc -pthread -fPIC -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-generate -I./Include -I. -I/usr/local/include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2 -c /sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_contextvarsmodule.c -o build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_contextvarsmodule.o
gcc -pthread -shared -fprofile-generate build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_contextvarsmodule.o -L. -L/usr/local/lib -lpython3.7m -o build/lib.linux-x86_64-3.7/_contextvars.cpython-37m-x86_64-linux-gnu.so
building 'cmath' extension
gcc -pthread -fPIC -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-generate -I./Include -I. -I/usr/local/include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2 -c /sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/cmathmodule.c -o build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/cmathmodule.o
gcc -pthread -shared -fprofile-generate build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/cmathmodule.o Modules/_math.o -L. -L/usr/local/lib -lm -lpython3.7m -o build/lib.linux-x86_64-3.7/cmath.cpython-37m-x86_64-linux-gnu.so
building 'math' extension
gcc -pthread -fPIC -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-generate -I./Include -I. -I/usr/local/include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2 -c /sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/mathmodule.c -o build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/mathmodule.o
gcc -pthread -shared -fprofile-generate build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/mathmodule.o Modules/_math.o -L. -L/usr/local/lib -lm -lpython3.7m -o build/lib.linux-x86_64-3.7/math.cpython-37m-x86_64-linux-gnu.so
building '_datetime' extension
gcc -pthread -fPIC -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-generate -I./Include -I. -I/usr/local/include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2 -c /sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_datetimemodule.c -o build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_datetimemodule.o
gcc -pthread -shared -fprofile-generate build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_datetimemodule.o -L. -L/usr/local/lib -lm -lpython3.7m -o build/lib.linux-x86_64-3.7/_datetime.cpython-37m-x86_64-linux-gnu.so
building '_random' extension
gcc -pthread -fPIC -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-generate -I./Include -I. -I/usr/local/include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2 -c /sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_randommodule.c -o build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_randommodule.o
gcc -pthread -shared -fprofile-generate build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_randommodule.o -L. -L/usr/local/lib -lpython3.7m -o build/lib.linux-x86_64-3.7/_random.cpython-37m-x86_64-linux-gnu.so
building '_bisect' extension
gcc -pthread -fPIC -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-generate -I./Include -I. -I/usr/local/include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2 -c /sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_bisectmodule.c -o build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_bisectmodule.o
gcc -pthread -shared -fprofile-generate build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_bisectmodule.o -L. -L/usr/local/lib -lpython3.7m -o build/lib.linux-x86_64-3.7/_bisect.cpython-37m-x86_64-linux-gnu.so
building '_heapq' extension
gcc -pthread -fPIC -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-generate -I./Include -I. -I/usr/local/include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2 -c /sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_heapqmodule.c -o build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_heapqmodule.o
gcc -pthread -shared -fprofile-generate build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_heapqmodule.o -L. -L/usr/local/lib -lpython3.7m -o build/lib.linux-x86_64-3.7/_heapq.cpython-37m-x86_64-linux-gnu.so
building '_pickle' extension
gcc -pthread -fPIC -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-generate -I./Include -I. -I/usr/local/include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2 -c /sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_pickle.c -o build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_pickle.o
gcc -pthread -shared -fprofile-generate build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_pickle.o -L. -L/usr/local/lib -lpython3.7m -o build/lib.linux-x86_64-3.7/_pickle.cpython-37m-x86_64-linux-gnu.so
building '_json' extension
gcc -pthread -fPIC -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-generate -I./Include -I. -I/usr/local/include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2 -c /sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_json.c -o build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_json.o
gcc -pthread -shared -fprofile-generate build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_json.o -L. -L/usr/local/lib -lpython3.7m -o build/lib.linux-x86_64-3.7/_json.cpython-37m-x86_64-linux-gnu.so
building '_testcapi' extension
gcc -pthread -fPIC -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-generate -I./Include -I. -I/usr/local/include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2 -c /sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_testcapimodule.c -o build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_testcapimodule.o
gcc -pthread -shared -fprofile-generate build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_testcapimodule.o -L. -L/usr/local/lib -lpython3.7m -o build/lib.linux-x86_64-3.7/_testcapi.cpython-37m-x86_64-linux-gnu.so
building '_testbuffer' extension
gcc -pthread -fPIC -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-generate -I./Include -I. -I/usr/local/include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2 -c /sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_testbuffer.c -o build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_testbuffer.o
gcc -pthread -shared -fprofile-generate build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_testbuffer.o -L. -L/usr/local/lib -lpython3.7m -o build/lib.linux-x86_64-3.7/_testbuffer.cpython-37m-x86_64-linux-gnu.so
building '_testimportmultiple' extension
gcc -pthread -fPIC -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-generate -I./Include -I. -I/usr/local/include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2 -c /sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_testimportmultiple.c -o build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_testimportmultiple.o
gcc -pthread -shared -fprofile-generate build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_testimportmultiple.o -L. -L/usr/local/lib -lpython3.7m -o build/lib.linux-x86_64-3.7/_testimportmultiple.cpython-37m-x86_64-linux-gnu.so
building '_testmultiphase' extension
gcc -pthread -fPIC -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-generate -I./Include -I. -I/usr/local/include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2 -c /sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_testmultiphase.c -o build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_testmultiphase.o
gcc -pthread -shared -fprofile-generate build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_testmultiphase.o -L. -L/usr/local/lib -lpython3.7m -o build/lib.linux-x86_64-3.7/_testmultiphase.cpython-37m-x86_64-linux-gnu.so
building '_lsprof' extension
gcc -pthread -fPIC -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-generate -I./Include -I. -I/usr/local/include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2 -c /sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_lsprof.c -o build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_lsprof.o
gcc -pthread -fPIC -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-generate -I./Include -I. -I/usr/local/include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2 -c /sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/rotatingtree.c -o build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/rotatingtree.o
gcc -pthread -shared -fprofile-generate build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_lsprof.o build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/rotatingtree.o -L. -L/usr/local/lib -lpython3.7m -o build/lib.linux-x86_64-3.7/_lsprof.cpython-37m-x86_64-linux-gnu.so
building 'unicodedata' extension
gcc -pthread -fPIC -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-generate -I./Include -I. -I/usr/local/include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2 -c /sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/unicodedata.c -o build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/unicodedata.o
gcc -pthread -shared -fprofile-generate build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/unicodedata.o -L. -L/usr/local/lib -lpython3.7m -o build/lib.linux-x86_64-3.7/unicodedata.cpython-37m-x86_64-linux-gnu.so
building '_opcode' extension
gcc -pthread -fPIC -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-generate -I./Include -I. -I/usr/local/include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2 -c /sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_opcode.c -o build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_opcode.o
gcc -pthread -shared -fprofile-generate build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_opcode.o -L. -L/usr/local/lib -lpython3.7m -o build/lib.linux-x86_64-3.7/_opcode.cpython-37m-x86_64-linux-gnu.so
building '_asyncio' extension
gcc -pthread -fPIC -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-generate -I./Include -I. -I/usr/local/include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2 -c /sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_asynciomodule.c -o build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_asynciomodule.o
gcc -pthread -shared -fprofile-generate build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_asynciomodule.o -L. -L/usr/local/lib -lpython3.7m -o build/lib.linux-x86_64-3.7/_asyncio.cpython-37m-x86_64-linux-gnu.so
building '_queue' extension
gcc -pthread -fPIC -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-generate -I./Include -I. -I/usr/local/include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2 -c /sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_queuemodule.c -o build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_queuemodule.o
gcc -pthread -shared -fprofile-generate build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_queuemodule.o -L. -L/usr/local/lib -lpython3.7m -o build/lib.linux-x86_64-3.7/_queue.cpython-37m-x86_64-linux-gnu.so
building 'fcntl' extension
gcc -pthread -fPIC -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-generate -I./Include -I. -I/usr/local/include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2 -c /sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/fcntlmodule.c -o build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/fcntlmodule.o
gcc -pthread -shared -fprofile-generate build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/fcntlmodule.o -L. -L/usr/local/lib -lpython3.7m -o build/lib.linux-x86_64-3.7/fcntl.cpython-37m-x86_64-linux-gnu.so
building 'grp' extension
gcc -pthread -fPIC -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-generate -I./Include -I. -I/usr/local/include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2 -c /sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/grpmodule.c -o build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/grpmodule.o
gcc -pthread -shared -fprofile-generate build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/grpmodule.o -L. -L/usr/local/lib -lpython3.7m -o build/lib.linux-x86_64-3.7/grp.cpython-37m-x86_64-linux-gnu.so
building 'spwd' extension
gcc -pthread -fPIC -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-generate -I./Include -I. -I/usr/local/include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2 -c /sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/spwdmodule.c -o build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/spwdmodule.o
gcc -pthread -shared -fprofile-generate build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/spwdmodule.o -L. -L/usr/local/lib -lpython3.7m -o build/lib.linux-x86_64-3.7/spwd.cpython-37m-x86_64-linux-gnu.so
building 'select' extension
gcc -pthread -fPIC -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-generate -I./Include -I. -I/usr/local/include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2 -c /sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/selectmodule.c -o build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/selectmodule.o
gcc -pthread -shared -fprofile-generate build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/selectmodule.o -L. -L/usr/local/lib -lpython3.7m -o build/lib.linux-x86_64-3.7/select.cpython-37m-x86_64-linux-gnu.so
building 'parser' extension
gcc -pthread -fPIC -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-generate -I./Include -I. -I/usr/local/include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2 -c /sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/parsermodule.c -o build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/parsermodule.o
gcc -pthread -shared -fprofile-generate build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/parsermodule.o -L. -L/usr/local/lib -lpython3.7m -o build/lib.linux-x86_64-3.7/parser.cpython-37m-x86_64-linux-gnu.so
building 'mmap' extension
gcc -pthread -fPIC -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-generate -I./Include -I. -I/usr/local/include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2 -c /sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/mmapmodule.c -o build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/mmapmodule.o
gcc -pthread -shared -fprofile-generate build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/mmapmodule.o -L. -L/usr/local/lib -lpython3.7m -o build/lib.linux-x86_64-3.7/mmap.cpython-37m-x86_64-linux-gnu.so
building 'syslog' extension
gcc -pthread -fPIC -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-generate -I./Include -I. -I/usr/local/include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2 -c /sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/syslogmodule.c -o build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/syslogmodule.o
gcc -pthread -shared -fprofile-generate build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/syslogmodule.o -L. -L/usr/local/lib -lpython3.7m -o build/lib.linux-x86_64-3.7/syslog.cpython-37m-x86_64-linux-gnu.so
building '_xxtestfuzz' extension
creating build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_xxtestfuzz
gcc -pthread -fPIC -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-generate -I./Include -I. -I/usr/local/include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2 -c /sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_xxtestfuzz/_xxtestfuzz.c -o build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_xxtestfuzz/_xxtestfuzz.o
gcc -pthread -fPIC -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-generate -I./Include -I. -I/usr/local/include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2 -c /sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_xxtestfuzz/fuzzer.c -o build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_xxtestfuzz/fuzzer.o
gcc -pthread -shared -fprofile-generate build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_xxtestfuzz/_xxtestfuzz.o build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_xxtestfuzz/fuzzer.o -L. -L/usr/local/lib -lpython3.7m -o build/lib.linux-x86_64-3.7/_xxtestfuzz.cpython-37m-x86_64-linux-gnu.so
building 'audioop' extension
gcc -pthread -fPIC -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-generate -I./Include -I. -I/usr/local/include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2 -c /sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/audioop.c -o build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/audioop.o
gcc -pthread -shared -fprofile-generate build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/audioop.o -L. -L/usr/local/lib -lm -lpython3.7m -o build/lib.linux-x86_64-3.7/audioop.cpython-37m-x86_64-linux-gnu.so
building 'readline' extension
gcc -pthread -fPIC -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-generate -I./Include -I. -I/usr/local/include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2 -c /sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/readline.c -o build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/readline.o
gcc -pthread -shared -fprofile-generate build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/readline.o -L/usr/lib/termcap -L. -L/usr/local/lib -lreadline -lpython3.7m -o build/lib.linux-x86_64-3.7/readline.cpython-37m-x86_64-linux-gnu.so
building '_crypt' extension
gcc -pthread -fPIC -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-generate -I./Include -I. -I/usr/local/include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2 -c /sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_cryptmodule.c -o build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_cryptmodule.o
gcc -pthread -shared -fprofile-generate build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_cryptmodule.o -L. -L/usr/local/lib -lcrypt -lpython3.7m -o build/lib.linux-x86_64-3.7/_crypt.cpython-37m-x86_64-linux-gnu.so
building '_csv' extension
gcc -pthread -fPIC -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-generate -I./Include -I. -I/usr/local/include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2 -c /sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_csv.c -o build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_csv.o
gcc -pthread -shared -fprofile-generate build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_csv.o -L. -L/usr/local/lib -lpython3.7m -o build/lib.linux-x86_64-3.7/_csv.cpython-37m-x86_64-linux-gnu.so
building '_posixsubprocess' extension
gcc -pthread -fPIC -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-generate -I./Include -I. -I/usr/local/include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2 -c /sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_posixsubprocess.c -o build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_posixsubprocess.o
gcc -pthread -shared -fprofile-generate build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_posixsubprocess.o -L. -L/usr/local/lib -lpython3.7m -o build/lib.linux-x86_64-3.7/_posixsubprocess.cpython-37m-x86_64-linux-gnu.so
building '_socket' extension
gcc -pthread -fPIC -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-generate -I./Include -I. -I/usr/local/include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2 -c /sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/socketmodule.c -o build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/socketmodule.o
gcc -pthread -shared -fprofile-generate build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/socketmodule.o -L. -L/usr/local/lib -lpython3.7m -o build/lib.linux-x86_64-3.7/_socket.cpython-37m-x86_64-linux-gnu.so
building '_hashlib' extension
gcc -pthread -fPIC -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-generate -I./Include -I. -I/usr/local/include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2 -c /sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_hashopenssl.c -o build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_hashopenssl.o
gcc -pthread -shared -fprofile-generate build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_hashopenssl.o -L. -L/usr/local/lib -lssl -lcrypto -lpython3.7m -o build/lib.linux-x86_64-3.7/_hashlib.cpython-37m-x86_64-linux-gnu.so
building '_sha256' extension
gcc -pthread -fPIC -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-generate -I./Include -I. -I/usr/local/include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2 -c /sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/sha256module.c -o build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/sha256module.o
gcc -pthread -shared -fprofile-generate build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/sha256module.o -L. -L/usr/local/lib -lpython3.7m -o build/lib.linux-x86_64-3.7/_sha256.cpython-37m-x86_64-linux-gnu.so
building '_sha512' extension
gcc -pthread -fPIC -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-generate -I./Include -I. -I/usr/local/include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2 -c /sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/sha512module.c -o build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/sha512module.o
gcc -pthread -shared -fprofile-generate build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/sha512module.o -L. -L/usr/local/lib -lpython3.7m -o build/lib.linux-x86_64-3.7/_sha512.cpython-37m-x86_64-linux-gnu.so
building '_md5' extension
gcc -pthread -fPIC -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-generate -I./Include -I. -I/usr/local/include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2 -c /sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/md5module.c -o build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/md5module.o
gcc -pthread -shared -fprofile-generate build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/md5module.o -L. -L/usr/local/lib -lpython3.7m -o build/lib.linux-x86_64-3.7/_md5.cpython-37m-x86_64-linux-gnu.so
building '_sha1' extension
gcc -pthread -fPIC -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-generate -I./Include -I. -I/usr/local/include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2 -c /sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/sha1module.c -o build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/sha1module.o
gcc -pthread -shared -fprofile-generate build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/sha1module.o -L. -L/usr/local/lib -lpython3.7m -o build/lib.linux-x86_64-3.7/_sha1.cpython-37m-x86_64-linux-gnu.so
building '_blake2' extension
creating build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_blake2
gcc -pthread -fPIC -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-generate -I./Include -I. -I/usr/local/include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2 -c /sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_blake2/blake2module.c -o build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_blake2/blake2module.o
gcc -pthread -fPIC -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-generate -I./Include -I. -I/usr/local/include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2 -c /sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_blake2/blake2b_impl.c -o build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_blake2/blake2b_impl.o
gcc -pthread -fPIC -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-generate -I./Include -I. -I/usr/local/include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2 -c /sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_blake2/blake2s_impl.c -o build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_blake2/blake2s_impl.o
gcc -pthread -shared -fprofile-generate build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_blake2/blake2module.o build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_blake2/blake2b_impl.o build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_blake2/blake2s_impl.o -L. -L/usr/local/lib -lpython3.7m -o build/lib.linux-x86_64-3.7/_blake2.cpython-37m-x86_64-linux-gnu.so
building '_sha3' extension
creating build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_sha3
gcc -pthread -fPIC -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-generate -I./Include -I. -I/usr/local/include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2 -c /sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_sha3/sha3module.c -o build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_sha3/sha3module.o
gcc -pthread -shared -fprofile-generate build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_sha3/sha3module.o -L. -L/usr/local/lib -lpython3.7m -o build/lib.linux-x86_64-3.7/_sha3.cpython-37m-x86_64-linux-gnu.so
building '_sqlite3' extension
creating build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_sqlite
gcc -pthread -fPIC -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-generate -DMODULE_NAME="sqlite3" -DSQLITE_OMIT_LOAD_EXTENSION=1 -IModules/_sqlite -I/usr/include -I./Include -I. -I/usr/local/include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2 -c /sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_sqlite/cache.c -o build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_sqlite/cache.o
gcc -pthread -fPIC -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-generate -DMODULE_NAME="sqlite3" -DSQLITE_OMIT_LOAD_EXTENSION=1 -IModules/_sqlite -I/usr/include -I./Include -I. -I/usr/local/include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2 -c /sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_sqlite/connection.c -o build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_sqlite/connection.o
gcc -pthread -fPIC -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-generate -DMODULE_NAME="sqlite3" -DSQLITE_OMIT_LOAD_EXTENSION=1 -IModules/_sqlite -I/usr/include -I./Include -I. -I/usr/local/include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2 -c /sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_sqlite/cursor.c -o build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_sqlite/cursor.o
gcc -pthread -fPIC -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-generate -DMODULE_NAME="sqlite3" -DSQLITE_OMIT_LOAD_EXTENSION=1 -IModules/_sqlite -I/usr/include -I./Include -I. -I/usr/local/include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2 -c /sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_sqlite/microprotocols.c -o build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_sqlite/microprotocols.o
gcc -pthread -fPIC -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-generate -DMODULE_NAME="sqlite3" -DSQLITE_OMIT_LOAD_EXTENSION=1 -IModules/_sqlite -I/usr/include -I./Include -I. -I/usr/local/include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2 -c /sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_sqlite/module.c -o build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_sqlite/module.o
gcc -pthread -fPIC -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-generate -DMODULE_NAME="sqlite3" -DSQLITE_OMIT_LOAD_EXTENSION=1 -IModules/_sqlite -I/usr/include -I./Include -I. -I/usr/local/include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2 -c /sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_sqlite/prepare_protocol.c -o build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_sqlite/prepare_protocol.o
gcc -pthread -fPIC -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-generate -DMODULE_NAME="sqlite3" -DSQLITE_OMIT_LOAD_EXTENSION=1 -IModules/_sqlite -I/usr/include -I./Include -I. -I/usr/local/include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2 -c /sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_sqlite/row.c -o build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_sqlite/row.o
gcc -pthread -fPIC -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-generate -DMODULE_NAME="sqlite3" -DSQLITE_OMIT_LOAD_EXTENSION=1 -IModules/_sqlite -I/usr/include -I./Include -I. -I/usr/local/include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2 -c /sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_sqlite/statement.c -o build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_sqlite/statement.o
gcc -pthread -fPIC -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-generate -DMODULE_NAME="sqlite3" -DSQLITE_OMIT_LOAD_EXTENSION=1 -IModules/_sqlite -I/usr/include -I./Include -I. -I/usr/local/include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2 -c /sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_sqlite/util.c -o build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_sqlite/util.o
gcc -pthread -shared -fprofile-generate build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_sqlite/cache.o build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_sqlite/connection.o build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_sqlite/cursor.o build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_sqlite/microprotocols.o build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_sqlite/module.o build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_sqlite/prepare_protocol.o build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_sqlite/row.o build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_sqlite/statement.o build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_sqlite/util.o -L. -L/usr/local/lib -lsqlite3 -lpython3.7m -o build/lib.linux-x86_64-3.7/_sqlite3.cpython-37m-x86_64-linux-gnu.so
building '_dbm' extension
gcc -pthread -fPIC -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-generate -DHAVE_GDBM_NDBM_H -I./Include -I. -I/usr/local/include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2 -c /sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_dbmmodule.c -o build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_dbmmodule.o
gcc -pthread -shared -fprofile-generate build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_dbmmodule.o -L. -L/usr/local/lib -lgdbm -lpython3.7m -o build/lib.linux-x86_64-3.7/_dbm.cpython-37m-x86_64-linux-gnu.so
building '_gdbm' extension
gcc -pthread -fPIC -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-generate -I./Include -I. -I/usr/local/include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2 -c /sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_gdbmmodule.c -o build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_gdbmmodule.o
gcc -pthread -shared -fprofile-generate build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_gdbmmodule.o -L. -L/usr/local/lib -lgdbm -lpython3.7m -o build/lib.linux-x86_64-3.7/_gdbm.cpython-37m-x86_64-linux-gnu.so
building 'termios' extension
gcc -pthread -fPIC -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-generate -I./Include -I. -I/usr/local/include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2 -c /sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/termios.c -o build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/termios.o
gcc -pthread -shared -fprofile-generate build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/termios.o -L. -L/usr/local/lib -lpython3.7m -o build/lib.linux-x86_64-3.7/termios.cpython-37m-x86_64-linux-gnu.so
building 'resource' extension
gcc -pthread -fPIC -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-generate -I./Include -I. -I/usr/local/include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2 -c /sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/resource.c -o build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/resource.o
gcc -pthread -shared -fprofile-generate build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/resource.o -L. -L/usr/local/lib -lpython3.7m -o build/lib.linux-x86_64-3.7/resource.cpython-37m-x86_64-linux-gnu.so
building 'nis' extension
gcc -pthread -fPIC -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-generate -I./Include -I. -I/usr/local/include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2 -c /sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/nismodule.c -o build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/nismodule.o
gcc -pthread -shared -fprofile-generate build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/nismodule.o -L. -L/usr/local/lib -lnsl -lpython3.7m -o build/lib.linux-x86_64-3.7/nis.cpython-37m-x86_64-linux-gnu.so
building '_curses' extension
gcc -pthread -fPIC -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-generate -DHAVE_NCURSESW=1 -I/usr/include/ncursesw -I./Include -I. -I/usr/local/include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2 -c /sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_cursesmodule.c -o build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_cursesmodule.o
gcc -pthread -shared -fprofile-generate build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_cursesmodule.o -L. -L/usr/local/lib -lncursesw -lpython3.7m -o build/lib.linux-x86_64-3.7/_curses.cpython-37m-x86_64-linux-gnu.so
building '_curses_panel' extension
gcc -pthread -fPIC -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-generate -DHAVE_NCURSESW=1 -I/usr/include/ncursesw -I./Include -I. -I/usr/local/include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2 -c /sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_curses_panel.c -o build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_curses_panel.o
gcc -pthread -shared -fprofile-generate build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_curses_panel.o -L. -L/usr/local/lib -lpanelw -lncursesw -lpython3.7m -o build/lib.linux-x86_64-3.7/_curses_panel.cpython-37m-x86_64-linux-gnu.so
building 'zlib' extension
gcc -pthread -fPIC -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-generate -I./Include -I. -I/usr/local/include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2 -c /sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/zlibmodule.c -o build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/zlibmodule.o
gcc -pthread -shared -fprofile-generate build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/zlibmodule.o -L. -L/usr/local/lib -lz -lpython3.7m -o build/lib.linux-x86_64-3.7/zlib.cpython-37m-x86_64-linux-gnu.so
building 'binascii' extension
gcc -pthread -fPIC -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-generate -I./Include -I. -I/usr/local/include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2 -c /sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/binascii.c -o build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/binascii.o -DUSE_ZLIB_CRC32
gcc -pthread -shared -fprofile-generate build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/binascii.o -L. -L/usr/local/lib -lz -lpython3.7m -o build/lib.linux-x86_64-3.7/binascii.cpython-37m-x86_64-linux-gnu.so
building '_bz2' extension
gcc -pthread -fPIC -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-generate -I./Include -I. -I/usr/local/include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2 -c /sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_bz2module.c -o build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_bz2module.o
gcc -pthread -shared -fprofile-generate build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_bz2module.o -L. -L/usr/local/lib -lbz2 -lpython3.7m -o build/lib.linux-x86_64-3.7/_bz2.cpython-37m-x86_64-linux-gnu.so
building '_lzma' extension
gcc -pthread -fPIC -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-generate -I./Include -I. -I/usr/local/include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2 -c /sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_lzmamodule.c -o build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_lzmamodule.o
gcc -pthread -shared -fprofile-generate build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_lzmamodule.o -L. -L/usr/local/lib -llzma -lpython3.7m -o build/lib.linux-x86_64-3.7/_lzma.cpython-37m-x86_64-linux-gnu.so
building 'pyexpat' extension
creating build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/expat
gcc -pthread -fPIC -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-generate -DHAVE_EXPAT_CONFIG_H=1 -DXML_POOR_ENTROPY=1 -DUSE_PYEXPAT_CAPI -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/expat -I./Include -I. -I/usr/local/include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2 -c /sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/pyexpat.c -o build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/pyexpat.o
gcc -pthread -fPIC -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-generate -DHAVE_EXPAT_CONFIG_H=1 -DXML_POOR_ENTROPY=1 -DUSE_PYEXPAT_CAPI -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/expat -I./Include -I. -I/usr/local/include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2 -c /sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/expat/xmlparse.c -o build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/expat/xmlparse.o
gcc -pthread -fPIC -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-generate -DHAVE_EXPAT_CONFIG_H=1 -DXML_POOR_ENTROPY=1 -DUSE_PYEXPAT_CAPI -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/expat -I./Include -I. -I/usr/local/include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2 -c /sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/expat/xmlrole.c -o build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/expat/xmlrole.o
gcc -pthread -fPIC -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-generate -DHAVE_EXPAT_CONFIG_H=1 -DXML_POOR_ENTROPY=1 -DUSE_PYEXPAT_CAPI -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/expat -I./Include -I. -I/usr/local/include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2 -c /sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/expat/xmltok.c -o build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/expat/xmltok.o
gcc -pthread -shared -fprofile-generate build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/pyexpat.o build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/expat/xmlparse.o build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/expat/xmlrole.o build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/expat/xmltok.o -L. -L/usr/local/lib -lpython3.7m -o build/lib.linux-x86_64-3.7/pyexpat.cpython-37m-x86_64-linux-gnu.so
building '_elementtree' extension
gcc -pthread -fPIC -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-generate -DHAVE_EXPAT_CONFIG_H=1 -DXML_POOR_ENTROPY=1 -DUSE_PYEXPAT_CAPI -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/expat -I./Include -I. -I/usr/local/include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2 -c /sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_elementtree.c -o build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_elementtree.o
gcc -pthread -shared -fprofile-generate build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_elementtree.o -L. -L/usr/local/lib -lpython3.7m -o build/lib.linux-x86_64-3.7/_elementtree.cpython-37m-x86_64-linux-gnu.so
building '_multibytecodec' extension
creating build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/cjkcodecs
gcc -pthread -fPIC -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-generate -I./Include -I. -I/usr/local/include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2 -c /sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/cjkcodecs/multibytecodec.c -o build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/cjkcodecs/multibytecodec.o
gcc -pthread -shared -fprofile-generate build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/cjkcodecs/multibytecodec.o -L. -L/usr/local/lib -lpython3.7m -o build/lib.linux-x86_64-3.7/_multibytecodec.cpython-37m-x86_64-linux-gnu.so
building '_codecs_kr' extension
gcc -pthread -fPIC -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-generate -I./Include -I. -I/usr/local/include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2 -c /sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/cjkcodecs/_codecs_kr.c -o build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/cjkcodecs/_codecs_kr.o
gcc -pthread -shared -fprofile-generate build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/cjkcodecs/_codecs_kr.o -L. -L/usr/local/lib -lpython3.7m -o build/lib.linux-x86_64-3.7/_codecs_kr.cpython-37m-x86_64-linux-gnu.so
building '_codecs_jp' extension
gcc -pthread -fPIC -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-generate -I./Include -I. -I/usr/local/include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2 -c /sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/cjkcodecs/_codecs_jp.c -o build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/cjkcodecs/_codecs_jp.o
gcc -pthread -shared -fprofile-generate build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/cjkcodecs/_codecs_jp.o -L. -L/usr/local/lib -lpython3.7m -o build/lib.linux-x86_64-3.7/_codecs_jp.cpython-37m-x86_64-linux-gnu.so
building '_codecs_cn' extension
gcc -pthread -fPIC -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-generate -I./Include -I. -I/usr/local/include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2 -c /sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/cjkcodecs/_codecs_cn.c -o build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/cjkcodecs/_codecs_cn.o
gcc -pthread -shared -fprofile-generate build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/cjkcodecs/_codecs_cn.o -L. -L/usr/local/lib -lpython3.7m -o build/lib.linux-x86_64-3.7/_codecs_cn.cpython-37m-x86_64-linux-gnu.so
building '_codecs_tw' extension
gcc -pthread -fPIC -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-generate -I./Include -I. -I/usr/local/include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2 -c /sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/cjkcodecs/_codecs_tw.c -o build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/cjkcodecs/_codecs_tw.o
gcc -pthread -shared -fprofile-generate build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/cjkcodecs/_codecs_tw.o -L. -L/usr/local/lib -lpython3.7m -o build/lib.linux-x86_64-3.7/_codecs_tw.cpython-37m-x86_64-linux-gnu.so
building '_codecs_hk' extension
gcc -pthread -fPIC -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-generate -I./Include -I. -I/usr/local/include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2 -c /sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/cjkcodecs/_codecs_hk.c -o build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/cjkcodecs/_codecs_hk.o
gcc -pthread -shared -fprofile-generate build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/cjkcodecs/_codecs_hk.o -L. -L/usr/local/lib -lpython3.7m -o build/lib.linux-x86_64-3.7/_codecs_hk.cpython-37m-x86_64-linux-gnu.so
building '_codecs_iso2022' extension
gcc -pthread -fPIC -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-generate -I./Include -I. -I/usr/local/include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2 -c /sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/cjkcodecs/_codecs_iso2022.c -o build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/cjkcodecs/_codecs_iso2022.o
gcc -pthread -shared -fprofile-generate build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/cjkcodecs/_codecs_iso2022.o -L. -L/usr/local/lib -lpython3.7m -o build/lib.linux-x86_64-3.7/_codecs_iso2022.cpython-37m-x86_64-linux-gnu.so
building '_decimal' extension
creating build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_decimal
creating build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_decimal/libmpdec
gcc -pthread -fPIC -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-generate -DCONFIG_64=1 -DASM=1 -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_decimal/libmpdec -I./Include -I. -I/usr/local/include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2 -c /sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_decimal/_decimal.c -o build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_decimal/_decimal.o
gcc -pthread -fPIC -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-generate -DCONFIG_64=1 -DASM=1 -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_decimal/libmpdec -I./Include -I. -I/usr/local/include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2 -c /sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_decimal/libmpdec/basearith.c -o build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_decimal/libmpdec/basearith.o
gcc -pthread -fPIC -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-generate -DCONFIG_64=1 -DASM=1 -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_decimal/libmpdec -I./Include -I. -I/usr/local/include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2 -c /sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_decimal/libmpdec/constants.c -o build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_decimal/libmpdec/constants.o
gcc -pthread -fPIC -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-generate -DCONFIG_64=1 -DASM=1 -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_decimal/libmpdec -I./Include -I. -I/usr/local/include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2 -c /sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_decimal/libmpdec/context.c -o build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_decimal/libmpdec/context.o
gcc -pthread -fPIC -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-generate -DCONFIG_64=1 -DASM=1 -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_decimal/libmpdec -I./Include -I. -I/usr/local/include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2 -c /sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_decimal/libmpdec/convolute.c -o build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_decimal/libmpdec/convolute.o
gcc -pthread -fPIC -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-generate -DCONFIG_64=1 -DASM=1 -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_decimal/libmpdec -I./Include -I. -I/usr/local/include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2 -c /sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_decimal/libmpdec/crt.c -o build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_decimal/libmpdec/crt.o
gcc -pthread -fPIC -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-generate -DCONFIG_64=1 -DASM=1 -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_decimal/libmpdec -I./Include -I. -I/usr/local/include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2 -c /sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_decimal/libmpdec/difradix2.c -o build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_decimal/libmpdec/difradix2.o
gcc -pthread -fPIC -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-generate -DCONFIG_64=1 -DASM=1 -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_decimal/libmpdec -I./Include -I. -I/usr/local/include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2 -c /sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_decimal/libmpdec/fnt.c -o build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_decimal/libmpdec/fnt.o
gcc -pthread -fPIC -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-generate -DCONFIG_64=1 -DASM=1 -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_decimal/libmpdec -I./Include -I. -I/usr/local/include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2 -c /sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_decimal/libmpdec/fourstep.c -o build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_decimal/libmpdec/fourstep.o
gcc -pthread -fPIC -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-generate -DCONFIG_64=1 -DASM=1 -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_decimal/libmpdec -I./Include -I. -I/usr/local/include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2 -c /sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_decimal/libmpdec/io.c -o build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_decimal/libmpdec/io.o
gcc -pthread -fPIC -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-generate -DCONFIG_64=1 -DASM=1 -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_decimal/libmpdec -I./Include -I. -I/usr/local/include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2 -c /sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_decimal/libmpdec/memory.c -o build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_decimal/libmpdec/memory.o
gcc -pthread -fPIC -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-generate -DCONFIG_64=1 -DASM=1 -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_decimal/libmpdec -I./Include -I. -I/usr/local/include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2 -c /sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_decimal/libmpdec/mpdecimal.c -o build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_decimal/libmpdec/mpdecimal.o
gcc -pthread -fPIC -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-generate -DCONFIG_64=1 -DASM=1 -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_decimal/libmpdec -I./Include -I. -I/usr/local/include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2 -c /sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_decimal/libmpdec/numbertheory.c -o build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_decimal/libmpdec/numbertheory.o
gcc -pthread -fPIC -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-generate -DCONFIG_64=1 -DASM=1 -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_decimal/libmpdec -I./Include -I. -I/usr/local/include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2 -c /sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_decimal/libmpdec/sixstep.c -o build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_decimal/libmpdec/sixstep.o
gcc -pthread -fPIC -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-generate -DCONFIG_64=1 -DASM=1 -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_decimal/libmpdec -I./Include -I. -I/usr/local/include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2 -c /sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_decimal/libmpdec/transpose.c -o build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_decimal/libmpdec/transpose.o
gcc -pthread -shared -fprofile-generate build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_decimal/_decimal.o build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_decimal/libmpdec/basearith.o build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_decimal/libmpdec/constants.o build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_decimal/libmpdec/context.o build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_decimal/libmpdec/convolute.o build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_decimal/libmpdec/crt.o build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_decimal/libmpdec/difradix2.o build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_decimal/libmpdec/fnt.o build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_decimal/libmpdec/fourstep.o build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_decimal/libmpdec/io.o build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_decimal/libmpdec/memory.o build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_decimal/libmpdec/mpdecimal.o build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_decimal/libmpdec/numbertheory.o build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_decimal/libmpdec/sixstep.o build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_decimal/libmpdec/transpose.o -L. -L/usr/local/lib -lm -lpython3.7m -o build/lib.linux-x86_64-3.7/_decimal.cpython-37m-x86_64-linux-gnu.so
building '_multiprocessing' extension
creating build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_multiprocessing
gcc -pthread -fPIC -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-generate -IModules/_multiprocessing -I./Include -I. -I/usr/local/include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2 -c /sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_multiprocessing/multiprocessing.c -o build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_multiprocessing/multiprocessing.o
gcc -pthread -fPIC -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-generate -IModules/_multiprocessing -I./Include -I. -I/usr/local/include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2 -c /sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_multiprocessing/semaphore.c -o build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_multiprocessing/semaphore.o
gcc -pthread -shared -fprofile-generate build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_multiprocessing/multiprocessing.o build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_multiprocessing/semaphore.o -L. -L/usr/local/lib -lpython3.7m -o build/lib.linux-x86_64-3.7/_multiprocessing.cpython-37m-x86_64-linux-gnu.so
building 'ossaudiodev' extension
gcc -pthread -fPIC -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-generate -I./Include -I. -I/usr/local/include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2 -c /sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/ossaudiodev.c -o build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/ossaudiodev.o
gcc -pthread -shared -fprofile-generate build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/ossaudiodev.o -L. -L/usr/local/lib -lpython3.7m -o build/lib.linux-x86_64-3.7/ossaudiodev.cpython-37m-x86_64-linux-gnu.so
building '_tkinter' extension
gcc -pthread -fPIC -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-generate -DWITH_APPINIT=1 -I/usr/X11/include -I./Include -I. -I/usr/local/include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2 -c /sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_tkinter.c -o build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_tkinter.o
gcc -pthread -fPIC -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-generate -DWITH_APPINIT=1 -I/usr/X11/include -I./Include -I. -I/usr/local/include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2 -c /sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/tkappinit.c -o build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/tkappinit.o
gcc -pthread -shared -fprofile-generate build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_tkinter.o build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/tkappinit.o -L/usr/X11/lib -L. -L/usr/local/lib -ltk8.5 -ltcl8.5 -lX11 -lpython3.7m -o build/lib.linux-x86_64-3.7/_tkinter.cpython-37m-x86_64-linux-gnu.so
building '_uuid' extension
gcc -pthread -fPIC -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-generate -I/usr/include/uuid -I./Include -I. -I/usr/local/include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2 -c /sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_uuidmodule.c -o build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_uuidmodule.o
gcc -pthread -shared -fprofile-generate build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_uuidmodule.o -L. -L/usr/local/lib -luuid -lpython3.7m -o build/lib.linux-x86_64-3.7/_uuid.cpython-37m-x86_64-linux-gnu.so
building 'xxlimited' extension
gcc -pthread -fPIC -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-generate -DPy_LIMITED_API=0x03050000 -I./Include -I. -I/usr/local/include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2 -c /sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/xxlimited.c -o build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/xxlimited.o
gcc -pthread -shared -fprofile-generate build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/xxlimited.o -L. -L/usr/local/lib -lpython3.7m -o build/lib.linux-x86_64-3.7/xxlimited.cpython-37m-x86_64-linux-gnu.so
building '_ctypes' extension
gcc -pthread -fPIC -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-generate -I/usr/lib64/libffi-3.0.5/include -I./Include -I. -I/usr/local/include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2 -c /sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_ctypes/_ctypes.c -o build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_ctypes/_ctypes.o
gcc -pthread -fPIC -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-generate -I/usr/lib64/libffi-3.0.5/include -I./Include -I. -I/usr/local/include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2 -c /sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_ctypes/callbacks.c -o build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_ctypes/callbacks.o
gcc -pthread -fPIC -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-generate -I/usr/lib64/libffi-3.0.5/include -I./Include -I. -I/usr/local/include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2 -c /sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_ctypes/callproc.c -o build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_ctypes/callproc.o
gcc -pthread -fPIC -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-generate -I/usr/lib64/libffi-3.0.5/include -I./Include -I. -I/usr/local/include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2 -c /sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_ctypes/stgdict.c -o build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_ctypes/stgdict.o
gcc -pthread -fPIC -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-generate -I/usr/lib64/libffi-3.0.5/include -I./Include -I. -I/usr/local/include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2 -c /sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_ctypes/cfield.c -o build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_ctypes/cfield.o
gcc -pthread -shared -fprofile-generate build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_ctypes/_ctypes.o build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_ctypes/callbacks.o build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_ctypes/callproc.o build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_ctypes/stgdict.o build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_ctypes/cfield.o -L. -L/usr/local/lib -lffi -ldl -lpython3.7m -o build/lib.linux-x86_64-3.7/_ctypes.cpython-37m-x86_64-linux-gnu.so

Python build finished successfully!
The necessary bits to build these optional modules were not found:
_ssl                                                           
To find the necessary bits, look in setup.py in detect_modules() for the module's name.


The following modules found by detect_modules() in setup.py, have been
built by the Makefile instead, as configured by the Setup files:
_abc                  atexit                pwd                
time                                                           


Could not build the ssl module!
Python requires an OpenSSL 1.0.2 or 1.1 compatible libssl with X509_VERIFY_PARAM_set1_host().
LibreSSL 2.6.4 and earlier do not provide the necessary APIs, https://github.com/libressl-portable/portable/issues/381

running build_scripts
creating build/scripts-3.7
copying and adjusting /sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Tools/scripts/pydoc3 -> build/scripts-3.7
copying and adjusting /sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Tools/scripts/idle3 -> build/scripts-3.7
copying and adjusting /sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Tools/scripts/2to3 -> build/scripts-3.7
copying and adjusting /sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Tools/scripts/pyvenv -> build/scripts-3.7
changing mode of build/scripts-3.7/pydoc3 from 644 to 755
changing mode of build/scripts-3.7/idle3 from 644 to 755
changing mode of build/scripts-3.7/2to3 from 644 to 755
changing mode of build/scripts-3.7/pyvenv from 644 to 755
renaming build/scripts-3.7/pydoc3 to build/scripts-3.7/pydoc3.7
renaming build/scripts-3.7/idle3 to build/scripts-3.7/idle3.7
renaming build/scripts-3.7/2to3 to build/scripts-3.7/2to3-3.7
renaming build/scripts-3.7/pyvenv to build/scripts-3.7/pyvenv-3.7
make[3]: Leaving directory `/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2'
make[2]: Leaving directory `/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2'
touch profile-gen-stamp
make[1]: Leaving directory `/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2'
# Next, run the profile task to generate the profile information.
make run_profile_task
make[1]: Entering directory `/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2'
LD_LIBRARY_PATH=/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2:/hpc/packages/minerva-common/gcc/4.8.2/lib64:/hpc/packages/minerva-common/gcc/4.8.2/lib:/hpc/packages/minerva-common/mpc/1.0.2/lib:/hpc/packages/minerva-common/mpc/1.0.2/lib64:/hpc/packages/minerva-common/mpfr/3.1.2/lib:/hpc/packages/minerva-common/gmp/5.1.3/lib64:/hpc/packages/minerva-common/gmp/5.1.3/lib:/hpc/lsf/9.1/linux2.6-glibc2.3-x86_64/lib ./python -m test.regrtest --pgo || true
Run tests sequentially
0:00:00 load avg: 1.73 [  1/416] test_grammar
0:00:00 load avg: 1.73 [  2/416] test_opcodes
0:00:00 load avg: 1.73 [  3/416] test_dict
0:00:00 load avg: 1.73 [  4/416] test_builtin
0:00:01 load avg: 1.67 [  5/416] test_exceptions
0:00:02 load avg: 1.67 [  6/416] test_types
0:00:02 load avg: 1.67 [  7/416] test_unittest -- test_types failed (env changed)
0:00:06 load avg: 1.70 [  8/416] test_doctest
0:00:08 load avg: 1.70 [  9/416] test_doctest2
0:00:08 load avg: 1.70 [ 10/416] test_support
0:00:15 load avg: 1.80 [ 11/416] test___all__
0:00:29 load avg: 1.70 [ 12/416] test___future__
0:00:29 load avg: 1.70 [ 13/416] test__locale
0:00:29 load avg: 1.70 [ 14/416] test__opcode
0:00:29 load avg: 1.70 [ 15/416] test__osx_support
0:00:30 load avg: 1.70 [ 16/416] test_abc
0:00:30 load avg: 1.70 [ 17/416] test_abstract_numbers
0:00:30 load avg: 1.70 [ 18/416] test_aifc
0:00:30 load avg: 1.70 [ 19/416] test_argparse
0:00:36 load avg: 1.59 [ 20/416] test_array
0:00:38 load avg: 1.59 [ 21/416] test_asdl_parser
0:00:38 load avg: 1.59 [ 22/416] test_ast
0:00:41 load avg: 1.54 [ 23/416] test_asyncgen
0:00:42 load avg: 1.54 [ 24/416] test_asynchat
0:00:43 load avg: 1.54 [ 25/416] test_asyncio
0:01:52 load avg: 1.36 [ 26/416] test_asyncore -- test_asyncio passed in 1 min 9 sec
0:01:52 load avg: 1.36 [ 27/416] test_atexit -- test_asyncore skipped
0:01:53 load avg: 1.36 [ 28/416] test_audioop
0:01:53 load avg: 1.36 [ 29/416] test_augassign
0:01:53 load avg: 1.36 [ 30/416] test_base64
0:01:54 load avg: 1.36 [ 31/416] test_baseexception
0:01:54 load avg: 1.36 [ 32/416] test_bdb
0:01:54 load avg: 1.36 [ 33/416] test_bigaddrspace
0:01:54 load avg: 1.36 [ 34/416] test_bigmem
0:01:54 load avg: 1.36 [ 35/416] test_binascii
0:01:54 load avg: 1.36 [ 36/416] test_binhex
0:01:54 load avg: 1.36 [ 37/416] test_binop
0:01:54 load avg: 1.36 [ 38/416] test_bisect
0:01:55 load avg: 1.36 [ 39/416] test_bool
0:01:55 load avg: 1.36 [ 40/416] test_buffer
0:02:15 load avg: 1.26 [ 41/416] test_bufio
0:02:17 load avg: 1.24 [ 42/416] test_bytes
0:02:21 load avg: 1.22 [ 43/416] test_bz2
0:02:25 load avg: 1.22 [ 44/416] test_c_locale_coercion
0:02:29 load avg: 1.28 [ 45/416] test_calendar
0:02:32 load avg: 1.26 [ 46/416] test_call -- test_calendar failed (env changed)
0:02:33 load avg: 1.26 [ 47/416] test_capi
0:02:36 load avg: 1.16 [ 48/416] test_cgi
0:02:36 load avg: 1.16 [ 49/416] test_cgitb
0:02:37 load avg: 1.16 [ 50/416] test_charmapcodec
0:02:37 load avg: 1.16 [ 51/416] test_class
0:02:37 load avg: 1.16 [ 52/416] test_clinic
0:02:37 load avg: 1.16 [ 53/416] test_cmath
0:02:38 load avg: 1.16 [ 54/416] test_cmd
0:02:38 load avg: 1.16 [ 55/416] test_cmd_line
0:02:43 load avg: 1.22 [ 56/416] test_cmd_line_script
0:02:48 load avg: 1.37 [ 57/416] test_code
0:02:48 load avg: 1.37 [ 58/416] test_code_module
0:02:48 load avg: 1.37 [ 59/416] test_codeccallbacks
0:02:48 load avg: 1.37 [ 60/416] test_codecencodings_cn
0:02:49 load avg: 1.37 [ 61/416] test_codecencodings_hk
0:02:49 load avg: 1.37 [ 62/416] test_codecencodings_iso2022
0:02:50 load avg: 1.37 [ 63/416] test_codecencodings_jp
0:02:51 load avg: 1.34 [ 64/416] test_codecencodings_kr
0:02:52 load avg: 1.34 [ 65/416] test_codecencodings_tw
0:02:52 load avg: 1.34 [ 66/416] test_codecmaps_cn
0:02:52 load avg: 1.34 [ 67/416] test_codecmaps_hk
0:02:52 load avg: 1.34 [ 68/416] test_codecmaps_jp
0:02:52 load avg: 1.34 [ 69/416] test_codecmaps_kr
0:02:52 load avg: 1.34 [ 70/416] test_codecmaps_tw
0:02:52 load avg: 1.34 [ 71/416] test_codecs
0:02:55 load avg: 1.31 [ 72/416] test_codeop
0:02:56 load avg: 1.31 [ 73/416] test_collections
0:02:57 load avg: 1.31 [ 74/416] test_colorsys
0:02:57 load avg: 1.31 [ 75/416] test_compare
0:02:57 load avg: 1.31 [ 76/416] test_compile
0:02:59 load avg: 1.31 [ 77/416] test_compileall
0:03:10 load avg: 1.34 [ 78/416] test_complex
0:03:10 load avg: 1.34 [ 79/416] test_concurrent_futures
0:05:34 load avg: 1.06 [ 80/416] test_configparser -- test_concurrent_futures passed in 2 min 24 sec
0:05:35 load avg: 1.06 [ 81/416] test_contains
0:05:35 load avg: 1.05 [ 82/416] test_context
0:05:39 load avg: 1.05 [ 83/416] test_contextlib
0:05:39 load avg: 1.05 [ 84/416] test_contextlib_async
Task was destroyed but it is pending!
task: <Task pending coro=<<async_generator_athrow without __name__>()>>
Task was destroyed but it is pending!
task: <Task pending coro=<<async_generator_athrow without __name__>()>>
0:05:39 load avg: 1.05 [ 85/416] test_copy
0:05:39 load avg: 1.05 [ 86/416] test_copyreg
0:05:40 load avg: 1.05 [ 87/416] test_coroutines
0:05:41 load avg: 1.05 [ 88/416] test_cprofile
0:05:42 load avg: 1.05 [ 89/416] test_crashers
0:05:42 load avg: 1.05 [ 90/416] test_crypt
0:05:42 load avg: 1.05 [ 91/416] test_csv
0:05:42 load avg: 1.05 [ 92/416] test_ctypes
0:05:44 load avg: 1.05 [ 93/416] test_curses
0:05:45 load avg: 1.05 [ 94/416] test_dataclasses -- test_curses skipped (resource denied)
0:05:45 load avg: 1.05 [ 95/416] test_datetime
0:05:55 load avg: 1.04 [ 96/416] test_dbm
0:05:59 load avg: 1.12 [ 97/416] test_dbm_dumb
0:06:00 load avg: 1.12 [ 98/416] test_dbm_gnu
0:06:01 load avg: 1.19 [ 99/416] test_dbm_ndbm
0:06:02 load avg: 1.19 [100/416] test_decimal
0:06:13 load avg: 1.31 [101/416] test_decorators
0:06:13 load avg: 1.31 [102/416] test_defaultdict
0:06:14 load avg: 1.31 [103/416] test_deque
0:06:19 load avg: 1.29 [104/416] test_descr
0:06:22 load avg: 1.26 [105/416] test_descrtut
0:06:22 load avg: 1.26 [106/416] test_devpoll
0:06:22 load avg: 1.26 [107/416] test_dict_version -- test_devpoll skipped
0:06:22 load avg: 1.26 [108/416] test_dictcomps
0:06:22 load avg: 1.26 [109/416] test_dictviews
0:06:23 load avg: 1.26 [110/416] test_difflib
0:06:25 load avg: 1.26 [111/416] test_dis
0:06:26 load avg: 1.24 [112/416] test_distutils
0:06:30 load avg: 1.24 [113/416] test_docxmlrpc
0:06:33 load avg: 1.22 [114/416] test_dtrace
0:06:33 load avg: 1.22 [115/416] test_dummy_thread -- test_dtrace run no tests
0:06:33 load avg: 1.22 [116/416] test_dummy_threading
0:06:33 load avg: 1.22 [117/416] test_dynamic
0:06:33 load avg: 1.22 [118/416] test_dynamicclassattribute
0:06:34 load avg: 1.22 [119/416] test_eintr
0:06:41 load avg: 1.27 [120/416] test_email
0:06:49 load avg: 1.33 [121/416] test_embed
0:06:54 load avg: 1.38 [122/416] test_ensurepip
0:06:55 load avg: 1.38 [123/416] test_enum
0:06:56 load avg: 1.59 [124/416] test_enumerate
0:06:56 load avg: 1.59 [125/416] test_eof
0:06:56 load avg: 1.59 [126/416] test_epoll
0:06:59 load avg: 1.59 [127/416] test_errno
0:06:59 load avg: 1.59 [128/416] test_exception_hierarchy
0:06:59 load avg: 1.59 [129/416] test_exception_variations
0:06:59 load avg: 1.59 [130/416] test_extcall
0:06:59 load avg: 1.59 [131/416] test_faulthandler
0:07:19 load avg: 1.72 [132/416] test_fcntl
0:07:19 load avg: 1.72 [133/416] test_file
0:07:20 load avg: 1.72 [134/416] test_file_eintr
0:07:22 load avg: 1.91 [135/416] test_filecmp
0:07:23 load avg: 1.91 [136/416] test_fileinput
0:07:23 load avg: 1.91 [137/416] test_fileio
0:07:23 load avg: 1.91 [138/416] test_finalization
0:07:27 load avg: 1.91 [139/416] test_float
0:07:27 load avg: 1.91 [140/416] test_flufl -- test_float failed (env changed)
0:07:28 load avg: 1.91 [141/416] test_fnmatch
0:07:28 load avg: 1.91 [142/416] test_fork1
0:07:35 load avg: 2.00 [143/416] test_format
0:07:35 load avg: 2.00 [144/416] test_fractions
0:07:35 load avg: 2.00 [145/416] test_frame
0:07:36 load avg: 2.00 [146/416] test_frozen
0:07:36 load avg: 2.00 [147/416] test_fstring
0:07:37 load avg: 2.00 [148/416] test_ftplib
0:07:39 load avg: 2.00 [149/416] test_funcattrs
0:07:39 load avg: 2.00 [150/416] test_functools
0:07:40 load avg: 2.00 [151/416] test_future
0:07:40 load avg: 2.00 [152/416] test_future3
0:07:40 load avg: 2.00 [153/416] test_future4
0:07:40 load avg: 2.00 [154/416] test_future5 -- test_future4 run no tests
0:07:41 load avg: 2.08 [155/416] test_gc
0:07:47 load avg: 2.23 [156/416] test_gdb
0:07:48 load avg: 2.23 [157/416] test_generator_stop -- test_gdb skipped
0:07:48 load avg: 2.23 [158/416] test_generators
0:07:49 load avg: 2.23 [159/416] test_genericclass
0:07:49 load avg: 2.23 [160/416] test_genericpath
0:07:49 load avg: 2.23 [161/416] test_genexps
0:07:49 load avg: 2.23 [162/416] test_getargs2
0:07:50 load avg: 2.23 [163/416] test_getopt
0:07:50 load avg: 2.23 [164/416] test_getpass
0:07:50 load avg: 2.23 [165/416] test_gettext
0:07:51 load avg: 2.21 [166/416] test_glob
0:07:51 load avg: 2.21 [167/416] test_global
0:07:51 load avg: 2.21 [168/416] test_grp
0:07:53 load avg: 2.21 [169/416] test_gzip
0:07:54 load avg: 2.21 [170/416] test_hash
0:07:56 load avg: 2.44 [171/416] test_hashlib
0:07:57 load avg: 2.44 [172/416] test_heapq
0:07:58 load avg: 2.44 [173/416] test_hmac
0:07:59 load avg: 2.44 [174/416] test_html
0:07:59 load avg: 2.44 [175/416] test_htmlparser
0:07:59 load avg: 2.44 [176/416] test_http_cookiejar
0:08:00 load avg: 2.44 [177/416] test_http_cookies
0:08:00 load avg: 2.44 [178/416] test_httplib
0:08:00 load avg: 2.44 [179/416] test_httpservers
0:08:03 load avg: 2.40 [180/416] test_idle
0:08:04 load avg: 2.40 [181/416] test_imaplib
0:08:07 load avg: 2.53 [182/416] test_imghdr
0:08:07 load avg: 2.53 [183/416] test_imp
0:08:08 load avg: 2.53 [184/416] test_import
0:08:09 load avg: 2.53 [185/416] test_importlib
0:08:14 load avg: 2.73 [186/416] test_index
0:08:15 load avg: 2.73 [187/416] test_inspect
0:08:16 load avg: 2.67 [188/416] test_int
0:08:17 load avg: 2.67 [189/416] test_int_literal
0:08:17 load avg: 2.67 [190/416] test_io
0:09:09 load avg: 2.18 [191/416] test_ioctl -- test_io passed in 52 sec 347 ms
0:09:10 load avg: 2.18 [192/416] test_ipaddress
0:09:10 load avg: 2.18 [193/416] test_isinstance
0:09:10 load avg: 2.16 [194/416] test_iter
0:09:11 load avg: 2.16 [195/416] test_iterlen
0:09:11 load avg: 2.16 [196/416] test_itertools
0:09:21 load avg: 2.22 [197/416] test_json
0:09:26 load avg: 2.28 [198/416] test_keyword
0:09:27 load avg: 2.28 [199/416] test_keywordonlyarg
0:09:27 load avg: 2.28 [200/416] test_kqueue
0:09:27 load avg: 2.28 [201/416] test_largefile -- test_kqueue skipped
0:09:28 load avg: 2.28 [202/416] test_lib2to3
0:09:56 load avg: 2.55 [203/416] test_linecache
0:09:57 load avg: 2.55 [204/416] test_list
0:09:58 load avg: 2.55 [205/416] test_listcomps
0:09:58 load avg: 2.55 [206/416] test_locale
0:09:59 load avg: 2.55 [207/416] test_logging -- test_locale failed (env changed)
0:10:20 load avg: 2.34 [208/416] test_long
0:10:27 load avg: 2.22 [209/416] test_longexp
0:10:27 load avg: 2.22 [210/416] test_lzma
0:10:31 load avg: 2.20 [211/416] test_macpath
0:10:32 load avg: 2.20 [212/416] test_mailbox
0:10:34 load avg: 2.20 [213/416] test_mailcap
0:10:35 load avg: 2.20 [214/416] test_marshal
0:10:36 load avg: 2.26 [215/416] test_math
0:10:41 load avg: 2.32 [216/416] test_memoryio
0:10:42 load avg: 2.32 [217/416] test_memoryview
0:10:45 load avg: 2.32 [218/416] test_metaclass
0:10:45 load avg: 2.32 [219/416] test_mimetypes
0:10:46 load avg: 2.54 [220/416] test_minidom
0:10:46 load avg: 2.54 [221/416] test_mmap
0:10:47 load avg: 2.54 [222/416] test_module
0:10:48 load avg: 2.54 [223/416] test_modulefinder
0:10:49 load avg: 2.54 [224/416] test_msilib
0:10:49 load avg: 2.54 [225/416] test_multibytecodec -- test_msilib skipped
0:10:53 load avg: 2.73 [226/416] test_multiprocessing_fork
0:10:54 load avg: 2.73 [227/416] test_multiprocessing_forkserver -- test_multiprocessing_fork skipped
0:10:54 load avg: 2.73 [228/416] test_multiprocessing_main_handling -- test_multiprocessing_forkserver skipped
0:10:55 load avg: 2.73 [229/416] test_multiprocessing_spawn -- test_multiprocessing_main_handling skipped
0:10:55 load avg: 2.73 [230/416] test_netrc -- test_multiprocessing_spawn skipped
0:10:55 load avg: 2.73 [231/416] test_nis
0:10:56 load avg: 2.67 [232/416] test_nntplib
0:10:56 load avg: 2.67 [233/416] test_normalization
0:10:57 load avg: 2.67 [234/416] test_ntpath
0:10:57 load avg: 2.67 [235/416] test_numeric_tower
0:10:58 load avg: 2.67 [236/416] test_openpty
0:10:58 load avg: 2.67 [237/416] test_operator
0:10:59 load avg: 2.67 [238/416] test_optparse
0:10:59 load avg: 2.67 [239/416] test_ordered_dict
0:11:06 load avg: 2.73 [240/416] test_os
0:11:10 load avg: 2.73 [241/416] test_ossaudiodev
0:11:10 load avg: 2.73 [242/416] test_osx_env -- test_ossaudiodev skipped (resource denied)
0:11:11 load avg: 2.67 [243/416] test_parser
0:11:11 load avg: 2.67 [244/416] test_pathlib
0:11:13 load avg: 2.67 [245/416] test_pdb -- test_pathlib failed
0:11:15 load avg: 2.67 [246/416] test_peepholer
0:11:15 load avg: 2.67 [247/416] test_pickle
0:11:36 load avg: 2.44 [248/416] test_pickletools
0:11:40 load avg: 2.44 [249/416] test_pipes
0:11:40 load avg: 2.44 [250/416] test_pkg
0:11:41 load avg: 2.41 [251/416] test_pkgimport
0:11:41 load avg: 2.41 [252/416] test_pkgutil
0:11:42 load avg: 2.41 [253/416] test_platform
0:11:42 load avg: 2.41 [254/416] test_plistlib
0:11:43 load avg: 2.41 [255/416] test_poll
0:11:54 load avg: 2.19 [256/416] test_popen
0:11:55 load avg: 2.19 [257/416] test_poplib
0:11:56 load avg: 2.17 [258/416] test_posix
0:11:57 load avg: 2.17 [259/416] test_posixpath
0:11:57 load avg: 2.17 [260/416] test_pow
0:11:58 load avg: 2.17 [261/416] test_pprint
0:11:59 load avg: 2.17 [262/416] test_print
0:11:59 load avg: 2.17 [263/416] test_profile
0:11:59 load avg: 2.17 [264/416] test_property
0:12:00 load avg: 2.17 [265/416] test_pstats
0:12:00 load avg: 2.17 [266/416] test_pty
0:12:01 load avg: 2.24 [267/416] test_pulldom
0:12:01 load avg: 2.24 [268/416] test_pwd
0:12:02 load avg: 2.24 [269/416] test_py_compile
0:12:03 load avg: 2.24 [270/416] test_pyclbr
0:12:07 load avg: 2.22 [271/416] test_pydoc
0:12:12 load avg: 2.12 [272/416] test_pyexpat
0:12:12 load avg: 2.12 [273/416] test_queue
0:12:18 load avg: 2.03 [274/416] test_quopri
0:12:18 load avg: 2.03 [275/416] test_raise
0:12:19 load avg: 2.03 [276/416] test_random
0:12:22 load avg: 2.11 [277/416] test_range
0:12:23 load avg: 2.11 [278/416] test_re
0:12:26 load avg: 2.10 [279/416] test_readline
0:12:27 load avg: 2.10 [280/416] test_regrtest
0:12:41 load avg: 2.23 [281/416] test_repl
0:12:41 load avg: 2.23 [282/416] test_reprlib
0:12:42 load avg: 2.23 [283/416] test_resource
0:12:42 load avg: 2.23 [284/416] test_richcmp
0:12:43 load avg: 2.23 [285/416] test_rlcompleter
0:12:43 load avg: 2.23 [286/416] test_robotparser
0:12:44 load avg: 2.23 [287/416] test_runpy
0:12:46 load avg: 2.21 [288/416] test_sax
0:12:46 load avg: 2.21 [289/416] test_sched
0:12:47 load avg: 2.21 [290/416] test_scope
0:12:48 load avg: 2.21 [291/416] test_script_helper
0:12:48 load avg: 2.21 [292/416] test_secrets
0:12:49 load avg: 2.21 [293/416] test_select
0:13:00 load avg: 2.03 [294/416] test_selectors
0:13:16 load avg: 2.15 [295/416] test_set
0:13:20 load avg: 2.15 [296/416] test_setcomps
0:13:21 load avg: 2.30 [297/416] test_shelve
0:13:22 load avg: 2.30 [298/416] test_shlex
0:13:22 load avg: 2.30 [299/416] test_shutil
0:13:23 load avg: 2.30 [300/416] test_signal
0:13:47 load avg: 1.91 [301/416] test_site
0:13:48 load avg: 1.91 [302/416] test_slice
0:13:49 load avg: 1.91 [303/416] test_smtpd
0:13:49 load avg: 1.91 [304/416] test_smtplib
0:13:51 load avg: 1.84 [305/416] test_smtpnet
0:13:51 load avg: 1.84 [306/416] test_sndhdr -- test_smtpnet skipped
0:13:52 load avg: 1.84 [307/416] test_socket
0:14:18 load avg: 1.89 [308/416] test_socketserver
0:14:19 load avg: 1.89 [309/416] test_sort -- test_socketserver skipped (resource denied)
0:14:19 load avg: 1.89 [310/416] test_source_encoding
0:14:21 load avg: 1.90 [311/416] test_spwd
0:14:21 load avg: 1.90 [312/416] test_sqlite
0:14:22 load avg: 1.90 [313/416] test_ssl -- test_sqlite failed
0:14:23 load avg: 1.90 [314/416] test_startfile -- test_ssl skipped
0:14:23 load avg: 1.90 [315/416] test_stat -- test_startfile skipped
0:14:24 load avg: 1.90 [316/416] test_statistics
0:14:26 load avg: 1.91 [317/416] test_strftime
0:14:27 load avg: 1.91 [318/416] test_string
0:14:27 load avg: 1.91 [319/416] test_string_literals
0:14:29 load avg: 1.91 [320/416] test_stringprep
0:14:29 load avg: 1.91 [321/416] test_strptime
0:14:30 load avg: 1.91 [322/416] test_strtod -- test_strptime failed (env changed)
0:14:32 load avg: 2.08 [323/416] test_struct
0:14:34 load avg: 2.08 [324/416] test_structmembers
0:14:34 load avg: 2.08 [325/416] test_structseq
0:14:35 load avg: 2.08 [326/416] test_subclassinit
0:14:35 load avg: 2.08 [327/416] test_subprocess
0:14:36 load avg: 2.07 [328/416] test_sunau -- test_subprocess skipped
0:14:36 load avg: 2.07 [329/416] test_sundry
0:14:37 load avg: 2.07 [330/416] test_super
0:14:37 load avg: 2.07 [331/416] test_symbol
0:14:38 load avg: 2.07 [332/416] test_symtable
0:14:39 load avg: 2.07 [333/416] test_syntax
0:14:39 load avg: 2.07 [334/416] test_sys
0:14:42 load avg: 2.06 [335/416] test_sys_setprofile
0:14:42 load avg: 2.06 [336/416] test_sys_settrace
unhandled exception during asyncio.run() shutdown
task: <Task finished coro=<<async_generator_athrow without __name__>()> exception=RuntimeError("can't send non-None value to a just-started coroutine")>
RuntimeError: can't send non-None value to a just-started coroutine
unhandled exception during asyncio.run() shutdown
task: <Task finished coro=<<async_generator_athrow without __name__>()> exception=RuntimeError("can't send non-None value to a just-started coroutine")>
RuntimeError: can't send non-None value to a just-started coroutine
0:14:43 load avg: 2.06 [337/416] test_sysconfig
0:14:44 load avg: 2.06 [338/416] test_syslog
0:14:44 load avg: 2.06 [339/416] test_tarfile
0:14:59 load avg: 2.13 [340/416] test_tcl
0:15:00 load avg: 2.13 [341/416] test_telnetlib
0:15:00 load avg: 2.13 [342/416] test_tempfile
0:15:03 load avg: 2.12 [343/416] test_textwrap
0:15:03 load avg: 2.12 [344/416] test_thread
0:15:05 load avg: 2.12 [345/416] test_threaded_import
0:15:06 load avg: 2.03 [346/416] test_threadedtempfile
0:15:07 load avg: 2.03 [347/416] test_threading
0:15:18 load avg: 1.94 [348/416] test_threading_local
0:15:20 load avg: 1.94 [349/416] test_threadsignals
0:15:26 load avg: 1.95 [350/416] test_time
0:15:28 load avg: 1.95 [351/416] test_timeit
0:15:29 load avg: 1.95 [352/416] test_timeout
0:15:29 load avg: 1.95 [353/416] test_tix -- test_timeout skipped (resource denied)
0:15:30 load avg: 1.95 [354/416] test_tk -- test_tix skipped (resource denied)
0:15:30 load avg: 1.95 [355/416] test_tokenize -- test_tk skipped (resource denied)
0:15:33 load avg: 1.96 [356/416] test_tools
0:15:41 load avg: 1.96 [357/416] test_trace
0:15:52 load avg: 1.97 [358/416] test_traceback
0:15:54 load avg: 1.97 [359/416] test_tracemalloc
0:15:56 load avg: 2.05 [360/416] test_ttk_guionly
0:15:56 load avg: 2.05 [361/416] test_ttk_textonly -- test_ttk_guionly skipped (resource denied)
0:15:57 load avg: 2.05 [362/416] test_tuple
0:16:14 load avg: 2.17 [363/416] test_turtle
0:16:14 load avg: 2.17 [364/416] test_typechecks
0:16:14 load avg: 2.17 [365/416] test_typing
0:16:15 load avg: 2.17 [366/416] test_ucn
0:16:16 load avg: 2.24 [367/416] test_unary
0:16:16 load avg: 2.24 [368/416] test_unicode
0:16:20 load avg: 2.24 [369/416] test_unicode_file
0:16:20 load avg: 2.24 [370/416] test_unicode_file_functions
0:16:21 load avg: 2.30 [371/416] test_unicode_identifiers
0:16:21 load avg: 2.30 [372/416] test_unicodedata
0:16:28 load avg: 2.36 [373/416] test_univnewlines
0:16:29 load avg: 2.36 [374/416] test_unpack
0:16:29 load avg: 2.36 [375/416] test_unpack_ex
0:16:30 load avg: 2.36 [376/416] test_urllib
0:16:30 load avg: 2.36 [377/416] test_urllib2
0:16:31 load avg: 2.33 [378/416] test_urllib2_localnet
0:16:32 load avg: 2.33 [379/416] test_urllib2net
0:16:33 load avg: 2.33 [380/416] test_urllib_response -- test_urllib2net skipped (resource denied)
0:16:33 load avg: 2.33 [381/416] test_urllibnet
0:16:33 load avg: 2.33 [382/416] test_urlparse -- test_urllibnet skipped (resource denied)
0:16:34 load avg: 2.33 [383/416] test_userdict
0:16:35 load avg: 2.33 [384/416] test_userlist
0:16:35 load avg: 2.30 [385/416] test_userstring
0:16:39 load avg: 2.30 [386/416] test_utf8_mode
0:16:41 load avg: 2.36 [387/416] test_utf8source
0:16:41 load avg: 2.36 [388/416] test_uu
0:16:42 load avg: 2.36 [389/416] test_uuid
0:16:43 load avg: 2.36 [390/416] test_venv
0:16:57 load avg: 2.28 [391/416] test_wait3
0:17:03 load avg: 2.17 [392/416] test_wait4
0:17:08 load avg: 2.08 [393/416] test_warnings
0:17:10 load avg: 2.08 [394/416] test_wave
0:17:11 load avg: 2.15 [395/416] test_weakref
0:17:55 load avg: 2.21 [396/416] test_weakset -- test_weakref passed in 44 sec 461 ms
0:17:57 load avg: 2.27 [397/416] test_webbrowser
0:17:58 load avg: 2.27 [398/416] test_winconsoleio
0:17:58 load avg: 2.27 [399/416] test_winreg -- test_winconsoleio skipped
0:17:58 load avg: 2.27 [400/416] test_winsound -- test_winreg skipped
0:17:59 load avg: 2.27 [401/416] test_with -- test_winsound skipped (resource denied)
0:17:59 load avg: 2.27 [402/416] test_wsgiref
0:18:00 load avg: 2.27 [403/416] test_xdrlib
0:18:00 load avg: 2.27 [404/416] test_xml_dom_minicompat
0:18:01 load avg: 2.33 [405/416] test_xml_etree
0:18:03 load avg: 2.33 [406/416] test_xml_etree_c
0:18:07 load avg: 2.30 [407/416] test_xmlrpc
0:18:11 load avg: 2.28 [408/416] test_xmlrpc_net
0:18:11 load avg: 2.28 [409/416] test_xxtestfuzz -- test_xmlrpc_net skipped (resource denied)
0:18:11 load avg: 2.28 [410/416] test_yield_from
0:18:12 load avg: 2.28 [411/416] test_zipapp
0:18:13 load avg: 2.28 [412/416] test_zipfile
0:18:27 load avg: 2.22 [413/416] test_zipfile64
0:18:28 load avg: 2.22 [414/416] test_zipimport -- test_zipfile64 skipped (resource denied)
0:18:28 load avg: 2.22 [415/416] test_zipimport_support
0:18:30 load avg: 2.22 [416/416] test_zlib

Total duration: 18 min 31 sec
Tests result: FAILURE
make[1]: Leaving directory `/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2'
make build_all_merge_profile
make[1]: Entering directory `/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2'
true
make[1]: Leaving directory `/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2'
# Remove profile generation binary since we are done with it.
make clean
make[1]: Entering directory `/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2'
find . -depth -name '__pycache__' -exec rm -rf {} ';'
find . -name '*.py[co]' -exec rm -f {} ';'
find . -name '*.[oa]' -exec rm -f {} ';'
find . -name '*.s[ol]' -exec rm -f {} ';'
find . -name '*.so.[0-9]*.[0-9]*' -exec rm -f {} ';'
find build -name 'fficonfig.h' -exec rm -f {} ';' || true
find build -name '*.py' -exec rm -f {} ';' || true
find build -name '*.py[co]' -exec rm -f {} ';' || true
rm -f pybuilddir.txt
rm -f Lib/lib2to3/*Grammar*.pickle
rm -f Programs/_testembed Programs/_freeze_importlib
find build -type f -a ! -name '*.gc??' -exec rm -f {} ';'
rm -f Include/pydtrace_probes.h
rm -f profile-gen-stamp
make[1]: Leaving directory `/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2'
# This is an expensive target to build and it does not have proper
# makefile dependency information.  So, we create a "stamp" file
# to record its completion and avoid re-running it.
touch profile-run-stamp
Rebuilding with profile guided optimizations:
rm -f profile-clean-stamp
make build_all CFLAGS_NODIST=" -fprofile-use -fprofile-correction" LDFLAGS_NODIST=""
make[1]: Entering directory `/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2'
gcc -pthread -c -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall    -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-use -fprofile-correction  -I. -I./Include   -fPIC -DPy_BUILD_CORE -o Programs/python.o ./Programs/python.c
gcc -pthread -c -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall    -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-use -fprofile-correction  -I. -I./Include   -fPIC -DPy_BUILD_CORE -o Parser/acceler.o Parser/acceler.c
gcc -pthread -c -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall    -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-use -fprofile-correction  -I. -I./Include   -fPIC -DPy_BUILD_CORE -o Parser/grammar1.o Parser/grammar1.c
gcc -pthread -c -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall    -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-use -fprofile-correction  -I. -I./Include   -fPIC -DPy_BUILD_CORE -o Parser/listnode.o Parser/listnode.c
gcc -pthread -c -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall    -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-use -fprofile-correction  -I. -I./Include   -fPIC -DPy_BUILD_CORE -o Parser/node.o Parser/node.c
gcc -pthread -c -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall    -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-use -fprofile-correction  -I. -I./Include   -fPIC -DPy_BUILD_CORE -o Parser/parser.o Parser/parser.c
gcc -pthread -c -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall    -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-use -fprofile-correction  -I. -I./Include   -fPIC -DPy_BUILD_CORE -o Parser/bitset.o Parser/bitset.c
gcc -pthread -c -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall    -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-use -fprofile-correction  -I. -I./Include   -fPIC -DPy_BUILD_CORE -o Parser/metagrammar.o Parser/metagrammar.c
gcc -pthread -c -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall    -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-use -fprofile-correction  -I. -I./Include   -fPIC -DPy_BUILD_CORE -o Parser/firstsets.o Parser/firstsets.c
gcc -pthread -c -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall    -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-use -fprofile-correction  -I. -I./Include   -fPIC -DPy_BUILD_CORE -o Parser/grammar.o Parser/grammar.c
gcc -pthread -c -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall    -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-use -fprofile-correction  -I. -I./Include   -fPIC -DPy_BUILD_CORE -o Parser/pgen.o Parser/pgen.c
gcc -pthread -c -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall    -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-use -fprofile-correction  -I. -I./Include   -fPIC -DPy_BUILD_CORE -o Parser/myreadline.o Parser/myreadline.c
gcc -pthread -c -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall    -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-use -fprofile-correction  -I. -I./Include   -fPIC -DPy_BUILD_CORE -o Parser/parsetok.o Parser/parsetok.c
gcc -pthread -c -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall    -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-use -fprofile-correction  -I. -I./Include   -fPIC -DPy_BUILD_CORE -o Parser/tokenizer.o Parser/tokenizer.c
gcc -pthread -c -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall    -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-use -fprofile-correction  -I. -I./Include   -fPIC -DPy_BUILD_CORE -o Objects/abstract.o Objects/abstract.c
gcc -pthread -c -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall    -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-use -fprofile-correction  -I. -I./Include   -fPIC -DPy_BUILD_CORE -o Objects/accu.o Objects/accu.c
gcc -pthread -c -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall    -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-use -fprofile-correction  -I. -I./Include   -fPIC -DPy_BUILD_CORE -o Objects/boolobject.o Objects/boolobject.c
gcc -pthread -c -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall    -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-use -fprofile-correction  -I. -I./Include   -fPIC -DPy_BUILD_CORE -o Objects/bytes_methods.o Objects/bytes_methods.c
gcc -pthread -c -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall    -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-use -fprofile-correction  -I. -I./Include   -fPIC -DPy_BUILD_CORE -o Objects/bytearrayobject.o Objects/bytearrayobject.c
gcc -pthread -c -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall    -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-use -fprofile-correction  -I. -I./Include   -fPIC -DPy_BUILD_CORE -o Objects/bytesobject.o Objects/bytesobject.c
gcc -pthread -c -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall    -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-use -fprofile-correction  -I. -I./Include   -fPIC -DPy_BUILD_CORE -o Objects/call.o Objects/call.c
gcc -pthread -c -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall    -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-use -fprofile-correction  -I. -I./Include   -fPIC -DPy_BUILD_CORE -o Objects/cellobject.o Objects/cellobject.c
gcc -pthread -c -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall    -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-use -fprofile-correction  -I. -I./Include   -fPIC -DPy_BUILD_CORE -o Objects/classobject.o Objects/classobject.c
gcc -pthread -c -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall    -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-use -fprofile-correction  -I. -I./Include   -fPIC -DPy_BUILD_CORE -o Objects/codeobject.o Objects/codeobject.c
Objects/bytes_methods.c: In function ‘find_internal’:
Objects/bytes_methods.c:537:31: warning: ‘subobj’ may be used uninitialized in this function [-Wmaybe-uninitialized]
         if (PyObject_GetBuffer(subobj, &subbuf, PyBUF_SIMPLE) != 0)
                               ^
gcc -pthread -c -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall    -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-use -fprofile-correction  -I. -I./Include   -fPIC -DPy_BUILD_CORE -o Objects/complexobject.o Objects/complexobject.c
Objects/bytes_methods.c: In function ‘_Py_bytes_find’:
Objects/bytes_methods.c:537:31: warning: ‘subobj’ may be used uninitialized in this function [-Wmaybe-uninitialized]
Objects/bytes_methods.c:524:15: note: ‘subobj’ was declared here
     PyObject *subobj;
               ^
Objects/bytes_methods.c: In function ‘_Py_bytes_rfind’:
Objects/bytes_methods.c:537:31: warning: ‘subobj’ may be used uninitialized in this function [-Wmaybe-uninitialized]
         if (PyObject_GetBuffer(subobj, &subbuf, PyBUF_SIMPLE) != 0)
                               ^
Objects/bytes_methods.c:524:15: note: ‘subobj’ was declared here
     PyObject *subobj;
               ^
Objects/bytes_methods.c: In function ‘_Py_bytes_count’:
Objects/bytes_methods.c:686:31: warning: ‘sub_obj’ may be used uninitialized in this function [-Wmaybe-uninitialized]
         if (PyObject_GetBuffer(sub_obj, &vsub, PyBUF_SIMPLE) != 0)
                               ^
gcc -pthread -c -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall    -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-use -fprofile-correction  -I. -I./Include   -fPIC -DPy_BUILD_CORE -o Objects/descrobject.o Objects/descrobject.c
gcc -pthread -c -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall    -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-use -fprofile-correction  -I. -I./Include   -fPIC -DPy_BUILD_CORE -o Objects/enumobject.o Objects/enumobject.c
gcc -pthread -c -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall    -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-use -fprofile-correction  -I. -I./Include   -fPIC -DPy_BUILD_CORE -o Objects/exceptions.o Objects/exceptions.c
gcc -pthread -c -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall    -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-use -fprofile-correction  -I. -I./Include   -fPIC -DPy_BUILD_CORE -o Objects/genobject.o Objects/genobject.c
gcc -pthread -c -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall    -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-use -fprofile-correction  -I. -I./Include   -fPIC -DPy_BUILD_CORE -o Objects/fileobject.o Objects/fileobject.c
gcc -pthread -c -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall    -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-use -fprofile-correction  -I. -I./Include   -fPIC -DPy_BUILD_CORE -o Objects/floatobject.o Objects/floatobject.c
gcc -pthread -c -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall    -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-use -fprofile-correction  -I. -I./Include   -fPIC -DPy_BUILD_CORE -o Objects/frameobject.o Objects/frameobject.c
gcc -pthread -c -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall    -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-use -fprofile-correction  -I. -I./Include   -fPIC -DPy_BUILD_CORE -o Objects/funcobject.o Objects/funcobject.c
gcc -pthread -c -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall    -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-use -fprofile-correction  -I. -I./Include   -fPIC -DPy_BUILD_CORE -o Objects/iterobject.o Objects/iterobject.c
gcc -pthread -c -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall    -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-use -fprofile-correction  -I. -I./Include   -fPIC -DPy_BUILD_CORE -o Objects/listobject.o Objects/listobject.c
gcc -pthread -c -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall    -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-use -fprofile-correction  -I. -I./Include   -fPIC -DPy_BUILD_CORE -o Objects/longobject.o Objects/longobject.c
gcc -pthread -c -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall    -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-use -fprofile-correction  -I. -I./Include   -fPIC -DPy_BUILD_CORE -o Objects/dictobject.o Objects/dictobject.c
gcc -pthread -c -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall    -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-use -fprofile-correction  -I. -I./Include   -fPIC -DPy_BUILD_CORE -o Objects/odictobject.o Objects/odictobject.c
gcc -pthread -c -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall    -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-use -fprofile-correction  -I. -I./Include   -fPIC -DPy_BUILD_CORE -o Objects/memoryobject.o Objects/memoryobject.c
gcc -pthread -c -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall    -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-use -fprofile-correction  -I. -I./Include   -fPIC -DPy_BUILD_CORE -o Objects/methodobject.o Objects/methodobject.c
gcc -pthread -c -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall    -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-use -fprofile-correction  -I. -I./Include   -fPIC -DPy_BUILD_CORE -o Objects/moduleobject.o Objects/moduleobject.c
gcc -pthread -c -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall    -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-use -fprofile-correction  -I. -I./Include   -fPIC -DPy_BUILD_CORE -o Objects/namespaceobject.o Objects/namespaceobject.c
gcc -pthread -c -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall    -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-use -fprofile-correction  -I. -I./Include   -fPIC -DPy_BUILD_CORE -o Objects/object.o Objects/object.c
gcc -pthread -c -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall    -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-use -fprofile-correction  -I. -I./Include   -fPIC -DPy_BUILD_CORE -o Objects/obmalloc.o Objects/obmalloc.c
gcc -pthread -c -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall    -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-use -fprofile-correction  -I. -I./Include   -fPIC -DPy_BUILD_CORE -o Objects/capsule.o Objects/capsule.c
gcc -pthread -c -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall    -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-use -fprofile-correction  -I. -I./Include   -fPIC -DPy_BUILD_CORE -o Objects/rangeobject.o Objects/rangeobject.c
Objects/obmalloc.c:1351:1: warning: ‘no_sanitize_thread’ attribute directive ignored [-Wattributes]
 {
 ^
gcc -pthread -c -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall    -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-use -fprofile-correction  -I. -I./Include   -fPIC -DPy_BUILD_CORE -o Objects/setobject.o Objects/setobject.c
gcc -pthread -c -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall    -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-use -fprofile-correction  -I. -I./Include   -fPIC -DPy_BUILD_CORE -o Objects/sliceobject.o Objects/sliceobject.c
gcc -pthread -c -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall    -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-use -fprofile-correction  -I. -I./Include   -fPIC -DPy_BUILD_CORE -o Objects/structseq.o Objects/structseq.c
gcc -pthread -c -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall    -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-use -fprofile-correction  -I. -I./Include   -fPIC -DPy_BUILD_CORE -o Objects/tupleobject.o Objects/tupleobject.c
gcc -pthread -c -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall    -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-use -fprofile-correction  -I. -I./Include   -fPIC -DPy_BUILD_CORE -o Objects/typeobject.o Objects/typeobject.c
gcc -pthread -c -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall    -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-use -fprofile-correction  -I. -I./Include   -fPIC -DPy_BUILD_CORE -o Objects/unicodeobject.o Objects/unicodeobject.c
gcc -pthread -c -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall    -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-use -fprofile-correction  -I. -I./Include   -fPIC -DPy_BUILD_CORE -o Objects/unicodectype.o Objects/unicodectype.c
gcc -pthread -c -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall    -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-use -fprofile-correction  -I. -I./Include   -fPIC -DPy_BUILD_CORE -o Objects/weakrefobject.o Objects/weakrefobject.c
gcc -pthread -c -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall    -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-use -fprofile-correction  -I. -I./Include   -fPIC -DPy_BUILD_CORE -o Python/_warnings.o Python/_warnings.c
gcc -pthread -c -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall    -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-use -fprofile-correction  -I. -I./Include   -fPIC -DPy_BUILD_CORE -o Python/Python-ast.o Python/Python-ast.c
gcc -pthread -c -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall    -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-use -fprofile-correction  -I. -I./Include   -fPIC -DPy_BUILD_CORE -o Python/asdl.o Python/asdl.c
gcc -pthread -c -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall    -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-use -fprofile-correction  -I. -I./Include   -fPIC -DPy_BUILD_CORE -o Python/ast.o Python/ast.c
gcc -pthread -c -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall    -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-use -fprofile-correction  -I. -I./Include   -fPIC -DPy_BUILD_CORE -o Python/ast_opt.o Python/ast_opt.c
gcc -pthread -c -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall    -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-use -fprofile-correction  -I. -I./Include   -fPIC -DPy_BUILD_CORE -o Python/ast_unparse.o Python/ast_unparse.c
gcc -pthread -c -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall    -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-use -fprofile-correction  -I. -I./Include   -fPIC -DPy_BUILD_CORE -o Python/bltinmodule.o Python/bltinmodule.c
gcc -pthread -c -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall    -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-use -fprofile-correction  -I. -I./Include   -fPIC -DPy_BUILD_CORE -o Python/ceval.o Python/ceval.c
gcc -pthread -c -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall    -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-use -fprofile-correction  -I. -I./Include   -fPIC -DPy_BUILD_CORE -o Python/compile.o Python/compile.c
gcc -pthread -c -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall    -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-use -fprofile-correction  -I. -I./Include   -fPIC -DPy_BUILD_CORE -o Python/codecs.o Python/codecs.c
gcc -pthread -c -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall    -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-use -fprofile-correction  -I. -I./Include   -fPIC -DPy_BUILD_CORE -o Python/dynamic_annotations.o Python/dynamic_annotations.c
gcc -pthread -c -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall    -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-use -fprofile-correction  -I. -I./Include   -fPIC -DPy_BUILD_CORE -o Python/errors.o Python/errors.c
gcc -pthread -c -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall    -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-use -fprofile-correction  -I. -I./Include   -fPIC -DPy_BUILD_CORE -o Python/frozenmain.o Python/frozenmain.c
gcc -pthread -c -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall    -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-use -fprofile-correction  -I. -I./Include   -fPIC -DPy_BUILD_CORE -o Python/future.o Python/future.c
gcc -pthread -c -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall    -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-use -fprofile-correction  -I. -I./Include   -fPIC -DPy_BUILD_CORE -o Python/getargs.o Python/getargs.c
gcc -pthread -c -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall    -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-use -fprofile-correction  -I. -I./Include   -fPIC -DPy_BUILD_CORE -o Python/getcompiler.o Python/getcompiler.c
gcc -pthread -c -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall    -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-use -fprofile-correction  -I. -I./Include   -fPIC -DPy_BUILD_CORE -o Python/getcopyright.o Python/getcopyright.c
gcc -pthread -c -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall    -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-use -fprofile-correction  -I. -I./Include   -fPIC -DPy_BUILD_CORE -DPLATFORM='"linux"' -o Python/getplatform.o ./Python/getplatform.c
gcc -pthread -c -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall    -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-use -fprofile-correction  -I. -I./Include   -fPIC -DPy_BUILD_CORE -o Python/getversion.o Python/getversion.c
gcc -pthread -c -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall    -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-use -fprofile-correction  -I. -I./Include   -fPIC -DPy_BUILD_CORE -o Python/graminit.o Python/graminit.c
gcc -pthread -c -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall    -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-use -fprofile-correction  -I. -I./Include   -fPIC -DPy_BUILD_CORE -o Python/import.o Python/import.c
Python/Python-ast.c: In function ‘PyAST_obj2mod’:
Python/Python-ast.c:8368:12: warning: ‘res’ may be used uninitialized in this function [-Wmaybe-uninitialized]
     mod_ty res;
            ^
gcc -pthread -c -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall    -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-use -fprofile-correction  -I. -I./Include   -fPIC -DPy_BUILD_CORE -I. -o Python/importdl.o ./Python/importdl.c
gcc -pthread -c -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall    -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-use -fprofile-correction  -I. -I./Include   -fPIC -DPy_BUILD_CORE -o Python/marshal.o Python/marshal.c
gcc -pthread -c -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall    -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-use -fprofile-correction  -I. -I./Include   -fPIC -DPy_BUILD_CORE -o Python/modsupport.o Python/modsupport.c
gcc -pthread -c -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall    -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-use -fprofile-correction  -I. -I./Include   -fPIC -DPy_BUILD_CORE -o Python/mysnprintf.o Python/mysnprintf.c
gcc -pthread -c -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall    -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-use -fprofile-correction  -I. -I./Include   -fPIC -DPy_BUILD_CORE -o Python/mystrtoul.o Python/mystrtoul.c
gcc -pthread -c -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall    -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-use -fprofile-correction  -I. -I./Include   -fPIC -DPy_BUILD_CORE -o Python/pathconfig.o Python/pathconfig.c
gcc -pthread -c -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall    -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-use -fprofile-correction  -I. -I./Include   -fPIC -DPy_BUILD_CORE -o Python/peephole.o Python/peephole.c
gcc -pthread -c -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall    -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-use -fprofile-correction  -I. -I./Include   -fPIC -DPy_BUILD_CORE -o Python/pyarena.o Python/pyarena.c
gcc -pthread -c -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall    -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-use -fprofile-correction  -I. -I./Include   -fPIC -DPy_BUILD_CORE -o Python/pyctype.o Python/pyctype.c
gcc -pthread -c -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall    -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-use -fprofile-correction  -I. -I./Include   -fPIC -DPy_BUILD_CORE -o Python/pyfpe.o Python/pyfpe.c
gcc -pthread -c -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall    -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-use -fprofile-correction  -I. -I./Include   -fPIC -DPy_BUILD_CORE -o Python/pyhash.o Python/pyhash.c
gcc -pthread -c -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall    -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-use -fprofile-correction  -I. -I./Include   -fPIC -DPy_BUILD_CORE -o Python/pylifecycle.o Python/pylifecycle.c
gcc -pthread -c -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall    -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-use -fprofile-correction  -I. -I./Include   -fPIC -DPy_BUILD_CORE -o Python/pymath.o Python/pymath.c
gcc -pthread -c -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall    -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-use -fprofile-correction  -I. -I./Include   -fPIC -DPy_BUILD_CORE -o Python/pystate.o Python/pystate.c
gcc -pthread -c -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall    -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-use -fprofile-correction  -I. -I./Include   -fPIC -DPy_BUILD_CORE -o Python/context.o Python/context.c
gcc -pthread -c -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall    -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-use -fprofile-correction  -I. -I./Include   -fPIC -DPy_BUILD_CORE -o Python/hamt.o Python/hamt.c
gcc -pthread -c -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall    -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-use -fprofile-correction  -I. -I./Include   -fPIC -DPy_BUILD_CORE -o Python/pythonrun.o Python/pythonrun.c
gcc -pthread -c -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall    -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-use -fprofile-correction  -I. -I./Include   -fPIC -DPy_BUILD_CORE -o Python/pytime.o Python/pytime.c
Python/pylifecycle.c: In function ‘Py_NewInterpreter’:
Python/pylifecycle.c:1517:5: warning: ‘tstate’ may be used uninitialized in this function [-Wmaybe-uninitialized]
     return tstate;
     ^
gcc -pthread -c -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall    -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-use -fprofile-correction  -I. -I./Include   -fPIC -DPy_BUILD_CORE -o Python/bootstrap_hash.o Python/bootstrap_hash.c
gcc -pthread -c -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall    -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-use -fprofile-correction  -I. -I./Include   -fPIC -DPy_BUILD_CORE -o Python/structmember.o Python/structmember.c
gcc -pthread -c -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall    -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-use -fprofile-correction  -I. -I./Include   -fPIC -DPy_BUILD_CORE -o Python/symtable.o Python/symtable.c
gcc -pthread -c -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall    -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-use -fprofile-correction  -I. -I./Include   -fPIC -DPy_BUILD_CORE \
		-DABIFLAGS='"m"' \
		-DMULTIARCH=\"x86_64-linux-gnu\" \
		-o Python/sysmodule.o ./Python/sysmodule.c
gcc -pthread -c -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall    -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-use -fprofile-correction  -I. -I./Include   -fPIC -DPy_BUILD_CORE -o Python/thread.o Python/thread.c
gcc -pthread -c -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall    -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-use -fprofile-correction  -I. -I./Include   -fPIC -DPy_BUILD_CORE -o Python/traceback.o Python/traceback.c
gcc -pthread -c -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall    -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-use -fprofile-correction  -I. -I./Include   -fPIC -DPy_BUILD_CORE -o Python/getopt.o Python/getopt.c
Python/thread.c: In function ‘PyThread_acquire_lock_timed’:
Python/thread.c:228:1: note: correcting inconsistent profile data
 }
 ^
gcc -pthread -c -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall    -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-use -fprofile-correction  -I. -I./Include   -fPIC -DPy_BUILD_CORE -o Python/pystrcmp.o Python/pystrcmp.c
gcc -pthread -c -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall    -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-use -fprofile-correction  -I. -I./Include   -fPIC -DPy_BUILD_CORE -o Python/pystrtod.o Python/pystrtod.c
gcc -pthread -c -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall    -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-use -fprofile-correction  -I. -I./Include   -fPIC -DPy_BUILD_CORE -o Python/pystrhex.o Python/pystrhex.c
gcc -pthread -c -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall    -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-use -fprofile-correction  -I. -I./Include   -fPIC -DPy_BUILD_CORE  -o Python/dtoa.o Python/dtoa.c
gcc -pthread -c -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall    -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-use -fprofile-correction  -I. -I./Include   -fPIC -DPy_BUILD_CORE -o Python/formatter_unicode.o Python/formatter_unicode.c
gcc -pthread -c -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall    -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-use -fprofile-correction  -I. -I./Include   -fPIC -DPy_BUILD_CORE -o Python/fileutils.o Python/fileutils.c
gcc -pthread -c -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall    -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-use -fprofile-correction  -I. -I./Include   -fPIC -DPy_BUILD_CORE \
		-DSOABI='"cpython-37m-x86_64-linux-gnu"' \
		-o Python/dynload_shlib.o ./Python/dynload_shlib.c
gcc -pthread -c -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall    -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-use -fprofile-correction  -I. -I./Include   -fPIC -DPy_BUILD_CORE -o Modules/config.o Modules/config.c
gcc -pthread -c -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall    -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-use -fprofile-correction  -I. -I./Include   -fPIC -DPy_BUILD_CORE -DPYTHONPATH='""' \
		-DPREFIX='"/sc/orga/packages/lili_tem/pkg/python"' \
		-DEXEC_PREFIX='"/sc/orga/packages/lili_tem/pkg/python"' \
		-DVERSION='"3.7"' \
		-DVPATH='""' \
		-o Modules/getpath.o ./Modules/getpath.c
gcc -pthread -c -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall    -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-use -fprofile-correction  -I. -I./Include   -fPIC -DPy_BUILD_CORE -o Modules/main.o Modules/main.c
gcc -pthread -c -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall    -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-use -fprofile-correction  -I. -I./Include   -fPIC -DPy_BUILD_CORE -o Modules/gcmodule.o Modules/gcmodule.c
gcc -pthread -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall    -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-use -fprofile-correction  -I. -I./Include   -fPIC -DPy_BUILD_CORE_BUILTIN  -DPy_BUILD_CORE -c ./Modules/posixmodule.c -o Modules/posixmodule.o
gcc -pthread -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall    -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-use -fprofile-correction  -I. -I./Include   -fPIC -DPy_BUILD_CORE_BUILTIN  -c ./Modules/errnomodule.c -o Modules/errnomodule.o
gcc -pthread -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall    -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-use -fprofile-correction  -I. -I./Include   -fPIC -DPy_BUILD_CORE_BUILTIN  -c ./Modules/pwdmodule.c -o Modules/pwdmodule.o
gcc -pthread -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall    -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-use -fprofile-correction  -I. -I./Include   -fPIC -DPy_BUILD_CORE_BUILTIN  -c ./Modules/_sre.c -o Modules/_sre.o
gcc -pthread -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall    -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-use -fprofile-correction  -I. -I./Include   -fPIC -DPy_BUILD_CORE_BUILTIN  -c ./Modules/_codecsmodule.c -o Modules/_codecsmodule.o
gcc -pthread -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall    -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-use -fprofile-correction  -I. -I./Include   -fPIC -DPy_BUILD_CORE_BUILTIN  -c ./Modules/_weakref.c -o Modules/_weakref.o
gcc -pthread -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall    -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-use -fprofile-correction  -I. -I./Include   -fPIC -DPy_BUILD_CORE_BUILTIN  -DPy_BUILD_CORE -c ./Modules/_functoolsmodule.c -o Modules/_functoolsmodule.o
gcc -pthread -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall    -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-use -fprofile-correction  -I. -I./Include   -fPIC -DPy_BUILD_CORE_BUILTIN  -c ./Modules/_operator.c -o Modules/_operator.o
gcc -pthread -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall    -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-use -fprofile-correction  -I. -I./Include   -fPIC -DPy_BUILD_CORE_BUILTIN  -c ./Modules/_collectionsmodule.c -o Modules/_collectionsmodule.o
gcc -pthread -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall    -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-use -fprofile-correction  -I. -I./Include   -fPIC -DPy_BUILD_CORE_BUILTIN  -c ./Modules/_abc.c -o Modules/_abc.o
gcc -pthread -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall    -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-use -fprofile-correction  -I. -I./Include   -fPIC -DPy_BUILD_CORE_BUILTIN  -c ./Modules/itertoolsmodule.c -o Modules/itertoolsmodule.o
gcc -pthread -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall    -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-use -fprofile-correction  -I. -I./Include   -fPIC -DPy_BUILD_CORE_BUILTIN  -c ./Modules/atexitmodule.c -o Modules/atexitmodule.o
gcc -pthread -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall    -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-use -fprofile-correction  -I. -I./Include   -fPIC -DPy_BUILD_CORE_BUILTIN  -DPy_BUILD_CORE -c ./Modules/signalmodule.c -o Modules/signalmodule.o
gcc -pthread -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall    -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-use -fprofile-correction  -I. -I./Include   -fPIC -DPy_BUILD_CORE_BUILTIN  -c ./Modules/_stat.c -o Modules/_stat.o
gcc -pthread -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall    -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-use -fprofile-correction  -I. -I./Include   -fPIC -DPy_BUILD_CORE_BUILTIN  -DPy_BUILD_CORE -c ./Modules/timemodule.c -o Modules/timemodule.o
gcc -pthread -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall    -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-use -fprofile-correction  -I. -I./Include   -fPIC -DPy_BUILD_CORE_BUILTIN  -DPy_BUILD_CORE -c ./Modules/_threadmodule.c -o Modules/_threadmodule.o
gcc -pthread -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall    -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-use -fprofile-correction  -I. -I./Include   -fPIC -DPy_BUILD_CORE_BUILTIN  -c ./Modules/_localemodule.c -o Modules/_localemodule.o
gcc -pthread -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall    -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-use -fprofile-correction  -I. -I./Include   -fPIC -DPy_BUILD_CORE_BUILTIN  -DPy_BUILD_CORE -I./Modules/_io -c ./Modules/_io/_iomodule.c -o Modules/_iomodule.o
gcc -pthread -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall    -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-use -fprofile-correction  -I. -I./Include   -fPIC -DPy_BUILD_CORE_BUILTIN  -DPy_BUILD_CORE -I./Modules/_io -c ./Modules/_io/iobase.c -o Modules/iobase.o
gcc -pthread -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall    -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-use -fprofile-correction  -I. -I./Include   -fPIC -DPy_BUILD_CORE_BUILTIN  -DPy_BUILD_CORE -I./Modules/_io -c ./Modules/_io/fileio.c -o Modules/fileio.o
gcc -pthread -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall    -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-use -fprofile-correction  -I. -I./Include   -fPIC -DPy_BUILD_CORE_BUILTIN  -DPy_BUILD_CORE -I./Modules/_io -c ./Modules/_io/bytesio.c -o Modules/bytesio.o
gcc -pthread -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall    -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-use -fprofile-correction  -I. -I./Include   -fPIC -DPy_BUILD_CORE_BUILTIN  -DPy_BUILD_CORE -I./Modules/_io -c ./Modules/_io/bufferedio.c -o Modules/bufferedio.o
gcc -pthread -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall    -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-use -fprofile-correction  -I. -I./Include   -fPIC -DPy_BUILD_CORE_BUILTIN  -DPy_BUILD_CORE -I./Modules/_io -c ./Modules/_io/textio.c -o Modules/textio.o
gcc -pthread -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall    -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-use -fprofile-correction  -I. -I./Include   -fPIC -DPy_BUILD_CORE_BUILTIN  -DPy_BUILD_CORE -I./Modules/_io -c ./Modules/_io/stringio.c -o Modules/stringio.o
gcc -pthread -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall    -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-use -fprofile-correction  -I. -I./Include   -fPIC -DPy_BUILD_CORE_BUILTIN  -DPy_BUILD_CORE -c ./Modules/zipimport.c -o Modules/zipimport.o
gcc -pthread -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall    -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-use -fprofile-correction  -I. -I./Include   -fPIC -DPy_BUILD_CORE_BUILTIN  -c ./Modules/faulthandler.c -o Modules/faulthandler.o
gcc -pthread -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall    -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-use -fprofile-correction  -I. -I./Include   -fPIC -DPy_BUILD_CORE_BUILTIN  -c ./Modules/_tracemalloc.c -o Modules/_tracemalloc.o
gcc -pthread -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall    -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-use -fprofile-correction  -I. -I./Include   -fPIC -DPy_BUILD_CORE_BUILTIN  -c ./Modules/hashtable.c -o Modules/hashtable.o
gcc -pthread -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall    -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-use -fprofile-correction  -I. -I./Include   -fPIC -DPy_BUILD_CORE_BUILTIN  -c ./Modules/symtablemodule.c -o Modules/symtablemodule.o
gcc -pthread -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall    -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-use -fprofile-correction  -I. -I./Include   -fPIC -DPy_BUILD_CORE_BUILTIN  -c ./Modules/xxsubtype.c -o Modules/xxsubtype.o
gcc -pthread -c -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall    -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-use -fprofile-correction  -I. -I./Include   -fPIC -DPy_BUILD_CORE -o Python/frozen.o Python/frozen.c
gcc -pthread -c -fPIC -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall    -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-use -fprofile-correction  -I. -I./Include   -fPIC -DPy_BUILD_CORE -o Modules/_math.o Modules/_math.c
gcc -pthread -c -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall    -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-use -fprofile-correction  -I. -I./Include   -fPIC -DPy_BUILD_CORE -o Programs/_testembed.o ./Programs/_testembed.c
gcc -pthread -c -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall    -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-use -fprofile-correction  -I. -I./Include   -fPIC -DPy_BUILD_CORE \
	      -DGITVERSION="\"`LC_ALL=C `\"" \
	      -DGITTAG="\"`LC_ALL=C `\"" \
	      -DGITBRANCH="\"`LC_ALL=C `\"" \
	      -o Modules/getbuildinfo.o ./Modules/getbuildinfo.c
rm -f libpython3.7m.a
if test libpython3.7m.so.1.0 != libpython3.7m.so; then \
		gcc -pthread -shared     -Wl,-hlibpython3.7m.so.1.0 -o libpython3.7m.so.1.0 Modules/getbuildinfo.o Parser/acceler.o Parser/grammar1.o Parser/listnode.o Parser/node.o Parser/parser.o Parser/bitset.o Parser/metagrammar.o Parser/firstsets.o Parser/grammar.o Parser/pgen.o Parser/myreadline.o Parser/parsetok.o Parser/tokenizer.o Objects/abstract.o Objects/accu.o Objects/boolobject.o Objects/bytes_methods.o Objects/bytearrayobject.o Objects/bytesobject.o Objects/call.o Objects/cellobject.o Objects/classobject.o Objects/codeobject.o Objects/complexobject.o Objects/descrobject.o Objects/enumobject.o Objects/exceptions.o Objects/genobject.o Objects/fileobject.o Objects/floatobject.o Objects/frameobject.o Objects/funcobject.o Objects/iterobject.o Objects/listobject.o Objects/longobject.o Objects/dictobject.o Objects/odictobject.o Objects/memoryobject.o Objects/methodobject.o Objects/moduleobject.o Objects/namespaceobject.o Objects/object.o Objects/obmalloc.o Objects/capsule.o Objects/rangeobject.o Objects/setobject.o Objects/sliceobject.o Objects/structseq.o Objects/tupleobject.o Objects/typeobject.o Objects/unicodeobject.o Objects/unicodectype.o Objects/weakrefobject.o Python/_warnings.o Python/Python-ast.o Python/asdl.o Python/ast.o Python/ast_opt.o Python/ast_unparse.o Python/bltinmodule.o Python/ceval.o Python/compile.o Python/codecs.o Python/dynamic_annotations.o Python/errors.o Python/frozenmain.o Python/future.o Python/getargs.o Python/getcompiler.o Python/getcopyright.o Python/getplatform.o Python/getversion.o Python/graminit.o Python/import.o Python/importdl.o Python/marshal.o Python/modsupport.o Python/mysnprintf.o Python/mystrtoul.o Python/pathconfig.o Python/peephole.o Python/pyarena.o Python/pyctype.o Python/pyfpe.o Python/pyhash.o Python/pylifecycle.o Python/pymath.o Python/pystate.o Python/context.o Python/hamt.o Python/pythonrun.o Python/pytime.o Python/bootstrap_hash.o Python/structmember.o Python/symtable.o Python/sysmodule.o Python/thread.o Python/traceback.o Python/getopt.o Python/pystrcmp.o Python/pystrtod.o Python/pystrhex.o Python/dtoa.o Python/formatter_unicode.o Python/fileutils.o Python/dynload_shlib.o    Modules/config.o Modules/getpath.o Modules/main.o Modules/gcmodule.o Modules/posixmodule.o  Modules/errnomodule.o  Modules/pwdmodule.o  Modules/_sre.o  Modules/_codecsmodule.o  Modules/_weakref.o  Modules/_functoolsmodule.o  Modules/_operator.o  Modules/_collectionsmodule.o  Modules/_abc.o  Modules/itertoolsmodule.o  Modules/atexitmodule.o  Modules/signalmodule.o  Modules/_stat.o  Modules/timemodule.o  Modules/_threadmodule.o  Modules/_localemodule.o  Modules/_iomodule.o Modules/iobase.o Modules/fileio.o Modules/bytesio.o Modules/bufferedio.o Modules/textio.o Modules/stringio.o  Modules/zipimport.o  Modules/faulthandler.o  Modules/_tracemalloc.o Modules/hashtable.o  Modules/symtablemodule.o  Modules/xxsubtype.o Python/frozen.o   -lpthread -ldl  -lutil -lrt  -lm ; \
		ln -f libpython3.7m.so.1.0 libpython3.7m.so; \
	else \
		gcc -pthread -shared     -o libpython3.7m.so Modules/getbuildinfo.o Parser/acceler.o Parser/grammar1.o Parser/listnode.o Parser/node.o Parser/parser.o Parser/bitset.o Parser/metagrammar.o Parser/firstsets.o Parser/grammar.o Parser/pgen.o Parser/myreadline.o Parser/parsetok.o Parser/tokenizer.o Objects/abstract.o Objects/accu.o Objects/boolobject.o Objects/bytes_methods.o Objects/bytearrayobject.o Objects/bytesobject.o Objects/call.o Objects/cellobject.o Objects/classobject.o Objects/codeobject.o Objects/complexobject.o Objects/descrobject.o Objects/enumobject.o Objects/exceptions.o Objects/genobject.o Objects/fileobject.o Objects/floatobject.o Objects/frameobject.o Objects/funcobject.o Objects/iterobject.o Objects/listobject.o Objects/longobject.o Objects/dictobject.o Objects/odictobject.o Objects/memoryobject.o Objects/methodobject.o Objects/moduleobject.o Objects/namespaceobject.o Objects/object.o Objects/obmalloc.o Objects/capsule.o Objects/rangeobject.o Objects/setobject.o Objects/sliceobject.o Objects/structseq.o Objects/tupleobject.o Objects/typeobject.o Objects/unicodeobject.o Objects/unicodectype.o Objects/weakrefobject.o Python/_warnings.o Python/Python-ast.o Python/asdl.o Python/ast.o Python/ast_opt.o Python/ast_unparse.o Python/bltinmodule.o Python/ceval.o Python/compile.o Python/codecs.o Python/dynamic_annotations.o Python/errors.o Python/frozenmain.o Python/future.o Python/getargs.o Python/getcompiler.o Python/getcopyright.o Python/getplatform.o Python/getversion.o Python/graminit.o Python/import.o Python/importdl.o Python/marshal.o Python/modsupport.o Python/mysnprintf.o Python/mystrtoul.o Python/pathconfig.o Python/peephole.o Python/pyarena.o Python/pyctype.o Python/pyfpe.o Python/pyhash.o Python/pylifecycle.o Python/pymath.o Python/pystate.o Python/context.o Python/hamt.o Python/pythonrun.o Python/pytime.o Python/bootstrap_hash.o Python/structmember.o Python/symtable.o Python/sysmodule.o Python/thread.o Python/traceback.o Python/getopt.o Python/pystrcmp.o Python/pystrtod.o Python/pystrhex.o Python/dtoa.o Python/formatter_unicode.o Python/fileutils.o Python/dynload_shlib.o    Modules/config.o Modules/getpath.o Modules/main.o Modules/gcmodule.o Modules/posixmodule.o  Modules/errnomodule.o  Modules/pwdmodule.o  Modules/_sre.o  Modules/_codecsmodule.o  Modules/_weakref.o  Modules/_functoolsmodule.o  Modules/_operator.o  Modules/_collectionsmodule.o  Modules/_abc.o  Modules/itertoolsmodule.o  Modules/atexitmodule.o  Modules/signalmodule.o  Modules/_stat.o  Modules/timemodule.o  Modules/_threadmodule.o  Modules/_localemodule.o  Modules/_iomodule.o Modules/iobase.o Modules/fileio.o Modules/bytesio.o Modules/bufferedio.o Modules/textio.o Modules/stringio.o  Modules/zipimport.o  Modules/faulthandler.o  Modules/_tracemalloc.o Modules/hashtable.o  Modules/symtablemodule.o  Modules/xxsubtype.o Python/frozen.o   -lpthread -ldl  -lutil -lrt  -lm ; \
	fi
ar rcs libpython3.7m.a Modules/getbuildinfo.o Parser/acceler.o Parser/grammar1.o Parser/listnode.o Parser/node.o Parser/parser.o Parser/bitset.o Parser/metagrammar.o Parser/firstsets.o Parser/grammar.o Parser/pgen.o Parser/myreadline.o Parser/parsetok.o Parser/tokenizer.o Objects/abstract.o Objects/accu.o Objects/boolobject.o Objects/bytes_methods.o Objects/bytearrayobject.o Objects/bytesobject.o Objects/call.o Objects/cellobject.o Objects/classobject.o Objects/codeobject.o Objects/complexobject.o Objects/descrobject.o Objects/enumobject.o Objects/exceptions.o Objects/genobject.o Objects/fileobject.o Objects/floatobject.o Objects/frameobject.o Objects/funcobject.o Objects/iterobject.o Objects/listobject.o Objects/longobject.o Objects/dictobject.o Objects/odictobject.o Objects/memoryobject.o Objects/methodobject.o Objects/moduleobject.o Objects/namespaceobject.o Objects/object.o Objects/obmalloc.o Objects/capsule.o Objects/rangeobject.o Objects/setobject.o Objects/sliceobject.o Objects/structseq.o Objects/tupleobject.o Objects/typeobject.o Objects/unicodeobject.o Objects/unicodectype.o Objects/weakrefobject.o Python/_warnings.o Python/Python-ast.o Python/asdl.o Python/ast.o Python/ast_opt.o Python/ast_unparse.o Python/bltinmodule.o Python/ceval.o Python/compile.o Python/codecs.o Python/dynamic_annotations.o Python/errors.o Python/frozenmain.o Python/future.o Python/getargs.o Python/getcompiler.o Python/getcopyright.o Python/getplatform.o Python/getversion.o Python/graminit.o Python/import.o Python/importdl.o Python/marshal.o Python/modsupport.o Python/mysnprintf.o Python/mystrtoul.o Python/pathconfig.o Python/peephole.o Python/pyarena.o Python/pyctype.o Python/pyfpe.o Python/pyhash.o Python/pylifecycle.o Python/pymath.o Python/pystate.o Python/context.o Python/hamt.o Python/pythonrun.o Python/pytime.o Python/bootstrap_hash.o Python/structmember.o Python/symtable.o Python/sysmodule.o Python/thread.o Python/traceback.o Python/getopt.o Python/pystrcmp.o Python/pystrtod.o Python/pystrhex.o Python/dtoa.o Python/formatter_unicode.o Python/fileutils.o Python/dynload_shlib.o    Modules/config.o Modules/getpath.o Modules/main.o Modules/gcmodule.o Modules/posixmodule.o  Modules/errnomodule.o  Modules/pwdmodule.o  Modules/_sre.o  Modules/_codecsmodule.o  Modules/_weakref.o  Modules/_functoolsmodule.o  Modules/_operator.o  Modules/_collectionsmodule.o  Modules/_abc.o  Modules/itertoolsmodule.o  Modules/atexitmodule.o  Modules/signalmodule.o  Modules/_stat.o  Modules/timemodule.o  Modules/_threadmodule.o  Modules/_localemodule.o  Modules/_iomodule.o Modules/iobase.o Modules/fileio.o Modules/bytesio.o Modules/bufferedio.o Modules/textio.o Modules/stringio.o  Modules/zipimport.o  Modules/faulthandler.o  Modules/_tracemalloc.o Modules/hashtable.o  Modules/symtablemodule.o  Modules/xxsubtype.o Python/frozen.o
gcc -pthread -shared     -Wl,--no-as-needed -o libpython3.so -Wl,-hlibpython3.so libpython3.7m.so
gcc -pthread     -Xlinker -export-dynamic -o python Programs/python.o -L. -lpython3.7m -lpthread -ldl  -lutil -lrt   -lm  
gcc -pthread     -Xlinker -export-dynamic -o Programs/_testembed Programs/_testembed.o -L. -lpython3.7m -lpthread -ldl  -lutil -lrt   -lm  
LD_LIBRARY_PATH=/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2:/hpc/packages/minerva-common/gcc/4.8.2/lib64:/hpc/packages/minerva-common/gcc/4.8.2/lib:/hpc/packages/minerva-common/mpc/1.0.2/lib:/hpc/packages/minerva-common/mpc/1.0.2/lib64:/hpc/packages/minerva-common/mpfr/3.1.2/lib:/hpc/packages/minerva-common/gmp/5.1.3/lib64:/hpc/packages/minerva-common/gmp/5.1.3/lib:/hpc/lsf/9.1/linux2.6-glibc2.3-x86_64/lib ./python -E -S -m sysconfig --generate-posix-vars ;\
	if test $? -ne 0 ; then \
		echo "generate-posix-vars failed" ; \
		rm -f ./pybuilddir.txt ; \
		exit 1 ; \
	fi
LD_LIBRARY_PATH=/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2:/hpc/packages/minerva-common/gcc/4.8.2/lib64:/hpc/packages/minerva-common/gcc/4.8.2/lib:/hpc/packages/minerva-common/mpc/1.0.2/lib:/hpc/packages/minerva-common/mpc/1.0.2/lib64:/hpc/packages/minerva-common/mpfr/3.1.2/lib:/hpc/packages/minerva-common/gmp/5.1.3/lib64:/hpc/packages/minerva-common/gmp/5.1.3/lib:/hpc/lsf/9.1/linux2.6-glibc2.3-x86_64/lib CC='gcc -pthread' LDSHARED='gcc -pthread -shared    ' OPT='-DNDEBUG -g -fwrapv -O3 -Wall' 	_TCLTK_INCLUDES='' _TCLTK_LIBS='' 	./python -E ./setup.py  build
running build
running build_ext
building '_struct' extension
gcc -pthread -fPIC -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-use -fprofile-correction -I./Include -I. -I/usr/local/include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2 -c /sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_struct.c -o build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_struct.o
gcc -pthread -shared build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_struct.o -L. -L/usr/local/lib -lpython3.7m -o build/lib.linux-x86_64-3.7/_struct.cpython-37m-x86_64-linux-gnu.so
building '_ctypes_test' extension
gcc -pthread -fPIC -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-use -fprofile-correction -I./Include -I. -I/usr/local/include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2 -c /sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_ctypes/_ctypes_test.c -o build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_ctypes/_ctypes_test.o
gcc -pthread -shared build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_ctypes/_ctypes_test.o -L. -L/usr/local/lib -lm -lpython3.7m -o build/lib.linux-x86_64-3.7/_ctypes_test.cpython-37m-x86_64-linux-gnu.so
building 'array' extension
gcc -pthread -fPIC -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-use -fprofile-correction -I./Include -I. -I/usr/local/include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2 -c /sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/arraymodule.c -o build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/arraymodule.o
gcc -pthread -shared build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/arraymodule.o -L. -L/usr/local/lib -lpython3.7m -o build/lib.linux-x86_64-3.7/array.cpython-37m-x86_64-linux-gnu.so
building '_contextvars' extension
gcc -pthread -fPIC -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-use -fprofile-correction -I./Include -I. -I/usr/local/include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2 -c /sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_contextvarsmodule.c -o build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_contextvarsmodule.o
gcc -pthread -shared build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_contextvarsmodule.o -L. -L/usr/local/lib -lpython3.7m -o build/lib.linux-x86_64-3.7/_contextvars.cpython-37m-x86_64-linux-gnu.so
building 'cmath' extension
gcc -pthread -fPIC -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-use -fprofile-correction -I./Include -I. -I/usr/local/include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2 -c /sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/cmathmodule.c -o build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/cmathmodule.o
gcc -pthread -shared build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/cmathmodule.o Modules/_math.o -L. -L/usr/local/lib -lm -lpython3.7m -o build/lib.linux-x86_64-3.7/cmath.cpython-37m-x86_64-linux-gnu.so
building 'math' extension
gcc -pthread -fPIC -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-use -fprofile-correction -I./Include -I. -I/usr/local/include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2 -c /sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/mathmodule.c -o build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/mathmodule.o
gcc -pthread -shared build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/mathmodule.o Modules/_math.o -L. -L/usr/local/lib -lm -lpython3.7m -o build/lib.linux-x86_64-3.7/math.cpython-37m-x86_64-linux-gnu.so
building '_datetime' extension
gcc -pthread -fPIC -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-use -fprofile-correction -I./Include -I. -I/usr/local/include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2 -c /sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_datetimemodule.c -o build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_datetimemodule.o
gcc -pthread -shared build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_datetimemodule.o -L. -L/usr/local/lib -lm -lpython3.7m -o build/lib.linux-x86_64-3.7/_datetime.cpython-37m-x86_64-linux-gnu.so
building '_random' extension
gcc -pthread -fPIC -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-use -fprofile-correction -I./Include -I. -I/usr/local/include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2 -c /sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_randommodule.c -o build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_randommodule.o
gcc -pthread -shared build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_randommodule.o -L. -L/usr/local/lib -lpython3.7m -o build/lib.linux-x86_64-3.7/_random.cpython-37m-x86_64-linux-gnu.so
building '_bisect' extension
gcc -pthread -fPIC -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-use -fprofile-correction -I./Include -I. -I/usr/local/include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2 -c /sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_bisectmodule.c -o build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_bisectmodule.o
gcc -pthread -shared build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_bisectmodule.o -L. -L/usr/local/lib -lpython3.7m -o build/lib.linux-x86_64-3.7/_bisect.cpython-37m-x86_64-linux-gnu.so
building '_heapq' extension
gcc -pthread -fPIC -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-use -fprofile-correction -I./Include -I. -I/usr/local/include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2 -c /sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_heapqmodule.c -o build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_heapqmodule.o
gcc -pthread -shared build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_heapqmodule.o -L. -L/usr/local/lib -lpython3.7m -o build/lib.linux-x86_64-3.7/_heapq.cpython-37m-x86_64-linux-gnu.so
building '_pickle' extension
gcc -pthread -fPIC -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-use -fprofile-correction -I./Include -I. -I/usr/local/include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2 -c /sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_pickle.c -o build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_pickle.o
/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_pickle.c: In function ‘load’:
/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_pickle.c:4785:15: warning: ‘s’ may be used uninitialized in this function [-Wmaybe-uninitialized]
         value = PyLong_FromString(s, NULL, 0);
               ^
/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_pickle.c:4766:20: note: ‘s’ was declared here
     char *endptr, *s;
                    ^
gcc -pthread -shared build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_pickle.o -L. -L/usr/local/lib -lpython3.7m -o build/lib.linux-x86_64-3.7/_pickle.cpython-37m-x86_64-linux-gnu.so
building '_json' extension
gcc -pthread -fPIC -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-use -fprofile-correction -I./Include -I. -I/usr/local/include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2 -c /sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_json.c -o build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_json.o
gcc -pthread -shared build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_json.o -L. -L/usr/local/lib -lpython3.7m -o build/lib.linux-x86_64-3.7/_json.cpython-37m-x86_64-linux-gnu.so
building '_testcapi' extension
gcc -pthread -fPIC -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-use -fprofile-correction -I./Include -I. -I/usr/local/include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2 -c /sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_testcapimodule.c -o build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_testcapimodule.o
gcc -pthread -shared build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_testcapimodule.o -L. -L/usr/local/lib -lpython3.7m -o build/lib.linux-x86_64-3.7/_testcapi.cpython-37m-x86_64-linux-gnu.so
building '_testbuffer' extension
gcc -pthread -fPIC -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-use -fprofile-correction -I./Include -I. -I/usr/local/include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2 -c /sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_testbuffer.c -o build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_testbuffer.o
gcc -pthread -shared build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_testbuffer.o -L. -L/usr/local/lib -lpython3.7m -o build/lib.linux-x86_64-3.7/_testbuffer.cpython-37m-x86_64-linux-gnu.so
building '_testimportmultiple' extension
gcc -pthread -fPIC -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-use -fprofile-correction -I./Include -I. -I/usr/local/include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2 -c /sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_testimportmultiple.c -o build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_testimportmultiple.o
gcc -pthread -shared build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_testimportmultiple.o -L. -L/usr/local/lib -lpython3.7m -o build/lib.linux-x86_64-3.7/_testimportmultiple.cpython-37m-x86_64-linux-gnu.so
building '_testmultiphase' extension
gcc -pthread -fPIC -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-use -fprofile-correction -I./Include -I. -I/usr/local/include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2 -c /sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_testmultiphase.c -o build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_testmultiphase.o
gcc -pthread -shared build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_testmultiphase.o -L. -L/usr/local/lib -lpython3.7m -o build/lib.linux-x86_64-3.7/_testmultiphase.cpython-37m-x86_64-linux-gnu.so
building '_lsprof' extension
gcc -pthread -fPIC -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-use -fprofile-correction -I./Include -I. -I/usr/local/include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2 -c /sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_lsprof.c -o build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_lsprof.o
gcc -pthread -fPIC -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-use -fprofile-correction -I./Include -I. -I/usr/local/include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2 -c /sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/rotatingtree.c -o build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/rotatingtree.o
gcc -pthread -shared build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_lsprof.o build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/rotatingtree.o -L. -L/usr/local/lib -lpython3.7m -o build/lib.linux-x86_64-3.7/_lsprof.cpython-37m-x86_64-linux-gnu.so
building 'unicodedata' extension
gcc -pthread -fPIC -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-use -fprofile-correction -I./Include -I. -I/usr/local/include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2 -c /sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/unicodedata.c -o build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/unicodedata.o
gcc -pthread -shared build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/unicodedata.o -L. -L/usr/local/lib -lpython3.7m -o build/lib.linux-x86_64-3.7/unicodedata.cpython-37m-x86_64-linux-gnu.so
building '_opcode' extension
gcc -pthread -fPIC -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-use -fprofile-correction -I./Include -I. -I/usr/local/include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2 -c /sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_opcode.c -o build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_opcode.o
gcc -pthread -shared build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_opcode.o -L. -L/usr/local/lib -lpython3.7m -o build/lib.linux-x86_64-3.7/_opcode.cpython-37m-x86_64-linux-gnu.so
building '_asyncio' extension
gcc -pthread -fPIC -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-use -fprofile-correction -I./Include -I. -I/usr/local/include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2 -c /sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_asynciomodule.c -o build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_asynciomodule.o
gcc -pthread -shared build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_asynciomodule.o -L. -L/usr/local/lib -lpython3.7m -o build/lib.linux-x86_64-3.7/_asyncio.cpython-37m-x86_64-linux-gnu.so
building '_queue' extension
gcc -pthread -fPIC -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-use -fprofile-correction -I./Include -I. -I/usr/local/include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2 -c /sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_queuemodule.c -o build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_queuemodule.o
gcc -pthread -shared build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_queuemodule.o -L. -L/usr/local/lib -lpython3.7m -o build/lib.linux-x86_64-3.7/_queue.cpython-37m-x86_64-linux-gnu.so
building 'fcntl' extension
gcc -pthread -fPIC -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-use -fprofile-correction -I./Include -I. -I/usr/local/include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2 -c /sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/fcntlmodule.c -o build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/fcntlmodule.o
gcc -pthread -shared build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/fcntlmodule.o -L. -L/usr/local/lib -lpython3.7m -o build/lib.linux-x86_64-3.7/fcntl.cpython-37m-x86_64-linux-gnu.so
building 'grp' extension
gcc -pthread -fPIC -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-use -fprofile-correction -I./Include -I. -I/usr/local/include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2 -c /sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/grpmodule.c -o build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/grpmodule.o
gcc -pthread -shared build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/grpmodule.o -L. -L/usr/local/lib -lpython3.7m -o build/lib.linux-x86_64-3.7/grp.cpython-37m-x86_64-linux-gnu.so
building 'spwd' extension
gcc -pthread -fPIC -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-use -fprofile-correction -I./Include -I. -I/usr/local/include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2 -c /sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/spwdmodule.c -o build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/spwdmodule.o
gcc -pthread -shared build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/spwdmodule.o -L. -L/usr/local/lib -lpython3.7m -o build/lib.linux-x86_64-3.7/spwd.cpython-37m-x86_64-linux-gnu.so
building 'select' extension
gcc -pthread -fPIC -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-use -fprofile-correction -I./Include -I. -I/usr/local/include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2 -c /sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/selectmodule.c -o build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/selectmodule.o
gcc -pthread -shared build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/selectmodule.o -L. -L/usr/local/lib -lpython3.7m -o build/lib.linux-x86_64-3.7/select.cpython-37m-x86_64-linux-gnu.so
building 'parser' extension
gcc -pthread -fPIC -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-use -fprofile-correction -I./Include -I. -I/usr/local/include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2 -c /sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/parsermodule.c -o build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/parsermodule.o
gcc -pthread -shared build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/parsermodule.o -L. -L/usr/local/lib -lpython3.7m -o build/lib.linux-x86_64-3.7/parser.cpython-37m-x86_64-linux-gnu.so
building 'mmap' extension
gcc -pthread -fPIC -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-use -fprofile-correction -I./Include -I. -I/usr/local/include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2 -c /sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/mmapmodule.c -o build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/mmapmodule.o
gcc -pthread -shared build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/mmapmodule.o -L. -L/usr/local/lib -lpython3.7m -o build/lib.linux-x86_64-3.7/mmap.cpython-37m-x86_64-linux-gnu.so
building 'syslog' extension
gcc -pthread -fPIC -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-use -fprofile-correction -I./Include -I. -I/usr/local/include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2 -c /sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/syslogmodule.c -o build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/syslogmodule.o
gcc -pthread -shared build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/syslogmodule.o -L. -L/usr/local/lib -lpython3.7m -o build/lib.linux-x86_64-3.7/syslog.cpython-37m-x86_64-linux-gnu.so
building '_xxtestfuzz' extension
gcc -pthread -fPIC -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-use -fprofile-correction -I./Include -I. -I/usr/local/include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2 -c /sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_xxtestfuzz/_xxtestfuzz.c -o build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_xxtestfuzz/_xxtestfuzz.o
gcc -pthread -fPIC -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-use -fprofile-correction -I./Include -I. -I/usr/local/include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2 -c /sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_xxtestfuzz/fuzzer.c -o build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_xxtestfuzz/fuzzer.o
gcc -pthread -shared build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_xxtestfuzz/_xxtestfuzz.o build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_xxtestfuzz/fuzzer.o -L. -L/usr/local/lib -lpython3.7m -o build/lib.linux-x86_64-3.7/_xxtestfuzz.cpython-37m-x86_64-linux-gnu.so
building 'audioop' extension
gcc -pthread -fPIC -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-use -fprofile-correction -I./Include -I. -I/usr/local/include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2 -c /sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/audioop.c -o build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/audioop.o
gcc -pthread -shared build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/audioop.o -L. -L/usr/local/lib -lm -lpython3.7m -o build/lib.linux-x86_64-3.7/audioop.cpython-37m-x86_64-linux-gnu.so
building 'readline' extension
gcc -pthread -fPIC -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-use -fprofile-correction -I./Include -I. -I/usr/local/include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2 -c /sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/readline.c -o build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/readline.o
gcc -pthread -shared build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/readline.o -L/usr/lib/termcap -L. -L/usr/local/lib -lreadline -lpython3.7m -o build/lib.linux-x86_64-3.7/readline.cpython-37m-x86_64-linux-gnu.so
building '_crypt' extension
gcc -pthread -fPIC -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-use -fprofile-correction -I./Include -I. -I/usr/local/include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2 -c /sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_cryptmodule.c -o build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_cryptmodule.o
gcc -pthread -shared build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_cryptmodule.o -L. -L/usr/local/lib -lcrypt -lpython3.7m -o build/lib.linux-x86_64-3.7/_crypt.cpython-37m-x86_64-linux-gnu.so
building '_csv' extension
gcc -pthread -fPIC -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-use -fprofile-correction -I./Include -I. -I/usr/local/include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2 -c /sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_csv.c -o build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_csv.o
gcc -pthread -shared build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_csv.o -L. -L/usr/local/lib -lpython3.7m -o build/lib.linux-x86_64-3.7/_csv.cpython-37m-x86_64-linux-gnu.so
building '_posixsubprocess' extension
gcc -pthread -fPIC -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-use -fprofile-correction -I./Include -I. -I/usr/local/include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2 -c /sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_posixsubprocess.c -o build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_posixsubprocess.o
gcc -pthread -shared build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_posixsubprocess.o -L. -L/usr/local/lib -lpython3.7m -o build/lib.linux-x86_64-3.7/_posixsubprocess.cpython-37m-x86_64-linux-gnu.so
building '_socket' extension
gcc -pthread -fPIC -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-use -fprofile-correction -I./Include -I. -I/usr/local/include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2 -c /sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/socketmodule.c -o build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/socketmodule.o
gcc -pthread -shared build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/socketmodule.o -L. -L/usr/local/lib -lpython3.7m -o build/lib.linux-x86_64-3.7/_socket.cpython-37m-x86_64-linux-gnu.so
building '_hashlib' extension
gcc -pthread -fPIC -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-use -fprofile-correction -I./Include -I. -I/usr/local/include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2 -c /sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_hashopenssl.c -o build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_hashopenssl.o
gcc -pthread -shared build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_hashopenssl.o -L. -L/usr/local/lib -lssl -lcrypto -lpython3.7m -o build/lib.linux-x86_64-3.7/_hashlib.cpython-37m-x86_64-linux-gnu.so
building '_sha256' extension
gcc -pthread -fPIC -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-use -fprofile-correction -I./Include -I. -I/usr/local/include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2 -c /sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/sha256module.c -o build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/sha256module.o
gcc -pthread -shared build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/sha256module.o -L. -L/usr/local/lib -lpython3.7m -o build/lib.linux-x86_64-3.7/_sha256.cpython-37m-x86_64-linux-gnu.so
building '_sha512' extension
gcc -pthread -fPIC -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-use -fprofile-correction -I./Include -I. -I/usr/local/include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2 -c /sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/sha512module.c -o build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/sha512module.o
gcc -pthread -shared build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/sha512module.o -L. -L/usr/local/lib -lpython3.7m -o build/lib.linux-x86_64-3.7/_sha512.cpython-37m-x86_64-linux-gnu.so
building '_md5' extension
gcc -pthread -fPIC -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-use -fprofile-correction -I./Include -I. -I/usr/local/include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2 -c /sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/md5module.c -o build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/md5module.o
gcc -pthread -shared build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/md5module.o -L. -L/usr/local/lib -lpython3.7m -o build/lib.linux-x86_64-3.7/_md5.cpython-37m-x86_64-linux-gnu.so
building '_sha1' extension
gcc -pthread -fPIC -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-use -fprofile-correction -I./Include -I. -I/usr/local/include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2 -c /sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/sha1module.c -o build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/sha1module.o
gcc -pthread -shared build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/sha1module.o -L. -L/usr/local/lib -lpython3.7m -o build/lib.linux-x86_64-3.7/_sha1.cpython-37m-x86_64-linux-gnu.so
building '_blake2' extension
gcc -pthread -fPIC -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-use -fprofile-correction -I./Include -I. -I/usr/local/include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2 -c /sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_blake2/blake2module.c -o build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_blake2/blake2module.o
gcc -pthread -fPIC -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-use -fprofile-correction -I./Include -I. -I/usr/local/include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2 -c /sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_blake2/blake2b_impl.c -o build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_blake2/blake2b_impl.o
gcc -pthread -fPIC -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-use -fprofile-correction -I./Include -I. -I/usr/local/include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2 -c /sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_blake2/blake2s_impl.c -o build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_blake2/blake2s_impl.o
gcc -pthread -shared build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_blake2/blake2module.o build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_blake2/blake2b_impl.o build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_blake2/blake2s_impl.o -L. -L/usr/local/lib -lpython3.7m -o build/lib.linux-x86_64-3.7/_blake2.cpython-37m-x86_64-linux-gnu.so
building '_sha3' extension
gcc -pthread -fPIC -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-use -fprofile-correction -I./Include -I. -I/usr/local/include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2 -c /sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_sha3/sha3module.c -o build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_sha3/sha3module.o
gcc -pthread -shared build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_sha3/sha3module.o -L. -L/usr/local/lib -lpython3.7m -o build/lib.linux-x86_64-3.7/_sha3.cpython-37m-x86_64-linux-gnu.so
building '_sqlite3' extension
gcc -pthread -fPIC -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-use -fprofile-correction -DMODULE_NAME="sqlite3" -DSQLITE_OMIT_LOAD_EXTENSION=1 -IModules/_sqlite -I/usr/include -I./Include -I. -I/usr/local/include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2 -c /sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_sqlite/cache.c -o build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_sqlite/cache.o
gcc -pthread -fPIC -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-use -fprofile-correction -DMODULE_NAME="sqlite3" -DSQLITE_OMIT_LOAD_EXTENSION=1 -IModules/_sqlite -I/usr/include -I./Include -I. -I/usr/local/include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2 -c /sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_sqlite/connection.c -o build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_sqlite/connection.o
gcc -pthread -fPIC -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-use -fprofile-correction -DMODULE_NAME="sqlite3" -DSQLITE_OMIT_LOAD_EXTENSION=1 -IModules/_sqlite -I/usr/include -I./Include -I. -I/usr/local/include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2 -c /sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_sqlite/cursor.c -o build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_sqlite/cursor.o
gcc -pthread -fPIC -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-use -fprofile-correction -DMODULE_NAME="sqlite3" -DSQLITE_OMIT_LOAD_EXTENSION=1 -IModules/_sqlite -I/usr/include -I./Include -I. -I/usr/local/include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2 -c /sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_sqlite/microprotocols.c -o build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_sqlite/microprotocols.o
gcc -pthread -fPIC -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-use -fprofile-correction -DMODULE_NAME="sqlite3" -DSQLITE_OMIT_LOAD_EXTENSION=1 -IModules/_sqlite -I/usr/include -I./Include -I. -I/usr/local/include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2 -c /sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_sqlite/module.c -o build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_sqlite/module.o
gcc -pthread -fPIC -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-use -fprofile-correction -DMODULE_NAME="sqlite3" -DSQLITE_OMIT_LOAD_EXTENSION=1 -IModules/_sqlite -I/usr/include -I./Include -I. -I/usr/local/include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2 -c /sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_sqlite/prepare_protocol.c -o build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_sqlite/prepare_protocol.o
gcc -pthread -fPIC -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-use -fprofile-correction -DMODULE_NAME="sqlite3" -DSQLITE_OMIT_LOAD_EXTENSION=1 -IModules/_sqlite -I/usr/include -I./Include -I. -I/usr/local/include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2 -c /sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_sqlite/row.c -o build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_sqlite/row.o
gcc -pthread -fPIC -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-use -fprofile-correction -DMODULE_NAME="sqlite3" -DSQLITE_OMIT_LOAD_EXTENSION=1 -IModules/_sqlite -I/usr/include -I./Include -I. -I/usr/local/include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2 -c /sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_sqlite/statement.c -o build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_sqlite/statement.o
gcc -pthread -fPIC -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-use -fprofile-correction -DMODULE_NAME="sqlite3" -DSQLITE_OMIT_LOAD_EXTENSION=1 -IModules/_sqlite -I/usr/include -I./Include -I. -I/usr/local/include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2 -c /sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_sqlite/util.c -o build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_sqlite/util.o
gcc -pthread -shared build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_sqlite/cache.o build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_sqlite/connection.o build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_sqlite/cursor.o build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_sqlite/microprotocols.o build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_sqlite/module.o build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_sqlite/prepare_protocol.o build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_sqlite/row.o build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_sqlite/statement.o build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_sqlite/util.o -L. -L/usr/local/lib -lsqlite3 -lpython3.7m -o build/lib.linux-x86_64-3.7/_sqlite3.cpython-37m-x86_64-linux-gnu.so
building '_dbm' extension
gcc -pthread -fPIC -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-use -fprofile-correction -DHAVE_GDBM_NDBM_H -I./Include -I. -I/usr/local/include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2 -c /sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_dbmmodule.c -o build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_dbmmodule.o
gcc -pthread -shared build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_dbmmodule.o -L. -L/usr/local/lib -lgdbm -lpython3.7m -o build/lib.linux-x86_64-3.7/_dbm.cpython-37m-x86_64-linux-gnu.so
building '_gdbm' extension
gcc -pthread -fPIC -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-use -fprofile-correction -I./Include -I. -I/usr/local/include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2 -c /sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_gdbmmodule.c -o build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_gdbmmodule.o
gcc -pthread -shared build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_gdbmmodule.o -L. -L/usr/local/lib -lgdbm -lpython3.7m -o build/lib.linux-x86_64-3.7/_gdbm.cpython-37m-x86_64-linux-gnu.so
building 'termios' extension
gcc -pthread -fPIC -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-use -fprofile-correction -I./Include -I. -I/usr/local/include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2 -c /sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/termios.c -o build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/termios.o
gcc -pthread -shared build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/termios.o -L. -L/usr/local/lib -lpython3.7m -o build/lib.linux-x86_64-3.7/termios.cpython-37m-x86_64-linux-gnu.so
building 'resource' extension
gcc -pthread -fPIC -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-use -fprofile-correction -I./Include -I. -I/usr/local/include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2 -c /sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/resource.c -o build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/resource.o
gcc -pthread -shared build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/resource.o -L. -L/usr/local/lib -lpython3.7m -o build/lib.linux-x86_64-3.7/resource.cpython-37m-x86_64-linux-gnu.so
building 'nis' extension
gcc -pthread -fPIC -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-use -fprofile-correction -I./Include -I. -I/usr/local/include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2 -c /sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/nismodule.c -o build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/nismodule.o
gcc -pthread -shared build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/nismodule.o -L. -L/usr/local/lib -lnsl -lpython3.7m -o build/lib.linux-x86_64-3.7/nis.cpython-37m-x86_64-linux-gnu.so
building '_curses' extension
gcc -pthread -fPIC -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-use -fprofile-correction -DHAVE_NCURSESW=1 -I/usr/include/ncursesw -I./Include -I. -I/usr/local/include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2 -c /sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_cursesmodule.c -o build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_cursesmodule.o
gcc -pthread -shared build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_cursesmodule.o -L. -L/usr/local/lib -lncursesw -lpython3.7m -o build/lib.linux-x86_64-3.7/_curses.cpython-37m-x86_64-linux-gnu.so
building '_curses_panel' extension
gcc -pthread -fPIC -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-use -fprofile-correction -DHAVE_NCURSESW=1 -I/usr/include/ncursesw -I./Include -I. -I/usr/local/include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2 -c /sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_curses_panel.c -o build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_curses_panel.o
gcc -pthread -shared build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_curses_panel.o -L. -L/usr/local/lib -lpanelw -lncursesw -lpython3.7m -o build/lib.linux-x86_64-3.7/_curses_panel.cpython-37m-x86_64-linux-gnu.so
building 'zlib' extension
gcc -pthread -fPIC -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-use -fprofile-correction -I./Include -I. -I/usr/local/include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2 -c /sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/zlibmodule.c -o build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/zlibmodule.o
gcc -pthread -shared build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/zlibmodule.o -L. -L/usr/local/lib -lz -lpython3.7m -o build/lib.linux-x86_64-3.7/zlib.cpython-37m-x86_64-linux-gnu.so
building 'binascii' extension
gcc -pthread -fPIC -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-use -fprofile-correction -I./Include -I. -I/usr/local/include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2 -c /sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/binascii.c -o build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/binascii.o -DUSE_ZLIB_CRC32
gcc -pthread -shared build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/binascii.o -L. -L/usr/local/lib -lz -lpython3.7m -o build/lib.linux-x86_64-3.7/binascii.cpython-37m-x86_64-linux-gnu.so
building '_bz2' extension
gcc -pthread -fPIC -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-use -fprofile-correction -I./Include -I. -I/usr/local/include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2 -c /sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_bz2module.c -o build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_bz2module.o
gcc -pthread -shared build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_bz2module.o -L. -L/usr/local/lib -lbz2 -lpython3.7m -o build/lib.linux-x86_64-3.7/_bz2.cpython-37m-x86_64-linux-gnu.so
building '_lzma' extension
gcc -pthread -fPIC -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-use -fprofile-correction -I./Include -I. -I/usr/local/include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2 -c /sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_lzmamodule.c -o build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_lzmamodule.o
gcc -pthread -shared build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_lzmamodule.o -L. -L/usr/local/lib -llzma -lpython3.7m -o build/lib.linux-x86_64-3.7/_lzma.cpython-37m-x86_64-linux-gnu.so
building 'pyexpat' extension
gcc -pthread -fPIC -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-use -fprofile-correction -DHAVE_EXPAT_CONFIG_H=1 -DXML_POOR_ENTROPY=1 -DUSE_PYEXPAT_CAPI -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/expat -I./Include -I. -I/usr/local/include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2 -c /sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/pyexpat.c -o build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/pyexpat.o
gcc -pthread -fPIC -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-use -fprofile-correction -DHAVE_EXPAT_CONFIG_H=1 -DXML_POOR_ENTROPY=1 -DUSE_PYEXPAT_CAPI -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/expat -I./Include -I. -I/usr/local/include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2 -c /sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/expat/xmlparse.c -o build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/expat/xmlparse.o
gcc -pthread -fPIC -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-use -fprofile-correction -DHAVE_EXPAT_CONFIG_H=1 -DXML_POOR_ENTROPY=1 -DUSE_PYEXPAT_CAPI -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/expat -I./Include -I. -I/usr/local/include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2 -c /sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/expat/xmlrole.c -o build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/expat/xmlrole.o
gcc -pthread -fPIC -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-use -fprofile-correction -DHAVE_EXPAT_CONFIG_H=1 -DXML_POOR_ENTROPY=1 -DUSE_PYEXPAT_CAPI -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/expat -I./Include -I. -I/usr/local/include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2 -c /sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/expat/xmltok.c -o build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/expat/xmltok.o
gcc -pthread -shared build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/pyexpat.o build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/expat/xmlparse.o build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/expat/xmlrole.o build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/expat/xmltok.o -L. -L/usr/local/lib -lpython3.7m -o build/lib.linux-x86_64-3.7/pyexpat.cpython-37m-x86_64-linux-gnu.so
building '_elementtree' extension
gcc -pthread -fPIC -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-use -fprofile-correction -DHAVE_EXPAT_CONFIG_H=1 -DXML_POOR_ENTROPY=1 -DUSE_PYEXPAT_CAPI -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/expat -I./Include -I. -I/usr/local/include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2 -c /sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_elementtree.c -o build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_elementtree.o
gcc -pthread -shared build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_elementtree.o -L. -L/usr/local/lib -lpython3.7m -o build/lib.linux-x86_64-3.7/_elementtree.cpython-37m-x86_64-linux-gnu.so
building '_multibytecodec' extension
gcc -pthread -fPIC -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-use -fprofile-correction -I./Include -I. -I/usr/local/include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2 -c /sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/cjkcodecs/multibytecodec.c -o build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/cjkcodecs/multibytecodec.o
gcc -pthread -shared build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/cjkcodecs/multibytecodec.o -L. -L/usr/local/lib -lpython3.7m -o build/lib.linux-x86_64-3.7/_multibytecodec.cpython-37m-x86_64-linux-gnu.so
building '_codecs_kr' extension
gcc -pthread -fPIC -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-use -fprofile-correction -I./Include -I. -I/usr/local/include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2 -c /sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/cjkcodecs/_codecs_kr.c -o build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/cjkcodecs/_codecs_kr.o
gcc -pthread -shared build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/cjkcodecs/_codecs_kr.o -L. -L/usr/local/lib -lpython3.7m -o build/lib.linux-x86_64-3.7/_codecs_kr.cpython-37m-x86_64-linux-gnu.so
building '_codecs_jp' extension
gcc -pthread -fPIC -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-use -fprofile-correction -I./Include -I. -I/usr/local/include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2 -c /sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/cjkcodecs/_codecs_jp.c -o build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/cjkcodecs/_codecs_jp.o
gcc -pthread -shared build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/cjkcodecs/_codecs_jp.o -L. -L/usr/local/lib -lpython3.7m -o build/lib.linux-x86_64-3.7/_codecs_jp.cpython-37m-x86_64-linux-gnu.so
building '_codecs_cn' extension
gcc -pthread -fPIC -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-use -fprofile-correction -I./Include -I. -I/usr/local/include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2 -c /sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/cjkcodecs/_codecs_cn.c -o build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/cjkcodecs/_codecs_cn.o
gcc -pthread -shared build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/cjkcodecs/_codecs_cn.o -L. -L/usr/local/lib -lpython3.7m -o build/lib.linux-x86_64-3.7/_codecs_cn.cpython-37m-x86_64-linux-gnu.so
building '_codecs_tw' extension
gcc -pthread -fPIC -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-use -fprofile-correction -I./Include -I. -I/usr/local/include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2 -c /sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/cjkcodecs/_codecs_tw.c -o build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/cjkcodecs/_codecs_tw.o
gcc -pthread -shared build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/cjkcodecs/_codecs_tw.o -L. -L/usr/local/lib -lpython3.7m -o build/lib.linux-x86_64-3.7/_codecs_tw.cpython-37m-x86_64-linux-gnu.so
building '_codecs_hk' extension
gcc -pthread -fPIC -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-use -fprofile-correction -I./Include -I. -I/usr/local/include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2 -c /sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/cjkcodecs/_codecs_hk.c -o build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/cjkcodecs/_codecs_hk.o
gcc -pthread -shared build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/cjkcodecs/_codecs_hk.o -L. -L/usr/local/lib -lpython3.7m -o build/lib.linux-x86_64-3.7/_codecs_hk.cpython-37m-x86_64-linux-gnu.so
building '_codecs_iso2022' extension
gcc -pthread -fPIC -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-use -fprofile-correction -I./Include -I. -I/usr/local/include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2 -c /sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/cjkcodecs/_codecs_iso2022.c -o build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/cjkcodecs/_codecs_iso2022.o
gcc -pthread -shared build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/cjkcodecs/_codecs_iso2022.o -L. -L/usr/local/lib -lpython3.7m -o build/lib.linux-x86_64-3.7/_codecs_iso2022.cpython-37m-x86_64-linux-gnu.so
building '_decimal' extension
gcc -pthread -fPIC -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-use -fprofile-correction -DCONFIG_64=1 -DASM=1 -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_decimal/libmpdec -I./Include -I. -I/usr/local/include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2 -c /sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_decimal/_decimal.c -o build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_decimal/_decimal.o
gcc -pthread -fPIC -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-use -fprofile-correction -DCONFIG_64=1 -DASM=1 -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_decimal/libmpdec -I./Include -I. -I/usr/local/include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2 -c /sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_decimal/libmpdec/basearith.c -o build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_decimal/libmpdec/basearith.o
gcc -pthread -fPIC -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-use -fprofile-correction -DCONFIG_64=1 -DASM=1 -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_decimal/libmpdec -I./Include -I. -I/usr/local/include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2 -c /sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_decimal/libmpdec/constants.c -o build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_decimal/libmpdec/constants.o
gcc -pthread -fPIC -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-use -fprofile-correction -DCONFIG_64=1 -DASM=1 -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_decimal/libmpdec -I./Include -I. -I/usr/local/include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2 -c /sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_decimal/libmpdec/context.c -o build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_decimal/libmpdec/context.o
gcc -pthread -fPIC -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-use -fprofile-correction -DCONFIG_64=1 -DASM=1 -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_decimal/libmpdec -I./Include -I. -I/usr/local/include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2 -c /sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_decimal/libmpdec/convolute.c -o build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_decimal/libmpdec/convolute.o
gcc -pthread -fPIC -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-use -fprofile-correction -DCONFIG_64=1 -DASM=1 -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_decimal/libmpdec -I./Include -I. -I/usr/local/include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2 -c /sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_decimal/libmpdec/crt.c -o build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_decimal/libmpdec/crt.o
gcc -pthread -fPIC -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-use -fprofile-correction -DCONFIG_64=1 -DASM=1 -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_decimal/libmpdec -I./Include -I. -I/usr/local/include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2 -c /sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_decimal/libmpdec/difradix2.c -o build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_decimal/libmpdec/difradix2.o
gcc -pthread -fPIC -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-use -fprofile-correction -DCONFIG_64=1 -DASM=1 -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_decimal/libmpdec -I./Include -I. -I/usr/local/include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2 -c /sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_decimal/libmpdec/fnt.c -o build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_decimal/libmpdec/fnt.o
gcc -pthread -fPIC -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-use -fprofile-correction -DCONFIG_64=1 -DASM=1 -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_decimal/libmpdec -I./Include -I. -I/usr/local/include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2 -c /sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_decimal/libmpdec/fourstep.c -o build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_decimal/libmpdec/fourstep.o
gcc -pthread -fPIC -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-use -fprofile-correction -DCONFIG_64=1 -DASM=1 -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_decimal/libmpdec -I./Include -I. -I/usr/local/include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2 -c /sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_decimal/libmpdec/io.c -o build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_decimal/libmpdec/io.o
gcc -pthread -fPIC -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-use -fprofile-correction -DCONFIG_64=1 -DASM=1 -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_decimal/libmpdec -I./Include -I. -I/usr/local/include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2 -c /sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_decimal/libmpdec/memory.c -o build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_decimal/libmpdec/memory.o
gcc -pthread -fPIC -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-use -fprofile-correction -DCONFIG_64=1 -DASM=1 -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_decimal/libmpdec -I./Include -I. -I/usr/local/include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2 -c /sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_decimal/libmpdec/mpdecimal.c -o build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_decimal/libmpdec/mpdecimal.o
gcc -pthread -fPIC -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-use -fprofile-correction -DCONFIG_64=1 -DASM=1 -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_decimal/libmpdec -I./Include -I. -I/usr/local/include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2 -c /sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_decimal/libmpdec/numbertheory.c -o build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_decimal/libmpdec/numbertheory.o
gcc -pthread -fPIC -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-use -fprofile-correction -DCONFIG_64=1 -DASM=1 -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_decimal/libmpdec -I./Include -I. -I/usr/local/include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2 -c /sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_decimal/libmpdec/sixstep.c -o build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_decimal/libmpdec/sixstep.o
gcc -pthread -fPIC -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-use -fprofile-correction -DCONFIG_64=1 -DASM=1 -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_decimal/libmpdec -I./Include -I. -I/usr/local/include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2 -c /sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_decimal/libmpdec/transpose.c -o build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_decimal/libmpdec/transpose.o
gcc -pthread -shared build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_decimal/_decimal.o build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_decimal/libmpdec/basearith.o build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_decimal/libmpdec/constants.o build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_decimal/libmpdec/context.o build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_decimal/libmpdec/convolute.o build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_decimal/libmpdec/crt.o build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_decimal/libmpdec/difradix2.o build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_decimal/libmpdec/fnt.o build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_decimal/libmpdec/fourstep.o build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_decimal/libmpdec/io.o build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_decimal/libmpdec/memory.o build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_decimal/libmpdec/mpdecimal.o build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_decimal/libmpdec/numbertheory.o build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_decimal/libmpdec/sixstep.o build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_decimal/libmpdec/transpose.o -L. -L/usr/local/lib -lm -lpython3.7m -o build/lib.linux-x86_64-3.7/_decimal.cpython-37m-x86_64-linux-gnu.so
building '_multiprocessing' extension
gcc -pthread -fPIC -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-use -fprofile-correction -IModules/_multiprocessing -I./Include -I. -I/usr/local/include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2 -c /sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_multiprocessing/multiprocessing.c -o build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_multiprocessing/multiprocessing.o
gcc -pthread -fPIC -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-use -fprofile-correction -IModules/_multiprocessing -I./Include -I. -I/usr/local/include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2 -c /sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_multiprocessing/semaphore.c -o build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_multiprocessing/semaphore.o
gcc -pthread -shared build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_multiprocessing/multiprocessing.o build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_multiprocessing/semaphore.o -L. -L/usr/local/lib -lpython3.7m -o build/lib.linux-x86_64-3.7/_multiprocessing.cpython-37m-x86_64-linux-gnu.so
building 'ossaudiodev' extension
gcc -pthread -fPIC -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-use -fprofile-correction -I./Include -I. -I/usr/local/include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2 -c /sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/ossaudiodev.c -o build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/ossaudiodev.o
gcc -pthread -shared build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/ossaudiodev.o -L. -L/usr/local/lib -lpython3.7m -o build/lib.linux-x86_64-3.7/ossaudiodev.cpython-37m-x86_64-linux-gnu.so
building '_tkinter' extension
gcc -pthread -fPIC -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-use -fprofile-correction -DWITH_APPINIT=1 -I/usr/X11/include -I./Include -I. -I/usr/local/include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2 -c /sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_tkinter.c -o build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_tkinter.o
gcc -pthread -fPIC -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-use -fprofile-correction -DWITH_APPINIT=1 -I/usr/X11/include -I./Include -I. -I/usr/local/include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2 -c /sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/tkappinit.c -o build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/tkappinit.o
gcc -pthread -shared build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_tkinter.o build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/tkappinit.o -L/usr/X11/lib -L. -L/usr/local/lib -ltk8.5 -ltcl8.5 -lX11 -lpython3.7m -o build/lib.linux-x86_64-3.7/_tkinter.cpython-37m-x86_64-linux-gnu.so
building '_uuid' extension
gcc -pthread -fPIC -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-use -fprofile-correction -I/usr/include/uuid -I./Include -I. -I/usr/local/include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2 -c /sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_uuidmodule.c -o build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_uuidmodule.o
gcc -pthread -shared build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_uuidmodule.o -L. -L/usr/local/lib -luuid -lpython3.7m -o build/lib.linux-x86_64-3.7/_uuid.cpython-37m-x86_64-linux-gnu.so
building 'xxlimited' extension
gcc -pthread -fPIC -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-use -fprofile-correction -DPy_LIMITED_API=0x03050000 -I./Include -I. -I/usr/local/include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2 -c /sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/xxlimited.c -o build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/xxlimited.o
gcc -pthread -shared build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/xxlimited.o -L. -L/usr/local/lib -lpython3.7m -o build/lib.linux-x86_64-3.7/xxlimited.cpython-37m-x86_64-linux-gnu.so
building '_ctypes' extension
gcc -pthread -fPIC -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-use -fprofile-correction -I/usr/lib64/libffi-3.0.5/include -I./Include -I. -I/usr/local/include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2 -c /sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_ctypes/_ctypes.c -o build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_ctypes/_ctypes.o
gcc -pthread -fPIC -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-use -fprofile-correction -I/usr/lib64/libffi-3.0.5/include -I./Include -I. -I/usr/local/include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2 -c /sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_ctypes/callbacks.c -o build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_ctypes/callbacks.o
gcc -pthread -fPIC -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-use -fprofile-correction -I/usr/lib64/libffi-3.0.5/include -I./Include -I. -I/usr/local/include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2 -c /sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_ctypes/callproc.c -o build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_ctypes/callproc.o
gcc -pthread -fPIC -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-use -fprofile-correction -I/usr/lib64/libffi-3.0.5/include -I./Include -I. -I/usr/local/include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2 -c /sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_ctypes/stgdict.c -o build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_ctypes/stgdict.o
gcc -pthread -fPIC -Wno-unused-result -Wsign-compare -DNDEBUG -g -fwrapv -O3 -Wall -std=c99 -Wextra -Wno-unused-result -Wno-unused-parameter -Wno-missing-field-initializers -Werror=implicit-function-declaration -fprofile-use -fprofile-correction -I/usr/lib64/libffi-3.0.5/include -I./Include -I. -I/usr/local/include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Include -I/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2 -c /sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_ctypes/cfield.c -o build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_ctypes/cfield.o
gcc -pthread -shared build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_ctypes/_ctypes.o build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_ctypes/callbacks.o build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_ctypes/callproc.o build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_ctypes/stgdict.o build/temp.linux-x86_64-3.7/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Modules/_ctypes/cfield.o -L. -L/usr/local/lib -lffi -ldl -lpython3.7m -o build/lib.linux-x86_64-3.7/_ctypes.cpython-37m-x86_64-linux-gnu.so

Python build finished successfully!
The necessary bits to build these optional modules were not found:
_ssl                                                           
To find the necessary bits, look in setup.py in detect_modules() for the module's name.


The following modules found by detect_modules() in setup.py, have been
built by the Makefile instead, as configured by the Setup files:
_abc                  atexit                pwd                
time                                                           


Could not build the ssl module!
Python requires an OpenSSL 1.0.2 or 1.1 compatible libssl with X509_VERIFY_PARAM_set1_host().
LibreSSL 2.6.4 and earlier do not provide the necessary APIs, https://github.com/libressl-portable/portable/issues/381

running build_scripts
copying and adjusting /sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Tools/scripts/pydoc3 -> build/scripts-3.7
copying and adjusting /sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Tools/scripts/idle3 -> build/scripts-3.7
copying and adjusting /sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Tools/scripts/2to3 -> build/scripts-3.7
copying and adjusting /sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2/Tools/scripts/pyvenv -> build/scripts-3.7
changing mode of build/scripts-3.7/pydoc3 from 644 to 755
changing mode of build/scripts-3.7/idle3 from 644 to 755
changing mode of build/scripts-3.7/2to3 from 644 to 755
changing mode of build/scripts-3.7/pyvenv from 644 to 755
renaming build/scripts-3.7/pydoc3 to build/scripts-3.7/pydoc3.7
renaming build/scripts-3.7/idle3 to build/scripts-3.7/idle3.7
renaming build/scripts-3.7/2to3 to build/scripts-3.7/2to3-3.7
renaming build/scripts-3.7/pyvenv to build/scripts-3.7/pyvenv-3.7
make[1]: Leaving directory `/sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2'
gail01@login1: /sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2 $ ssh data2
ssh_exchange_identification: Connection closed by remote host
gail01@login1: /sc/orga/packages/lili_tem/pkg/python/src/Python-3.7.2 $ cd
gail01@login1: ~ $ cd /
gail01@login1: / $ cd
gail01@login1: ~ $ cd /hpc/users/xestebr01/
-bash: cd: /hpc/users/xestebr01/: Permission denied
gail01@login1: ~ $ finger xestebr01
Login: xestebr01      			Name: Roger Esteban
Directory: /hpc/users/xestebr01     	Shell: /bin/bash
Never logged in.
No mail.
No Plan.
gail01@login1: ~ $ id xestebr01
uid=23548(xestebr01) gid=31052(llovej01a) groups=31052(llovej01a),20001(disabled)
gail01@login1: ~ $ id llovej01
uid=22327(llovej01) gid=31052(llovej01a) groups=31052(llovej01a),20001(disabled)
gail01@login1: ~ $ Shared connection to mothra.hpc.mssm.edu closed.
imac:~ gail01$ ssh mothra
Last login: Wed Jan 16 09:33:33 2019 from 10.91.17.183
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
	The /sc/orga/ file system is optimized for performance and
	capacity. It provides minimal redundancy and no backups.

	Data stored in /sc/orga/scratch/ is automatically purged after
	14 days.

	===    Follow us on Twitter @mssmhpc    ===
    === Send ticket to hpchelp@hpc.mssm.edu ===
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

gail01@login1: ~ $ sudo su -
[sudo] password for gail01: 
[root@login1 ~]# cd /sc/orga/projects/
[root@login1 projects]# ls | wc -l
255
[root@login1 projects]# cd
[root@login1 ~]# cd /hpc/users/
[root@login1 users]# ls | wc -l
1914
[root@login1 users]# ls
abulhn01  breenm01      degrae01  ghiraf01    hpctrn07  killia01   lotayv01           nazari01       rahmas14  sharma16       timsip01   woodeb01   xefthya01  xlaia01      xroubyn01  xwraya01
ackeic01  brennk02      deikug01  giambc02    hpctrn08  kimj101    lsf_drmaa_monitor  neffr01        rahmat03  sharma18       tinm01     woods01    xellios03  xlangsh01    xrubinj01  xxbattua01
aggara01  bresse01      delgaa07  gibsow02    hpctrn09  kimj108    lubina02           negria01       rajarp01  sharmr06       tlowry01   wooy01     xerjavs01  xlaverk01    xruderd01  xxgai
aggarv01  brohla01      deligc01  gilesz01    hpctrn10  kimj77     ludtka01           nekrie01       rajt01    sharpa01       tolbet01   wuh09      xespes10   xleea01      xrupark01  xxiny01
aguadl01  browna16      deliom01  gillc02     hpctrn11  kimr05     luh05              nelsom15       ramaka02  shay01         tomall01   wum03      xestebr01  xleee01      xryzas01   xxuhan01
agulle01  bruzee01      devchp01  giovaa02    hpctrn12  kimy25     luim02             newmal02       ramasr02  sheckm01       tomegj01   wuq01      xestrak01  xleej01      xsaboa01   xxxing
ahmedm20  bubiea01      dhamom01  girars03    hpctrn13  kinres01   lukato01           ngenes01       ramdhs05  shenbs02       topola01   wuw03      xevansk01  xleersf01    xsaintm01  xyangb01
ahujaa01  buk02         dhawan01  girdhk01    hpctrn14  kirkpe02   lukk01             ngj05          ramesm01  shenl03        torrej14   wuy21      xfanx01    xlees01      xsamock01  xyangh01
akersn01  bunshs01      diazg02   girim01     hpctrn15  kleinr08   lukszm01           nguyed01       ramses01  shenn01        torrel18   xabbots01  xfengz02   xlewisc01    xsandes01  xyangx01
aklerg01  bunyas02      dichij01  glickb01    hpctrn16  kobror01   luow01             nguyet26       raneap01  shenq01        torres25   xabdela01  xfinley01  xlewisl01    xsanjoj01  xyeem01
akpoyd02  burosj01      digioj01  glickl02    hpctrn17  kocay01    lux02              nicolg03       rashkm01  shervm01       touraa01   xadamsl01  xfished01  xlewism01    xsankal01  xyeemu01
aksoyb01  buttss01      dinara01  goa02       hpctrn18  kodysy01   luy05              nicolk01       rasooa02  shil01         tsankn01   xadaptive  xfontem01  xliaow01     xsarkaa01  xyenm01
alabis01  bxbadmin      dincea01  godina03    hpctrn19  koganl01   maa06              nicolp01       ravinn01  shil02         tsedeo01   xahsans01  xforouh01  xlih01       xsatot01   xyoungd01
alberz01  byunm01       dincez01  goela03     hpctrn20  koha01     macks01            niestd01       readhb01  shimj05        tsengj01   xahsenm01  xfosteg01  xlij01       xsattek01  xyounkc01
alfret01  caig01        dingw01   goffp01     hpctrn21  kohlis02   maffup01           nim01          reala01   siad01         tumins01   xakersn01  xfranzo01  xlij02       xsawyea01  xyum01
alir02    caij03        divara01  gofft01     hpctrn22  kojimk01   mahajm02           ningk01        rechko01  siddio01       tungn02    xakhunj01  xfrouds01  xlime01      xsaylor01  xyut01
alletk01  caix01        doa03     gokhaa02    hpctrn23  kollj01    mahjab01           nistad01       reedd02   sidhwn01       tut01      xalberz01  xfua01     xlindem01    xschafc01  xzafers01
alperj02  calder05      dobbya01  goldba06    hpctrn24  kongy02    mahobv01           nithym01       reisss01  siehw01        tuz01      xalexan01  xfuccis01  xlingw01     xschaft01  xzaitln01
althas01  calina01      dohlma01  goldee07    hpctrn25  koples01   maiaa01            noelj02        rejaj01   signam01       tylers01   xalir01    xfuertd01  xliup01      xschilb01  xzaranm01
altmad01  callej03      dongm01   goldj04     hpctrn26  koppos03   mais01             norbua01       renaut01  signer01       udinee01   xallinn01  xfurins01  xlius01      xschmik01  xzaslam01
altmaj04  calvic01      dongp01   goldsd07    hpctrn27  kornrr01   makarv02           novikg01       renc03    simchn01       umalim01   xalnefr01  xfus01     xliy01       xschulw01  xzengh01
amire01   campac03      donovm01  goldsr09    hpctrn28  kosoyr01   mal06              ntrana01       rendlm01  simonj09       ummata01   xalthas01  xgaitec01  xliyan01     xschwab01  xzhangb01
anderj05  campbj04      dor01     gomesa01    hpctrn29  kouy01     malakp01           nudelg01       rentoa01  simonk04       ungarr01   xamire01   xganell01  xliz01       xscottc01  xzhange01
andraj03  caol02        doradr01  gomezm12    hpctrn30  kovatp01   malhoj02           odgisj01       restrp01  singhm14       ungerh01   xanj01     xgarref01  xlochol01    xscotte01  xzhangj01
andram02  carcas01      douceg01  gomezy02    hpctrn31  kozlea01   malikr02           odonnt02       revab01   singhs31       ungp01     xantone01  xgettlk01  xlopest01    xseedon01  xzhangj02
andres12  carped01      doupep01  gongj04     hpctrn32  kravij02   mallaa01           oemkeh01       reyesf07  sinhar02       upadhr03   xartemy01  xghedie01  xlozadv01    xselvan01  xzhangw01
angiok01  carrer04      drachs01  gonzaa51    hpctrn33  kreka01    mallel01           oermae01       rialda01  sklarp01       Urbanm03   xarwoom01  xgiambc01  xlozam01     xshemir01  xzhangz01
anguiv01  carrj05       duanq01   gonzae34    hpctrn34  kritid01   malont03           oguntk01       richtf01  skogan01       uregen     xawada01   xgibbsr01  xluc01       xshij01    xzhangz02
antipy01  caster03      dudlej01  gopalk01    hpctrn35  krittc01   mam02              ohagar01       rideoj01  slivik01       uziloa01   xawada02   xgidwav01  xlussis01    xshins01   xzhaoz01
apontp04  castrk02      duehrj01  gopins03    hpctrn36  kronmh01   mandem05           ohallr01       rjh       sloofl01       valled02   xbacked01  xgignoc01  xmaldoh01    xshulgy01  xzhuk01
arferk01  catesh01      duffya02  gosseg01    hpctrn37  kud01      manoor01           ohanlr01       roberm20  smielm01       vanbah01   xbaekj01   xgilesz01  xmanthc01    xshuros01  xzhus01
argmac01  celebjadmin   dumad01   gowdas01    huanga16  kuffnr01   maoq01             oishik01       rocheg01  smithg17       vanbah01b  xbaerj01   xgilln01   xmaoq01      xsiad01    xzhuy01
argylj01  chackk02      dunkee01  granta06    huangj14  kulkak01   maramb01           olivep05       rockai01  smithm19       vanded03   xbakerc01  xgilsom01  xmarchm01    xsieber01  xzwickm01
arifm01   chadwb01      dunnij02  graye03     huangk04  kumara22   marchm04           onoa01         rodrio10  smithm49       vanvlt02   xbalasp01  xgiovaa01  xmariag01    xsieberts  yacour01
aroras03  chamin01      eamesa01  greenb08    huangk05  kundam01   marcoe02           oredet01       rodriy04  smithm56       varang01   xballk01   xgoeln01   xmarinb01    xsiebes01  yadawa01
attieo02  chana16       edelml02  grigod01    huangl11  kundup01   mariaj01           ormelp01       romanc10  smithr21       vardac01   xbankis01  xgoldmj01  xmarkoy01    xsinght01  yangb04
aushev01  chandd05      edward08  griswr01    huangt03  kuop01     marinb02           ortizd10       rompag01  smiths19       varshm01   xbarnar01  xgoldsj01  xmartia01    xsiskr01   yangc07
autull01  chands10      edwarj06  grossy02    huangx03  kurowa01   marink03           osmanr01       rosenb16  sneebm01       vasqur02   xbarnej01  xgoldso01  xmartic01    xsmiths01  yangc10
awada03   changc22      efthya01  groutj01    huckil01  kuzina01   marlob01           overbj01       rosenc07  soensz01       vastav01   xbaronr01  xgoulde01  xmartij01    xsorekm01  yangj10
ayatap01  change07      egervg01  grovek01    huj03     kwony04    martia68           overci01       roses07   solova02       vasudh01   xbarrej01  xgreenm01  xmasonc01    xsorenm01  yangj19
aydini01  changl06      egoron01  grubec05    hungm03   lagana01   martij47           ozbeku01       rossj01   somans04       vatans01   xbaskam01  xgreenm02  xmauram01    xsoroke01  yangj21
ayersk02  changr04      ejebek01  guisek01    huopai01  lagdaa01   martim64           ozteks05       rossm14   sonars01       vaydyy01   xbassal01  xgriffe01  xmccalk01    xstahle01  yangy10
azeloe02  chaom02       eldibm01  guixar01    hutchk02  laitmb01   martip03           padorf01       rothsj06  songb01        vcell      xbeaulj01  xguest1    xmcdont01    xstanea01  yangy13
bachik01  chaom03       elfmah01  gulyaa01    hux05     lalas01    martip11           paisac01       rothy04   songq01        veigaa01   xbendlj01  xguest2    xmcdont02    xstefam01  yaoq01
badgem01  chapec01      ellios03  gumusz01    huz04     lals02     martit26           pakt01         roussp01  songr01        venkaa02   xberism01  xgunnac01  xmelasm01    xstojma01  yarraa01
bailem04  charna02      ellise04  guob01      ilgd01    lamare01   matheb04           palcut01       rovinn01  songw01        verbam01   xbernsr01  xhac01     xmendof01    xstrizd01  yazdaa02
baiy02    charyd03      ellisk05  guoh01      ioelen01  lambel02   mathud01           pandeg01       royb01    songx04        vermag01   xberrim01  xhaerts01  xmetzk01     xsulj01    ychan01
bakerr05  charym01      ellisr05  guol03      ipm       lamd03     maw01              pandeo01       rozehj01  sosune01       verstr01   xbigdet01  xhajiri01  xmezj01      xsullip01  yef01
balka01   chattz01      elmenm01  guot01      iqbalr01  landrj01   may08              pandyc01       rozenl02  sotilc01       viallr01   xbilgib01  xhalent01  xmichot01    xsundab01  yemela01
baox01    chatzc01      elyb01    guox07      irizaa03  landyk01   mayouj01           parani01       ruand01   soultg01       vijg01     xbisigp01  xhana01    xmighet01    xsunj01    yingk01
barakd01  chaudk03      emerym01  guptai05    ishikk01  lardnc01   mazurs01           parikj03       rubena05  space_010713   villaa06   xblancj01  xhaqz01    xmilekm01    xtalkom01  yinx02
barbiv02  chavai01      enelp01   guptas15    iversa01  larocm01   mcbrir01           parkd04        rubina07  space_010813   villaj16   xblazej01  xharrir01  xmillec01    xtalukh01  yips01
barbom04  chdi          eortiz01  guptay01    jabado01  laseru01   mccafj01           parkhe02       ruderd02  space_011412   villan05   xboocoj01  xharta01   xmillec02    xtamayj01  yiz01
barc01    chenb07       eppsp01   gux01       jacobm07  lashbn01   mcclea02           parksm03       rum01     space_011413   vincea01   xborchv01  xhartmr01  xmillej01    xtangm01   yongr01
barnej12  chenga08      erenam01  hadasy01    jadhab01  lauc05     mcfadw01           parray01       rumbet01  space_021313   vingec01   xbotb01    xhaubem01  xmitras01    xtartaf01  yoos01
barrea04  chengh04      escobh01  hadjie01    jaina09   lauk06     mcgree01           parsonsadmin   rupank01  space_043013   vishna01   xbrocks01  xhawkej01  xmolinr01    xtcwj01    youngh02
barrod02  chengk06      espes10   hagenj02    jainr04   laviny02   mckena01           pasara01       rushj03   space_050813   voloug01   xbrownm01  xhawrim01  xmonasc01    xteerj01   youngj01
barroj02  chengw04      evrong01  haghif01    jaiswm01  leadea02   mckenc01           patela59       rutlaj02  space_102312   vonfej01   xbuddej01  xhayesj01  xmonror01    xteless01  yuany04
bartem01  chenj02admin  faithj02  hahnen01    jajamg01  lebovd02   mclela02           pateln35       ruy01     space_110112   voraa02    xbuysks01  xheftim01  xmontar01    xtendea01  yuany05
bashia02  chenj56       falcec01  hajjam01    janird01  leee19     meachc01           pateln54       rykund01  space_110112b  voras01    xcahilm01  xheissj01  xmoorec01    xthakub01  yuej01
battig01  chenl16       fangg03   hakenj01    jansss01  leei05     meade01            patelr67       sabinj01  spagna01       vyt01      xcalhoj01  xhenrim01  xmoortm01    xthirih01  yuh04
baxtem01  chenl36       farrek04  halent01    jeffj01   leej102    meadep02           patels73       sachir01  spasia01       waghra01   xcalisj01  xheoj01    xmorall01    xthomap01  yuj07
bayray01  chenla01      fazla01   hallj13     jensea04  leej56     meckek01           pavela01       sachsd01  sperbs01       walked07   xcalizr01  xhillh01   xmoralm01    xthorns01  yum14
bazine01  chenq06       fazlom01  hamamt01    jhunk01   leej96     medav01            peiw02         sadlek01  spivaj01       walked18   xcampbn01  xhillr01   xmorari01    xtomasm01  yut05
beaulj01  chenr02       fedica01  hameeu01    jiangb01  leew07     meeluo01           penac05        safaib01  sprooe01       walker05   xcanesp01  xhirsch01  xmoreii01    xtomera01  zamojm01
beckfc03  chenx08       fehrt01   hammej03    jiangd03  leey05     melned01           pendlm02       saidio01  sridhs01       wallad07   xcardea01  xhochbs01  xmorrid01    xtorozj01  zaretl02
beckmn01  chessa01      feldmr03  hamouw01    jiangy04  leitnd01   menaga01           pendsj01       saiotc01  srinir01       wallar04   xcarmis01  xhodosr01  xmulqur01    xtorres10  zaslae01
bedoue01  chetnk02      fengr01   hand10      jij03     lem04      mendek02           pengp01        sakaiy02  stahle01       wanga15    xcarnes01  xhofmao01  xmurill02    xtsaie01   zaslam01
belbig01  cheunk02      fengx02   hande01     jinx03    lennes01   merald01           pengs02        salemc02  stalbl01       wange13    xcaster01  xholmea01  xmurraj01    xtsujij01  zatorn01
bella05   chewy01       fengz02   hanksj01    jjebak01  lessec02   meretd01           pengs03        saloma03  stanea01       wangh11    xceckho01  xhorowm01  xmuzzim01    xturner01  zawarn01
belmoj01  chiand01      fengz03   hann02      johnsa44  levanr01   meslaj01           peralz01       saluzj01  stanga01       wangj08    xcedenr01  xhorown01  xnadkag01    xtwadda01  zeidn01
bendea04  chikim01      fenour01  hanne01     johnsj12  levinm08   mezeim01           perchb01       sanchc14  starnm01       wangj27    xchahrm01  xhuanga01  xnatsuk01    xuc04      zeinej01
bendlj01  chiup04       fernah04  hansej01    johnsj20  liangr01   micchm01           perezj23       sanche11  steinn04       wangj33    xchange01  xhuango01  xnealeb01    xuem01     zelenz01
benita01  choh07        fernan10  hansor03    johnsk26  liaoj02    middhm01           perrec01       sanchr05  sterna07       wangjm01   xchanm01   xhuangt01  xneffr01     xuj09      zengl04
benjab02  choj07        fettiv01  haok01      jonesd30  liebea02   mierlj01           perroj02       sandes03  sterne03       wangl20    xchaoa01   xhuangy01  xnelsol01    xuk02      zhangb02
benoi01   chowds14      fialae01  harak01     jordad05  lih16      millem14           perumd01       sandis01  stingj01       wangl35    xchapmb01  xhuz01     xnguyet01    xumalim01  zhangb03
berges03  chriss09      fieldr01  harchs01    josept02  liharl02   mincej01           pessij01       sarape01  stockj03       wangm05    xchenc01   xiae01     xnisloc01    xummata01  zhangb06
berrim02  chudna01      fierrl01  haronh01    joshir01  lij27      minerg01           peteri02       sarpok01  stoken01       wangm08    xchengw01  xiaog03    xnorthb01    xundie01   zhangc09
bertes01  chungc03      filipd02  harouv01    jubiel01  lij41      mingc02            peterj09       satot01   stolog01       wangq04    xchenk01   xic01      xobergm01    xurlij01   zhangd04
bestj03   chungj15      filizm02  hartlb02    jungs04   lij43      miottr01           peterl02       savicr01  strahm01       wangs16    xchenk02   xiglesa03  xobrien01    xux03      zhangf03
beyleg01  chuny02       finnij01  hassis01    jurczd01  lil08      mirmir01           petraf01       saxenn02  streen01       wangv02    xcheny01   xiongy01   xoperations  xux06      zhangg02
bianb01   ciferb02      fiorev01  hassod01    justa01   lilil01    misirr01           phaml01        sbsuser   strubt01       wangw14    xchetnk01  xioniti01  xormelp01    xvallic01  zhangj14
bicakm01  clarke16      flahee01  heaton01    kajid02   limj10     mitcha03           pinnen01       scarpj01  suarem08       wangx12    xchiar01   xiqbaln01  xortizn01    xvanara01  zhangj21
bichok01  clemej05      flanic02  heflim01    kajiwy01  limr09     mitikn01           pintod02       schade01  subras01       wangy27    xchinc01   xirizaa01  xortizv01    xvanvlt01  zhangj37
bicksl01  codye01       fleysl01  heftim01    kakkas01  linanm01   mitoy01            pintod02b      schafa01  suckis01       wangy33    xchron01   xjaegee01  xosetib01    xvardab01  zhangq04
biosoft   codyn01       fludee01  heissj01    kalatm01  lindem03   mmedsadmin         pirase01       schafm03  suebsc01       wangy34    xchungd01  xjamesc01  xpandeo01    xvarghb01  zhangt09
bircha02  cohaia01      forrei01  hej03       kalays01  lings01    moccig01           pisanl01       schana02  suerf01        wangy42    xciceka01  xjamesj01  xparanm01    xvasila01  zhangw09
birnbr02  cohena22      forstc01  hemerd01    kangm04   linh10     moea01             planua01       schenl01  suhlj01        wangy46    xclarkl01  xjanusa01  xparets01    xvatans01  zhangw17
birsoo01  cohenp05      fradei01  henrim02    kangs06   linh11     moeins01           plazaa01       schicu01  sullim11       wangz10    xclemej01  xjeffj01   xparkd01     xvenkaa01  zhangy21
birtwm03  colasc01      francn05  heo         kanish01  linj31     moellr01           pochis01       schifl05  sunx06         wangz16    xcohens01  xjink01    xparkda01    xvertoe01  zhangy22
bishod01  comelp01      franzj02  hermam02    kanjis01  linl04     mognoi01           podrak01       schilb03  suny04         wangz18    xcoonh01   xjoehar01  xpendlm01    xvillac01  zhangz05
bishts01  connea02      franzo01  hernam07    kapooa03  linw02     momohc01           poisnh01       schlea02  sunz01         wanh01     xcoopr01   xjohnj01   xpereic01    xvipram01  zhaoc03
bisigp01  contie01      frasca01  hernam13    kapoom02  liq05      monacr01           poultc01       schnas02  sunz03         warbup01   xcorneb01  xjohns01   xpereza01    xwahln01   zhaoe02
blakej02  cooka01       freemt01  herzol02    kappim01  lis07      mondes02           powelj03       schnes03  sunz04         watanh02   xcutled01  xjohnsk01  xperrij01    xwaller01  zhaon03
blancd05  corke01       freyna01  hew04       karake01  liub06     montar06           powels12       schnet05  suprum01       watsoc04   xdalym01   xjohnsm01  xpessij01    xwalsha01  zhaot02
blassa02  correj04      fribom01  hey06       karmam01  liuc06     montec08           pradad01       schote02  swithk01       weathc03   xdangk01   xjosepg01  xpeterd01    xwangd01   zhaow05
blazej02  costaa03      fricka01  hirsch03    karris01  liuh09     moonj05            prasem02       schram02  szalue01       webbb02    xdayam01   xjosepv01  xpinyor01    xwange01   zhaoy04
blisse01  cotea02       fricka02  hitzej01    karrj02   liuj20     morgak06           prastm01       schron01  szutoh01       webste01   xdayanm01  xkaewes01  xpollaj01    xwangeg01  zhaoy06
blooml03  craiga02      friedr05  hochbs04    kasaiy01  liuj21     mortha01           pratht02       schurc01  tadays01       weic04     xdeank01   xkaisek01  xpradad01    xwangl01   zhenga07
bobod01   craryj01      fromem03  hodesg02    kasara03  liup01     moscaa04           preusm01       scott     taih02         weig01     xdelawr01  xkalemo01  xpulkia01    xwangs01   zhoul07
bockm02   crokem02      frouds01  hodesi01    kaspes01  liuq08     moserd02           provad01       scotte09  takaby01       weinse01   xdellwm01  xkamdap01  xpullmb01    xwangsv01  zhour02
bogund01  crootd02      fstkcy01  hodosr01    kastur01  liux07     moshkn01           psychgenadmin  scottr05  takiks01       weismj01   xdemira01  xkaniak01  xqualka01    xwangy01   zhoux05
bogyok01  crosbk01      fuchst02  hoffmg01    katsyi01  liuy22     moy03              psyencd        scotts06  tamayj01       weissy03   xdenysl01  xkarteh01  xquinna01    xwebbb01   zhoux07
bongeg01  croxsp01      fujiwn01  hogstb01    katzs04   liuy29     muelll04           pul01          sebrar01  tambus01       wengeb01   xdingt01   xkartet01  xraghud01    xweil01    zhouy11
bonife01  crumim01      fullej02  holeha01    kavand01  liw10      mukhek03           puljum01       seidea02  tana06         wenris02   xdoanr01   xkavand01  xrajadj01    xweili01   zhuj05
borgej01  cuesta02      fultob01  holmeg02    keathr03  lix13      mulhem02           purces04       sevimc01  tangj15        whales02   xdobrir01  xkemptm01  xrajadp01    xweix01    zhuk01
borisc01  cullis01      fultob02  holtj02     keelij01  lizned01   mullin04           purusi01       sewdaa01  tangm05        whippm01   xdongp01   xkernss01  xrajagd01    xwengz01   zhuq01
bornsv01  cummim03      fus03     homanp03    keenaa01  llewes02   munizl02           putzeg01       shaabs01  tanq02         whitek04   xdongr01   xkhano01   xrajagv01    xwerlid01  zhus02
borree01  cunhal01      gagnej01  horgue01    keiseb01  loadadmin  muppis01           qadeez01       shabmr01  tartaf01       wickrn01   xdongs01   xkiflem01  xramaka03    xwhales01  zhut02
borrej02  daix01        gail01    hos04       kendas03  logank02   murill02           qiant02        shaham03  tavarr03       wiener02   xdormam01  xkimal01   xreddyj01    xwhitek01  zhux02
boscha01  damatc02      galarg02  hoshiy01    kenige01  loginw01   muzzim01           qiant03        shahc03   tchanb01       wilkk01    xdouy01    xkims01    xreddyt01    xwiessg01  zhuy02
bottom01  daniem06      garcim48  houldj01    kennye02  lohy01     myerse05           qiaow02        shahh06   tcwj01         willir31   xdoylec01  xkizerj01  xreicha01    xwillee01  zilvea01
bouham01  daniem14      gargp01   hoyr01      kentb03   longj01    nabeei01           quilej01       shaikr01  tenoeb01       wilsoz02   xduartl01  xkleib01   xripkes01    xwillil01  zlatav01
bowenm02  dara02        garibr01  hpctrain01  kerena01  longq01    nadukr01           quinne02       shaiks05  tessec02       wisotr01   xduchop01  xkloogi01  xritza01     xwillsj01  zwakat01
bowlek01  daskan01      gelbb01   hpctrn01    kernss01  longr01    naikh01            rabinr03       shaken01  thakub01       woldeb02   xduenah01  xkonigi01  xroberm01    xwingot01
bozm01    datti01       gellej01  hpctrn02    kerrk01   loog01     naresr01           radua01        shand01   thakub02       woldes01   xdumenl01  xkosmij01  xrodrim01    xwojcig01
brandt02  davea04       gettlk01  hpctrn03    keydai01  loosr01    nas01              rahaws01       shangj01  thangg01       wonge05    xdurrer01  xkoumal01  xrodrio01    xwongg01
brandt04  davilm04      gex04     hpctrn04    khades02  lopesk01   nathad02           rahima08       shangy02  thapar02       wongg05    xeddyj01   xkumarr01  xroitms01    xwontas01
branford  decarm02      gey01     hpctrn05    khanw02   Lorscz01   navarc03           rahmaa06       shaon01   thompt09       wongz01    xedward01  xkuzmaa01  xrosofh01    xwoodm01
breenk01  defeln01      ghimbs01  hpctrn06    kiddb01   losicb01   navare04           rahmar04       shapim04  thumf01        wonh01     xefstae01  xkwanj01   xrossj01     xwoods01
[root@login1 users]# vi /sc/orga/projects/zhangw09a/Data/Zeguo_Sun/project/4.Retron/7.De_novo/3.Run/SC_2/Test/test.sh
[root@login1 users]# cd sunz0
sunz01/ sunz03/ sunz04/ 
[root@login1 users]# cd sunz0
sunz01/ sunz03/ sunz04/ 
[root@login1 users]# cd sunz0
-bash: cd: sunz0: No such file or directory
[root@login1 users]# finger sunz04
Login: sunz04         			Name: Zeguo Sun
Directory: /hpc/users/sunz04        	Shell: /bin/bash
Never logged in.
No mail.
No Plan.
[root@login1 users]# su - sunz04
sunz04@login1 ~ $ 

sunz04@login1 ~ $ 
cd /sc/orga/projects/zhangw09a/Data/Zeguo_Sun/project/4.Retron/7.De_novo/3.Run/SC_2/Test/
sunz04@login1 /sc/orga/projects/zhangw09a/Data/Zeguo_Sun/project/4.Retron/7.De_novo/3.Run/SC_2/Test $ 
ls
example  test.sh
sunz04@login1 /sc/orga/projects/zhangw09a/Data/Zeguo_Sun/project/4.Retron/7.De_novo/3.Run/SC_2/Test $ 
module list
No Modulefiles Currently Loaded.
sunz04@login1 /sc/orga/projects/zhangw09a/Data/Zeguo_Sun/project/4.Retron/7.De_novo/3.Run/SC_2/Test $ 
module load python/3.6.2
sunz04@login1 /sc/orga/projects/zhangw09a/Data/Zeguo_Sun/project/4.Retron/7.De_novo/3.Run/SC_2/Test $ 
module load py_packages/3.6
sunz04@login1 /sc/orga/projects/zhangw09a/Data/Zeguo_Sun/project/4.Retron/7.De_novo/3.Run/SC_2/Test $ 
ls
example  test.sh
sunz04@login1 /sc/orga/projects/zhangw09a/Data/Zeguo_Sun/project/4.Retron/7.De_novo/3.Run/SC_2/Test $ 
vi test.sh 
sunz04@login1 /sc/orga/projects/zhangw09a/Data/Zeguo_Sun/project/4.Retron/7.De_novo/3.Run/SC_2/Test $ 
module list
Currently Loaded Modulefiles:
  1) python/3.6.2                    3) mpfr/3.1.2                      5) gcc/4.8.2                       7) hdf5/1.8.12-serial              9) py_packages/3.6
  2) gmp/5.1.3                       4) mpc/1.0.2                       6) intel/parallel_studio_xe_2018   8) zlib/1.2.8
sunz04@login1 /sc/orga/projects/zhangw09a/Data/Zeguo_Sun/project/4.Retron/7.De_novo/3.Run/SC_2/Test $ 
module load kallisto
sunz04@login1 /sc/orga/projects/zhangw09a/Data/Zeguo_Sun/project/4.Retron/7.De_novo/3.Run/SC_2/Test $ 
vi test.sh 
sunz04@login1 /sc/orga/projects/zhangw09a/Data/Zeguo_Sun/project/4.Retron/7.De_novo/3.Run/SC_2/Test $ 
sircel --threads 32 \
>         --output_dir example \
>         --reads /sc/orga/projects/zhangw09a/PANDA/ext_ZS/bin/sircel/sircel/example/SRR1873277_1m_r2.fastq.gz \
>         --barcodes /sc/orga/projects/zhangw09a/PANDA/ext_ZS/bin/sircel/sircel/example/SRR1873277_1m_r1.fastq.gz
^CTraceback (most recent call last):
  File "/hpc/packages/minerva-common/py_packages/3.6/bin/sircel", line 11, in <module>
    load_entry_point('sircel==0.1.2', 'console_scripts', 'sircel')()
  File "/hpc/packages/minerva-common/python/3.6.2/lib/python3.6/site-packages/pkg_resources/__init__.py", line 572, in load_entry_point
    return get_distribution(dist).load_entry_point(group, name)
  File "/hpc/packages/minerva-common/python/3.6.2/lib/python3.6/site-packages/pkg_resources/__init__.py", line 2769, in load_entry_point
    return ep.load()
  File "/hpc/packages/minerva-common/python/3.6.2/lib/python3.6/site-packages/pkg_resources/__init__.py", line 2422, in load
    return self.resolve()
  File "/hpc/packages/minerva-common/python/3.6.2/lib/python3.6/site-packages/pkg_resources/__init__.py", line 2428, in resolve
    module = __import__(self.module_name, fromlist=['__name__'], level=0)
  File "/hpc/packages/minerva-common/py_packages/3.6/lib/python3.6/site-packages/sircel-0.1.2-py3.6.egg/sircel/__init__.py", line 1, in <module>
    from sircel.Sircel_master import get_args, run_all
  File "/hpc/packages/minerva-common/py_packages/3.6/lib/python3.6/site-packages/sircel-0.1.2-py3.6.egg/sircel/Sircel_master.py", line 8, in <module>
    from sircel import Split_reads
  File "/hpc/packages/minerva-common/py_packages/3.6/lib/python3.6/site-packages/sircel-0.1.2-py3.6.egg/sircel/Split_reads.py", line 32, in <module>
    from scipy import signal
  File "/hpc/packages/minerva-common/py_packages/3.6/lib/python3.6/site-packages/scipy/signal/__init__.py", line 321, in <module>
    from .filter_design import *
  File "/hpc/packages/minerva-common/py_packages/3.6/lib/python3.6/site-packages/scipy/signal/filter_design.py", line 18, in <module>
    from scipy import special, optimize, fftpack
  File "/hpc/packages/minerva-common/py_packages/3.6/lib/python3.6/site-packages/scipy/optimize/__init__.py", line 281, in <module>
    from ._basinhopping import basinhopping
  File "<frozen importlib._bootstrap>", line 961, in _find_and_load
  File "<frozen importlib._bootstrap>", line 950, in _find_and_load_unlocked
  File "<frozen importlib._bootstrap>", line 655, in _load_unlocked
  File "<frozen importlib._bootstrap_external>", line 674, in exec_module
  File "<frozen importlib._bootstrap_external>", line 764, in get_code
  File "<frozen importlib._bootstrap_external>", line 832, in get_data
KeyboardInterrupt
sunz04@login1 /sc/orga/projects/zhangw09a/Data/Zeguo_Sun/project/4.Retron/7.De_novo/3.Run/SC_2/Test $ 
^C
sunz04@login1 /sc/orga/projects/zhangw09a/Data/Zeguo_Sun/project/4.Retron/7.De_novo/3.Run/SC_2/Test $ 
^C
sunz04@login1 /sc/orga/projects/zhangw09a/Data/Zeguo_Sun/project/4.Retron/7.De_novo/3.Run/SC_2/Test $ 
^C
sunz04@login1 /sc/orga/projects/zhangw09a/Data/Zeguo_Sun/project/4.Retron/7.De_novo/3.Run/SC_2/Test $ 

sunz04@login1 /sc/orga/projects/zhangw09a/Data/Zeguo_Sun/project/4.Retron/7.De_novo/3.Run/SC_2/Test $ 
vi test.sh 
sunz04@login1 /sc/orga/projects/zhangw09a/Data/Zeguo_Sun/project/4.Retron/7.De_novo/3.Run/SC_2/Test $ 
bash test.sh 

Inspecting and pre-processing inputs
Traceback (most recent call last):
  File "/hpc/packages/minerva-common/py_packages/3.6/bin/sircel", line 11, in <module>
    load_entry_point('sircel==0.1.2', 'console_scripts', 'sircel')()
  File "/hpc/packages/minerva-common/py_packages/3.6/lib/python3.6/site-packages/sircel-0.1.2-py3.6.egg/sircel/__main__.py", line 5, in main
    output_files = run_all(args)
  File "/hpc/packages/minerva-common/py_packages/3.6/lib/python3.6/site-packages/sircel-0.1.2-py3.6.egg/sircel/Sircel_master.py", line 38, in run_all
    check_pipeline_input(args, kallisto)
  File "/hpc/packages/minerva-common/py_packages/3.6/lib/python3.6/site-packages/sircel-0.1.2-py3.6.egg/sircel/Sircel_master.py", line 212, in check_pipeline_input
    'Cannot find kallisto executable %s' % kallisto
AssertionError: Cannot find kallisto executable /hpc/packages/minerva-common/kallisto/0.45.0/kallisto_linux-v0.45.0
sunz04@login1 /sc/orga/projects/zhangw09a/Data/Zeguo_Sun/project/4.Retron/7.De_novo/3.Run/SC_2/Test $ 
ls /hpc/packages/minerva-common/kallisto/0.45.0/kallisto_linux-v0.45.0
kallisto  license.txt  README.md  test
sunz04@login1 /sc/orga/projects/zhangw09a/Data/Zeguo_Sun/project/4.Retron/7.De_novo/3.Run/SC_2/Test $ 
vi test.sh 
sunz04@login1 /sc/orga/projects/zhangw09a/Data/Zeguo_Sun/project/4.Retron/7.De_novo/3.Run/SC_2/Test $ 
module purge
sunz04@login1 /sc/orga/projects/zhangw09a/Data/Zeguo_Sun/project/4.Retron/7.De_novo/3.Run/SC_2/Test $ 
bash test.sh 

Inspecting and pre-processing inputs
Unzipping (temporary)
^CTraceback (most recent call last):
  File "/hpc/packages/minerva-common/py_packages/3.6/bin/sircel", line 11, in <module>
    load_entry_point('sircel==0.1.2', 'console_scripts', 'sircel')()
  File "/hpc/packages/minerva-common/py_packages/3.6/lib/python3.6/site-packages/sircel-0.1.2-py3.6.egg/sircel/__main__.py", line 5, in main
    output_files = run_all(args)
  File "/hpc/packages/minerva-common/py_packages/3.6/lib/python3.6/site-packages/sircel-0.1.2-py3.6.egg/sircel/Sircel_master.py", line 59, in run_all
    IO_utils.unzip(args['reads'].split(','))
  File "/hpc/packages/minerva-common/py_packages/3.6/lib/python3.6/site-packages/sircel-0.1.2-py3.6.egg/sircel/utils/IO_utils.py", line 87, in unzip
    for lines in grouper(in_file, 4):
  File "/hpc/packages/minerva-common/python/3.6.2/lib/python3.6/gzip.py", line 374, in readline
    return self._buffer.readline(size)
KeyboardInterrupt
sunz04@login1 /sc/orga/projects/zhangw09a/Data/Zeguo_Sun/project/4.Retron/7.De_novo/3.Run/SC_2/Test $ 
^C
sunz04@login1 /sc/orga/projects/zhangw09a/Data/Zeguo_Sun/project/4.Retron/7.De_novo/3.Run/SC_2/Test $ 
ls
example  test.sh
sunz04@login1 /sc/orga/projects/zhangw09a/Data/Zeguo_Sun/project/4.Retron/7.De_novo/3.Run/SC_2/Test $ 
exit
logout
[root@login1 users]# 
[root@login1 users]# ssh mgmt1
Last login: Tue Jan 15 14:30:18 2019 from mgmt2
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
	The /sc/orga/ file system is optimized for performance and
	capacity. It provides minimal redundancy and no backups.

	Data stored in /sc/orga/scratch/ is automatically purged after
	14 days.

	===    Follow us on Twitter @mssmhpc    ===
    === Send ticket to hpchelp@hpc.mssm.edu ===
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

[root@mgmt1 ~]# 
[root@mgmt1 ~]# ssh minerva2
Last login: Tue Jan 15 13:00:28 2019 from mgmt2
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
	The /sc/orga/ file system is optimized for performance and
	capacity. It provides minimal redundancy and no backups.

	Data stored in /sc/orga/scratch/ is automatically purged after
	14 days.

	===    Follow us on Twitter @mssmhpc    ===
    === Send ticket to hpchelp@hpc.mssm.edu ===
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

[root@minerva2 ~]# cd /var/log/
[root@minerva2 log]# grep xbankis01
^C
[root@minerva2 log]# grep xbankis01 secure
Jan 16 04:21:49 minerva2 sshd[60873]: pam_unix(sshd:auth): authentication failure; logname= uid=0 euid=0 tty=ssh ruser= rhost=w6353.see.ed.ac.uk  user=xbankis01+yldap
Jan 16 04:21:50 minerva2 sshd[60873]: pam_sss(sshd:auth): authentication failure; logname= uid=0 euid=0 tty=ssh ruser= rhost=w6353.see.ed.ac.uk user=xbankis01+yldap
Jan 16 04:21:50 minerva2 sshd[60873]: pam_sss(sshd:auth): received for user xbankis01+yldap: 7 (Authentication failure)
Jan 16 04:21:52 minerva2 sshd[60871]: error: PAM: Authentication failure for xbankis01+yldap from w6353.see.ed.ac.uk
Jan 16 04:22:22 minerva2 sshd[60875]: pam_unix(sshd:auth): authentication failure; logname= uid=0 euid=0 tty=ssh ruser= rhost=w6353.see.ed.ac.uk  user=xbankis01+yldap
Jan 16 04:22:22 minerva2 sshd[60875]: pam_sss(sshd:auth): authentication failure; logname= uid=0 euid=0 tty=ssh ruser= rhost=w6353.see.ed.ac.uk user=xbankis01+yldap
Jan 16 04:22:22 minerva2 sshd[60875]: pam_sss(sshd:auth): received for user xbankis01+yldap: 7 (Authentication failure)
Jan 16 04:22:24 minerva2 sshd[60871]: error: PAM: Authentication failure for xbankis01+yldap from w6353.see.ed.ac.uk
Jan 16 04:24:04 minerva2 sshd[60881]: pam_unix(sshd:auth): authentication failure; logname= uid=0 euid=0 tty=ssh ruser= rhost=w6353.see.ed.ac.uk  user=xbankis01+yldap
Jan 16 04:24:04 minerva2 sshd[60881]: pam_sss(sshd:auth): authentication success; logname= uid=0 euid=0 tty=ssh ruser= rhost=w6353.see.ed.ac.uk user=xbankis01+yldap
Jan 16 04:24:04 minerva2 sshd[60881]: pam_access(sshd:account): access denied for user `xbankis01+yldap' from `w6353.see.ed.ac.uk'
Jan 16 04:24:04 minerva2 sshd[60879]: Accepted keyboard-interactive/pam for xbankis01+yldap from 129.215.102.23 port 56256 ssh2
Jan 16 04:24:04 minerva2 sshd[60879]: pam_unix(sshd:session): session opened for user xbankis01+yldap by (uid=0)
Jan 16 06:35:35 minerva2 sshd[60879]: pam_unix(sshd:session): session closed for user xbankis01+yldap
Jan 16 09:00:12 minerva2 sshd[9946]: pam_unix(sshd:auth): authentication failure; logname= uid=0 euid=0 tty=ssh ruser= rhost=w6353.see.ed.ac.uk  user=xbankis01+yldap
Jan 16 09:00:12 minerva2 sshd[9946]: pam_sss(sshd:auth): authentication success; logname= uid=0 euid=0 tty=ssh ruser= rhost=w6353.see.ed.ac.uk user=xbankis01+yldap
Jan 16 09:00:12 minerva2 sshd[9946]: pam_access(sshd:account): access denied for user `xbankis01+yldap' from `w6353.see.ed.ac.uk'
Jan 16 09:00:12 minerva2 sshd[9943]: Accepted keyboard-interactive/pam for xbankis01+yldap from 129.215.102.23 port 59608 ssh2
Jan 16 09:00:13 minerva2 sshd[9943]: pam_unix(sshd:session): session opened for user xbankis01+yldap by (uid=0)
Jan 16 09:00:57 minerva2 sshd[11366]: pam_unix(sshd:auth): authentication failure; logname= uid=0 euid=0 tty=ssh ruser= rhost=w6353.see.ed.ac.uk  user=xbankis01+yldap
Jan 16 09:00:58 minerva2 sshd[11366]: pam_sss(sshd:auth): authentication failure; logname= uid=0 euid=0 tty=ssh ruser= rhost=w6353.see.ed.ac.uk user=xbankis01+yldap
Jan 16 09:00:58 minerva2 sshd[11366]: pam_sss(sshd:auth): received for user xbankis01+yldap: 7 (Authentication failure)
Jan 16 09:01:00 minerva2 sshd[11364]: error: PAM: Authentication failure for xbankis01+yldap from w6353.see.ed.ac.uk
Jan 16 09:01:41 minerva2 sshd[11395]: pam_unix(sshd:auth): authentication failure; logname= uid=0 euid=0 tty=ssh ruser= rhost=w6353.see.ed.ac.uk  user=xbankis01+yldap
Jan 16 09:01:42 minerva2 sshd[11395]: pam_sss(sshd:auth): authentication failure; logname= uid=0 euid=0 tty=ssh ruser= rhost=w6353.see.ed.ac.uk user=xbankis01+yldap
Jan 16 09:01:42 minerva2 sshd[11395]: pam_sss(sshd:auth): received for user xbankis01+yldap: 7 (Authentication failure)
Jan 16 09:01:44 minerva2 sshd[11393]: error: PAM: Authentication failure for xbankis01+yldap from w6353.see.ed.ac.uk
Jan 16 09:02:09 minerva2 sshd[11537]: pam_unix(sshd:auth): authentication failure; logname= uid=0 euid=0 tty=ssh ruser= rhost=w6353.see.ed.ac.uk  user=xbankis01+yldap
Jan 16 09:02:09 minerva2 sshd[11537]: pam_sss(sshd:auth): authentication success; logname= uid=0 euid=0 tty=ssh ruser= rhost=w6353.see.ed.ac.uk user=xbankis01+yldap
Jan 16 09:02:09 minerva2 sshd[11537]: pam_access(sshd:account): access denied for user `xbankis01+yldap' from `w6353.see.ed.ac.uk'
Jan 16 09:02:09 minerva2 sshd[11393]: Accepted keyboard-interactive/pam for xbankis01+yldap from 129.215.102.23 port 59654 ssh2
Jan 16 09:02:10 minerva2 sshd[11393]: pam_unix(sshd:session): session opened for user xbankis01+yldap by (uid=0)
Jan 16 09:03:59 minerva2 sshd[11393]: pam_unix(sshd:session): session closed for user xbankis01+yldap
Jan 16 09:04:32 minerva2 sshd[12334]: pam_unix(sshd:auth): authentication failure; logname= uid=0 euid=0 tty=ssh ruser= rhost=w6353.see.ed.ac.uk  user=xbankis01+yldap
Jan 16 09:04:32 minerva2 sshd[12334]: pam_sss(sshd:auth): authentication failure; logname= uid=0 euid=0 tty=ssh ruser= rhost=w6353.see.ed.ac.uk user=xbankis01+yldap
Jan 16 09:04:32 minerva2 sshd[12334]: pam_sss(sshd:auth): received for user xbankis01+yldap: 7 (Authentication failure)
Jan 16 09:04:35 minerva2 sshd[12332]: error: PAM: Authentication failure for xbankis01+yldap from w6353.see.ed.ac.uk
Jan 16 09:04:51 minerva2 sshd[12336]: pam_unix(sshd:auth): authentication failure; logname= uid=0 euid=0 tty=ssh ruser= rhost=w6353.see.ed.ac.uk  user=xbankis01+yldap
Jan 16 09:04:51 minerva2 sshd[12336]: pam_sss(sshd:auth): authentication failure; logname= uid=0 euid=0 tty=ssh ruser= rhost=w6353.see.ed.ac.uk user=xbankis01+yldap
Jan 16 09:04:51 minerva2 sshd[12336]: pam_sss(sshd:auth): received for user xbankis01+yldap: 7 (Authentication failure)
Jan 16 09:04:53 minerva2 sshd[12332]: error: PAM: Authentication failure for xbankis01+yldap from w6353.see.ed.ac.uk
Jan 16 09:05:54 minerva2 sshd[12549]: pam_unix(sshd:auth): authentication failure; logname= uid=0 euid=0 tty=ssh ruser= rhost=w6353.see.ed.ac.uk  user=xbankis01+yldap
Jan 16 09:05:54 minerva2 sshd[12549]: pam_sss(sshd:auth): authentication failure; logname= uid=0 euid=0 tty=ssh ruser= rhost=w6353.see.ed.ac.uk user=xbankis01+yldap
Jan 16 09:05:54 minerva2 sshd[12549]: pam_sss(sshd:auth): received for user xbankis01+yldap: 7 (Authentication failure)
Jan 16 09:05:56 minerva2 sshd[12547]: error: PAM: Authentication failure for xbankis01+yldap from w6353.see.ed.ac.uk
Jan 16 09:07:44 minerva2 sshd[12987]: pam_unix(sshd:auth): auth could not identify password for [xbankis01+yldap]
Jan 16 09:07:44 minerva2 sshd[12987]: pam_sss(sshd:auth): authentication failure; logname= uid=0 euid=0 tty=ssh ruser= rhost=w6353.see.ed.ac.uk user=xbankis01+yldap
Jan 16 09:07:44 minerva2 sshd[12987]: pam_sss(sshd:auth): received for user xbankis01+yldap: 19 (Conversation error)
Jan 16 09:38:54 minerva2 sshd[61291]: pam_unix(sshd:auth): authentication failure; logname= uid=0 euid=0 tty=ssh ruser= rhost=pat-131-255.wlan.net.ed.ac.uk  user=xbankis01+yldap
Jan 16 09:38:54 minerva2 sshd[61291]: pam_sss(sshd:auth): authentication failure; logname= uid=0 euid=0 tty=ssh ruser= rhost=pat-131-255.wlan.net.ed.ac.uk user=xbankis01+yldap
Jan 16 09:38:54 minerva2 sshd[61291]: pam_sss(sshd:auth): received for user xbankis01+yldap: 7 (Authentication failure)
Jan 16 09:38:57 minerva2 sshd[61289]: error: PAM: Authentication failure for xbankis01+yldap from pat-131-255.wlan.net.ed.ac.uk
Jan 16 09:39:11 minerva2 sshd[61293]: pam_unix(sshd:auth): authentication failure; logname= uid=0 euid=0 tty=ssh ruser= rhost=pat-131-255.wlan.net.ed.ac.uk  user=xbankis01+yldap
Jan 16 09:39:11 minerva2 sshd[61293]: pam_sss(sshd:auth): authentication failure; logname= uid=0 euid=0 tty=ssh ruser= rhost=pat-131-255.wlan.net.ed.ac.uk user=xbankis01+yldap
Jan 16 09:39:11 minerva2 sshd[61293]: pam_sss(sshd:auth): received for user xbankis01+yldap: 7 (Authentication failure)
Jan 16 09:39:13 minerva2 sshd[61289]: error: PAM: Authentication failure for xbankis01+yldap from pat-131-255.wlan.net.ed.ac.uk
Jan 16 11:15:06 minerva2 sshd[9943]: pam_unix(sshd:session): session closed for user xbankis01+yldap
Jan 16 11:33:12 minerva2 sshd[50392]: pam_unix(sshd:auth): authentication failure; logname= uid=0 euid=0 tty=ssh ruser= rhost=w6353.see.ed.ac.uk  user=xbankis01+yldap
Jan 16 11:33:13 minerva2 sshd[50392]: pam_sss(sshd:auth): authentication failure; logname= uid=0 euid=0 tty=ssh ruser= rhost=w6353.see.ed.ac.uk user=xbankis01+yldap
Jan 16 11:33:13 minerva2 sshd[50392]: pam_sss(sshd:auth): received for user xbankis01+yldap: 7 (Authentication failure)
Jan 16 11:33:15 minerva2 sshd[50217]: error: PAM: Authentication failure for xbankis01+yldap from w6353.see.ed.ac.uk
Jan 16 11:33:50 minerva2 sshd[50614]: pam_unix(sshd:auth): authentication failure; logname= uid=0 euid=0 tty=ssh ruser= rhost=w6353.see.ed.ac.uk  user=xbankis01+yldap
Jan 16 11:33:50 minerva2 sshd[50614]: pam_sss(sshd:auth): authentication success; logname= uid=0 euid=0 tty=ssh ruser= rhost=w6353.see.ed.ac.uk user=xbankis01+yldap
Jan 16 11:33:51 minerva2 sshd[50614]: pam_access(sshd:account): access denied for user `xbankis01+yldap' from `w6353.see.ed.ac.uk'
Jan 16 11:33:51 minerva2 sshd[50612]: Accepted keyboard-interactive/pam for xbankis01+yldap from 129.215.102.23 port 33166 ssh2
Jan 16 11:33:51 minerva2 sshd[50612]: pam_unix(sshd:session): session opened for user xbankis01+yldap by (uid=0)
Jan 16 11:34:02 minerva2 sshd[50612]: pam_unix(sshd:session): session closed for user xbankis01+yldap
[root@minerva2 log]# last xbankis01
xbankis0 pts/54       w6353.see.ed.ac. Wed Jan 16 11:33 - 11:34  (00:00)    
xbankis0 pts/106      w6353.see.ed.ac. Wed Jan 16 09:00 - 11:15  (02:14)    
xbankis0 pts/31       w6353.see.ed.ac. Wed Jan 16 04:24 - 06:35  (02:11)    
xbankis0 pts/129      w6353.see.ed.ac. Tue Jan 15 09:49 - 09:49  (00:00)    
xbankis0 pts/109      w6353.see.ed.ac. Tue Jan 15 09:45 - 11:38  (01:53)    
xbankis0 pts/54       w6353.see.ed.ac. Tue Jan 15 09:15 - 09:16  (00:00)    
xbankis0 pts/54       w6353.see.ed.ac. Tue Jan 15 07:57 - 07:57  (00:00)    
xbankis0 pts/54       pat-125-253.wlan Tue Jan 15 07:55 - 07:56  (00:01)    
xbankis0 pts/12       w6353.see.ed.ac. Tue Jan 15 07:43 - 10:06  (02:23)    
xbankis0 pts/121      w6353.see.ed.ac. Tue Jan 15 06:42 - 06:42  (00:00)    
xbankis0 pts/121      pat-131-250.wlan Tue Jan 15 06:40 - 06:42  (00:01)    
xbankis0 pts/101      w6353.see.ed.ac. Tue Jan 15 06:20 - 06:36  (00:16)    
xbankis0 pts/90       w6353.see.ed.ac. Tue Jan 15 04:45 - 04:59  (00:13)    
xbankis0 pts/73       w6353.see.ed.ac. Tue Jan 15 04:34 - 04:35  (00:00)    
xbankis0 pts/71       w6353.see.ed.ac. Tue Jan 15 04:22 - 10:03  (05:41)    
xbankis0 pts/136      pat-131-250.wlan Mon Jan 14 10:57 - 10:59  (00:02)    
xbankis0 pts/132      w6353.see.ed.ac. Mon Jan 14 10:32 - 10:33  (00:00)    
xbankis0 pts/132      w6353.see.ed.ac. Mon Jan 14 10:31 - 10:31  (00:00)    
xbankis0 pts/128      w6353.see.ed.ac. Mon Jan 14 09:59 - 10:03  (00:04)    
xbankis0 pts/128      w6353.see.ed.ac. Mon Jan 14 09:57 - 09:57  (00:00)    
xbankis0 pts/128      w6353.see.ed.ac. Mon Jan 14 09:56 - 09:57  (00:00)    
xbankis0 pts/12       w6353.see.ed.ac. Mon Jan 14 09:02 - 12:41  (03:39)    
xbankis0 pts/69       pat-131-254.wlan Mon Jan 14 04:01 - 04:01  (00:00)    
xbankis0 pts/69       w6353.see.ed.ac. Mon Jan 14 03:53 - 03:53  (00:00)    
xbankis0 pts/102      cpc102388-sgyl38 Sat Jan 12 10:15 - 12:37  (02:21)    
xbankis0 pts/114      w6353.see.ed.ac. Fri Jan 11 10:58 - 10:58  (00:00)    
xbankis0 pts/110      w6353.see.ed.ac. Fri Jan 11 10:14 - 13:03  (02:49)    
xbankis0 pts/15       w6353.see.ed.ac. Fri Jan 11 08:36 - 10:51  (02:15)    

wtmp begins Tue Jan  1 03:23:34 2019
[root@minerva2 log]# nslookup w6353.see.ed.ac.uk
Server:		172.29.39.251
Address:	172.29.39.251#53

Non-authoritative answer:
Name:	w6353.see.ed.ac.uk
Address: 129.215.102.23

[root@minerva2 log]# iptables -L
Chain INPUT (policy ACCEPT)
target     prot opt source               destination         
fail2ban-SSH  tcp  --  anywhere             anywhere            tcp dpt:ssh 
HPC-FIREWALL  all  --  anywhere             anywhere            

Chain FORWARD (policy ACCEPT)
target     prot opt source               destination         
HPC-FIREWALL  all  --  anywhere             anywhere            

Chain OUTPUT (policy ACCEPT)
target     prot opt source               destination         

Chain HPC-FIREWALL (2 references)
target     prot opt source               destination         
ACCEPT     all  --  anywhere             anywhere            
ACCEPT     all  --  anywhere             anywhere            state RELATED,ESTABLISHED 
DROP       all  --  115.208.0.0/12       anywhere            
DROP       all  --  183.128.0.0/11       anywhere            
ACCEPT     all  --  172.29.32.0/20       anywhere            
ACCEPT     tcp  --  anywhere             anywhere            state NEW tcp dpt:gsiftp 
ACCEPT     udp  --  anywhere             anywhere            state NEW udp dpt:gsiftp 
ACCEPT     tcp  --  anywhere             anywhere            state NEW tcp dpt:7512 
ACCEPT     udp  --  anywhere             anywhere            state NEW udp dpt:7512 
ACCEPT     tcp  --  anywhere             anywhere            state NEW tcp dpts:50000:51000 
ACCEPT     udp  --  anywhere             anywhere            state NEW udp dpts:50000:51000 
ACCEPT     tcp  --  10.95.46.0/23        anywhere            /* GPFS traffic from hpc campus subnet */ state NEW tcp dpt:gpfs 
ACCEPT     tcp  --  172.29.32.0/20       anywhere            /* GPFS traffic from hpc internal subnet */ state NEW tcp dpt:gpfs 
ACCEPT     all  --  node6-20-ib0         anywhere            /* node6-20.ib */ state NEW 
ACCEPT     all  --  node7-20-ib0         anywhere            /* node7-20.ib */ state NEW 
ACCEPT     all  --  node8-20-ib0         anywhere            /* node8-20.ib */ state NEW 
ACCEPT     all  --  anywhere             anywhere            /* gs{01..04}.mgmt */ source IP range 10.95.46.41-10.95.46.44 state NEW 
ACCEPT     all  --  anywhere             anywhere            /* gs{01..04}.ib */ source IP range 172.29.40.1-172.29.40.4 state NEW 
ACCEPT     all  --  anywhere             anywhere            /* utility{1..4}.mothra */ source IP range 172.29.38.7-172.29.38.10 state NEW 
ACCEPT     all  --  anywhere             anywhere            /* nsd{1..8}.mothra */ source IP range 172.29.39.11-172.29.39.18 state NEW 
ACCEPT     all  --  anywhere             anywhere            /* gss{1..8}.mothra */ source IP range 172.29.39.243-172.29.39.250 state NEW 
ACCEPT     all  --  anywhere             anywhere            /* utility{1..4}.ib, nsd{1..8}.ib, gss{1..8}.ib */ source IP range 172.29.43.7-172.29.43.250 state NEW 
ACCEPT     all  --  10.95.46.41          anywhere            state NEW 
ACCEPT     all  --  10.95.46.42          anywhere            state NEW 
ACCEPT     all  --  10.95.46.43          anywhere            state NEW 
ACCEPT     all  --  10.95.46.44          anywhere            state NEW 
ACCEPT     all  --  172.29.40.1          anywhere            state NEW 
ACCEPT     all  --  172.29.40.2          anywhere            state NEW 
ACCEPT     all  --  172.29.40.3          anywhere            state NEW 
ACCEPT     all  --  172.29.40.4          anywhere            state NEW 
ACCEPT     all  --  hpccore1.mgmt.hpc.mssm.edu  anywhere            state NEW 
ACCEPT     all  --  172.29.36.2          anywhere            state NEW 
ACCEPT     all  --  172.29.36.3          anywhere            state NEW 
ACCEPT     all  --  172.29.36.4          anywhere            state NEW 
ACCEPT     tcp  --  10.95.46.0/24        anywhere            state NEW tcp dpt:gpfs 
ACCEPT     tcp  --  172.29.32.0/20       anywhere            state NEW tcp dpt:gpfs 
ACCEPT     tcp  --  anywhere             anywhere            state NEW tcp dpt:commplex-link 
ACCEPT     udp  --  anywhere             anywhere            state NEW udp dpt:commplex-link 
ACCEPT     tcp  --  anywhere             anywhere            state NEW tcp dpt:targus-getdata1 
ACCEPT     udp  --  anywhere             anywhere            state NEW udp dpt:targus-getdata1 
ACCEPT     udp  --  anywhere             anywhere            /* MOSH */ state NEW udp dpts:60000:60100 
ACCEPT     tcp  --  anywhere             anywhere            multiport dports 5666 /* nrpe */ state NEW 
ACCEPT     icmp --  anywhere             anywhere            icmp any 
ACCEPT     icmp --  10.95.46.0/24        anywhere            icmp any 
ACCEPT     icmp --  172.29.32.0/20       anywhere            icmp any 
DROP       tcp  --  anywhere             anywhere            state NEW tcp dpt:smtp 
ACCEPT     tcp  --  anywhere             anywhere            state NEW tcp dpt:ssh 
ACCEPT     tcp  --  10.95.46.0/24        anywhere            state NEW tcp dpt:ssh 
ACCEPT     tcp  --  172.29.32.0/20       anywhere            state NEW tcp dpt:ssh 
ACCEPT     tcp  --  10.95.46.0/24        anywhere            state NEW tcp dpts:hydap:15010 
ACCEPT     tcp  --  172.29.32.0/20       anywhere            state NEW tcp dpts:hydap:15010 
ACCEPT     udp  --  10.95.46.0/24        anywhere            state NEW udp dpts:hydap:15010 
ACCEPT     udp  --  172.29.32.0/20       anywhere            state NEW udp dpts:hydap:15010 
ACCEPT     udp  --  10.95.46.0/24        anywhere            state NEW udp dpts:exp2:1023 
ACCEPT     udp  --  172.29.32.0/20       anywhere            state NEW udp dpts:exp2:1023 
ACCEPT     tcp  --  10.95.46.0/24        anywhere            state NEW tcp dpt:42559 
ACCEPT     tcp  --  172.29.32.0/20       anywhere            state NEW tcp dpt:42559 
DROP       all  --  anywhere             anywhere            

Chain fail2ban-SSH (1 references)
target     prot opt source               destination         
DROP       all  --  188.131.192.54       anywhere            
DROP       all  --  218.92.1.130         anywhere            
DROP       all  --  promote.cache-dns.local  anywhere            
DROP       all  --  servera-07.cwbshop.com.br  anywhere            
DROP       all  --  61.184.247.3         anywhere            
DROP       all  --  61.184.247.6         anywhere            
DROP       all  --  122.226.181.167      anywhere            
DROP       all  --  taa-cgn6.kviknet.dk  anywhere            
DROP       all  --  huil5.fitarmonit.club  anywhere            
DROP       all  --  122.226.181.165      anywhere            
DROP       all  --  115.238.245.2        anywhere            
DROP       all  --  121.18.238.12        anywhere            
DROP       all  --  121.18.238.8         anywhere            
DROP       all  --  38.105.215.220       anywhere            
DROP       all  --  61.241.82.125        anywhere            
RETURN     all  --  anywhere             anywhere            
[root@minerva2 log]# 129.215.102.23
-bash: 129.215.102.23: command not found
[root@minerva2 log]# ssh data2
root@data2's password: 

[root@minerva2 log]# exit
logout
Connection to minerva2 closed.
[root@mgmt1 ~]# ssh data2
Last login: Wed Jan 16 16:15:43 2019 from mgmt1
[root@data2 ~]# su - gail01
gail01@data2: ~ $ cd /sc/orga 
-bash: cd: /sc/orga: Stale file handle
gail01@data2: ~ $ cd mysing/
gail01@data2: ~/mysing $ ls
susie-paper
gail01@data2: ~/mysing $ mkdir test
gail01@data2: ~/mysing $ cd test/
gail01@data2: ~/mysing/test $ singularity build hello-world.simg shub://vsoch/hello-world
WARNING: Authentication token file not found : Only pulls of public images will succeed
INFO:    Starting build...
 62.32 MiB / 62.32 MiB [==============================================================================================================================================================] 100.00% 13.12 MiB/s 4s
INFO:    Creating SIF file...
INFO:    Build complete: hello-world.simg
gail01@data2: ~/mysing/test $ ls
hello-world.simg
gail01@data2: ~/mysing/test $ vi hello-world.simg 
gail01@data2: ~/mysing/test $ singularity run hello-world.simg 
RaawwWWWWWRRRR!!
gail01@data2: ~/mysing/test $ singularity build lolcow.simg docker://godlovedc/lolcow
WARNING: Authentication token file not found : Only pulls of public images will succeed
INFO:    Starting build...
Getting image source signatures
Copying blob sha256:9fb6c798fa41e509b58bccc5c29654c3ff4648b608f5daa67c1aab6a7d02c118
 45.33 MiB / 45.33 MiB [====================================================] 1s
Copying blob sha256:3b61febd4aefe982e0cb9c696d415137384d1a01052b50a85aae46439e15e49a
 848 B / 848 B [============================================================] 0s
Copying blob sha256:9d99b9777eb02b8943c0e72d7a7baec5c782f8fd976825c9d3fb48b3101aacc2
 621 B / 621 B [============================================================] 0s
Copying blob sha256:d010c8cf75d7eb5d2504d5ffa0d19696e8d745a457dd8d28ec6dd41d3763617e
 853 B / 853 B [============================================================] 0s
Copying blob sha256:7fac07fb303e0589b9c23e6f49d5dc1ff9d6f3c8c88cabe768b430bdb47f03a9
 169 B / 169 B [============================================================] 0s
Copying blob sha256:8e860504ff1ee5dc7953672d128ce1e4aa4d8e3716eb39fe710b849c64b20945
 53.75 MiB / 53.75 MiB [====================================================] 3s
Copying config sha256:73d5b1025fbfa138f2cacf45bbf3f61f7de891559fa25b28ab365c7d9c3cbd82
 3.33 KiB / 3.33 KiB [======================================================] 0s
Writing manifest to image destination
Storing signatures
INFO:    Creating SIF file...
INFO:    Build complete: lolcow.simg
gail01@data2: ~/mysing/test $ ls
hello-world.simg  lolcow.simg
gail01@data2: ~/mysing/test $ vi lolcow.simg 
gail01@data2: ~/mysing/test $     
gail01@data2: ~/mysing/test $ sigulari
-bash: sigulari: command not found
gail01@data2: ~/mysing/test $ singularity lolcow.simg 

Linux container platform optimized for High Performance Computing (HPC) and
Enterprise Performance Computing (EPC)

Usage:
  singularity [global options...]

Description:
  Singularity containers provide an application virtualization layer enabling
  mobility of compute via both application and environment portability. With
  Singularity one is capable of building a root file system that runs on any 
  other Linux system where Singularity is installed.

Options:
  -d, --debug              print debugging information (highest verbosity)
  -h, --help               help for singularity
  -q, --quiet              suppress normal output
  -s, --silent             only print errors
  -t, --tokenfile string   path to the file holding your sylabs
                           authentication token (default
                           "/hpc/users/gail01/.singularity/sylabs-token")
  -v, --verbose            print additional information
      --version            version for singularity

Available Commands:
  build       Build a new Singularity container
  capability  Manage Linux capabilities on containers
  exec        Execute a command within container
  help        Help about any command
  inspect     Display metadata for container if available
  instance    Manage containers running in the background
  keys        Manage OpenPGP key stores
  pull        Pull a container from a URI
  push        Push a container to a Library URI
  run         Launch a runscript within container
  run-help    Display help for container if available
  search      Search the library
  shell       Run a Bourne shell within container
  sign        Attach cryptographic signatures to container
  test        Run defined tests for this particular container
  verify      Verify cryptographic signatures on container
  version     Show application version

Examples:
  $ singularity help <command>
      Additional help for any Singularity subcommand can be seen by appending
      the subcommand name to the above command.


For additional help or support, please visit https://www.sylabs.io/docs/
gail01@data2: ~/mysing/test $ singularity run lolcow.simg 
WARNING: skipping mount of /etc/localtime: no such file or directory
 _________________________________________
/ Q: How many Bell Labs Vice Presidents   \
| does it take to change a light bulb? A: |
| That's proprietary information. Answer  |
| available from AT&T on payment          |
|                                         |
\ of license fee (binary only).           /
 -----------------------------------------
        \   ^__^
         \  (oo)\_______
            (__)\       )\/\
                ||----w |
                ||     ||
gail01@data2: ~/mysing/test $ singularity shell hello-world.simg 
Singularity hello-world.simg:~/mysing/test> 
Singularity hello-world.simg:~/mysing/test> 
Singularity hello-world.simg:~/mysing/test> whoami
gail01
Singularity hello-world.simg:~/mysing/test> exit
gail01@data2: ~/mysing/test $ singularity exec hello-world.simg ls
hello-world.simg  lolcow.simg
gail01@data2: ~/mysing/test $ singularity exec hello-world.simg ls /
bin  boot  dev	environment  etc  home	hpc  lib  lib64  media	mnt  opt  proc	rawr.sh  root  run  sbin  singularity  srv  sys  tmp  usr  var
gail01@data2: ~/mysing/test $ singularity exec hello-world.simg ls -lt /
total 10
drwxr-xr-x.   3 gail01 hpcstaff   60 Jan 16 18:46 hpc
drwxrwxrwt.  13 root   root      400 Jan 16 18:44 tmp
lrwxrwxrwx.   1 root   root       36 Jan 16 18:43 environment -> .singularity.d/env/90-environment.sh
lrwxrwxrwx.   1 root   root       24 Jan 16 18:43 singularity -> .singularity.d/runscript
dr-xr-xr-x.  13 root   root        0 Jan 15 22:49 sys
dr-xr-xr-x. 403 root   root        0 Jan 15 22:48 proc
drwxr-xr-x.  61 root   root     2087 Oct 15  2017 etc
-rwxr-xr-x.   1 root   root       37 Oct 15  2017 rawr.sh
drwxr-xr-x.   8 root   root      141 Sep 13  2017 run
drwxr-xr-x.   2 root   root     2110 Sep 13  2017 sbin
drwxr-xr-x.   2 root   root     1645 Aug 17  2017 bin
drwx------.   2 root   root       46 Aug 17  2017 root
drwxr-xr-x.  11 root   root      160 Aug 17  2017 var
drwxr-xr-x.  12 root   root      241 Aug 17  2017 lib
drwxr-xr-x.   2 root   root        3 Aug 17  2017 dev
drwxr-xr-x.   2 root   root       43 Aug 17  2017 lib64
drwxr-xr-x.   2 root   root        3 Aug 17  2017 media
drwxr-xr-x.   2 root   root        3 Aug 17  2017 opt
drwxr-xr-x.   2 root   root        3 Aug 17  2017 srv
drwxr-xr-x.  10 root   root      138 Aug 17  2017 usr
drwxr-xr-x.   2 root   root        3 Apr 10  2014 boot
drwxr-xr-x.   2 root   root        3 Apr 10  2014 home
drwxr-xr-x.   2 root   root        3 Apr 10  2014 mnt
gail01@data2: ~/mysing/test $ echo "Hello World" > $HOME/hello-kitty.txt
gail01@data2: ~/mysing/test $ singularity exec vsoch-hello-world-master.simg cat $HOME/hello-kitty.txt
FATAL:   failed to retrieved path for /hpc/users/gail01/mysing/test/vsoch-hello-world-master.simg: lstat /hpc/users/gail01/mysing/test/vsoch-hello-world-master.simg: no such file or directory
ERROR  : Child exit with status 255
gail01@data2: ~/mysing/test $ ls
hello-world.simg  lolcow.simg
gail01@data2: ~/mysing/test $ singularity exec hello-world.simg cat $HOME/hello-kitty.txt
Hello World
gail01@data2: ~/mysing/test $ cat $HOME/hello-kitty.txt
Hello World
gail01@data2: ~/mysing/test $ cd ..
gail01@data2: ~/mysing $ ls
susie-paper  test
gail01@data2: ~/mysing $ cd susie-paper/
gail01@data2: ~/mysing/susie-paper $ ls
Dockerfile  Home.ipynb  LICENSE  README.md  Singularity  analysis  config.yml  docs  finemapping_benchmark  manuscript_results  release  src  ubuntu_latest.sif
gail01@data2: ~/mysing/susie-paper $ vi Singularity 
gail01@data2: ~/mysing/susie-paper $ git add Singularity 
gail01@data2: ~/mysing/susie-paper $ ls -lt
total 37948
drwxr-xr-x. 2 gail01 hpcstaff     4096 Jan 16 14:34 src
drwxr-xr-x. 2 gail01 hpcstaff       24 Jan 16 14:34 finemapping_benchmark
-rw-r--r--. 1 gail01 hpcstaff      534 Jan 16 14:34 README.md
-rwxr-xr-x. 1 gail01 hpcstaff 27992064 Jan 16 14:34 ubuntu_latest.sif
-rw-r--r--. 1 gail01 hpcstaff     3823 Jan 16 14:34 Dockerfile
-rw-r--r--. 1 gail01 hpcstaff     1460 Jan 16 14:34 config.yml
-rw-r--r--. 1 gail01 hpcstaff     3915 Jan 16 14:34 Singularity
lrwxrwxrwx. 1 gail01 hpcstaff        3 Jan 16 14:34 analysis -> src
-rw-r--r--. 1 gail01 hpcstaff     1114 Jan 16 14:34 LICENSE
drwxr-xr-x. 8 gail01 hpcstaff     4096 Jan 16 14:34 docs
-rwxr-xr-x. 1 gail01 hpcstaff    12838 Jan 16 14:34 release
-rw-r--r--. 1 gail01 hpcstaff    10998 Jan 16 14:34 Home.ipynb
drwxr-xr-x. 2 gail01 hpcstaff     4096 Jan 16 14:34 manuscript_results
gail01@data2: ~/mysing/susie-paper $ git commit -m "Adding Singularity file."

*** Please tell me who you are.

Run

  git config --global user.email "you@example.com"
  git config --global user.name "Your Name"

to set your account's default identity.
Omit --global to set the identity only in this repository.

fatal: unable to auto-detect email address (got 'gail01@data2.(none)')
gail01@data2: ~/mysing/susie-paper $  git config --global llgai508
error: key does not contain a section: llgai508
gail01@data2: ~/mysing/susie-paper $  git config --global user.name "llgai508"
gail01@data2: ~/mysing/susie-paper $ git add Singularity 
gail01@data2: ~/mysing/susie-paper $ git commit -m "Adding Singularity file."

*** Please tell me who you are.

Run

  git config --global user.email "you@example.com"
  git config --global user.name "Your Name"

to set your account's default identity.
Omit --global to set the identity only in this repository.

fatal: unable to auto-detect email address (got 'gail01@data2.(none)')
gail01@data2: ~/mysing/susie-paper $ it config --global user.email "llgai508@gmail.com"
-bash: it: command not found
gail01@data2: ~/mysing/susie-paper $ git config --global user.email "llgai508@gmail.com"
gail01@data2: ~/mysing/susie-paper $ git config --global user.name "llgai508"
gail01@data2: ~/mysing/susie-paper $ git add Singularity 
gail01@data2: ~/mysing/susie-paper $ git commit -m "Adding Singularity file."
[master ddddae9] Adding Singularity file.
 1 file changed, 101 insertions(+)
 create mode 100644 Singularity
gail01@data2: ~/mysing/susie-paper $ git commit -m "Adding Singularity file."
# On branch master
# Your branch is ahead of 'origin/master' by 1 commit.
#   (use "git push" to publish your local commits)
#
# Untracked files:
#   (use "git add <file>..." to include in what will be committed)
#
#	ubuntu_latest.sif
nothing added to commit but untracked files present (use "git add" to track)
gail01@data2: ~/mysing/susie-paper $ git push origin master
Username for 'https://github.com': llgai508
Password for 'https://llgai508@github.com': 
remote: Permission to stephenslab/susie-paper.git denied to llgai508.
fatal: unable to access 'https://github.com/stephenslab/susie-paper.git/': The requested URL returned error: 403
gail01@data2: ~/mysing/susie-paper $ cd ..
gail01@data2: ~/mysing $ ls
susie-paper  test
gail01@data2: ~/mysing $ cp susie-paper/Singularity .
gail01@data2: ~/mysing $ git add Singularity 
fatal: Not a git repository (or any parent up to mount point /hpc)
Stopping at filesystem boundary (GIT_DISCOVERY_ACROSS_FILESYSTEM not set).
gail01@data2: ~/mysing $ ls
Singularity  susie-paper  test
gail01@data2: ~/mysing $ mv susie-paper/ susie
gail01@data2: ~/mysing $ git clone https://github.com/stephenslab/susie-paper.git
Cloning into 'susie-paper'...
remote: Enumerating objects: 230, done.
remote: Counting objects: 100% (230/230), done.
remote: Compressing objects: 100% (155/155), done.
^Cceiving objects:  13% (147/1059), 4.32 MiB | 71.00 KiB/s     
gail01@data2: ~/mysing $ ls
Singularity  susie  test
gail01@data2: ~/mysing $ cd susie/
gail01@data2: ~/mysing/susie $ ls
Dockerfile  Home.ipynb  LICENSE  README.md  Singularity  analysis  config.yml  docs  finemapping_benchmark  manuscript_results  release  src  ubuntu_latest.sif
gail01@data2: ~/mysing/susie $ vi Singularity 

Bootstrap: docker
From: debian:stretch-slim
%labels
MAINTAINER Gao Wang, gaow@uchicago.edu
%post

cd /tmp

# Install dev libraries
apt-get update \
&& apt-get install -y --no-install-recommends \
curl \
unzip \
gzip \
bzip2 \
ca-certificates \
build-essential \
gfortran \
libgfortran-6-dev \
libgomp1 \
&& apt-get clean \
&& rm -rf /var/lib/apt/lists/* /var/log/dpkg.log

# R, Python, SoS and DSC
MINICONDA_VERSION=4.5.11
PATH=/opt/miniconda3/bin:$PATH
curl https://repo.continuum.io/miniconda/Miniconda3-$MINICONDA_VERSION-Linux-x86_64.sh -o MCON.sh \
&& /bin/bash MCON.sh -b -p /opt/miniconda3 \
&& ln -s /opt/miniconda3/etc/profile.d/conda.sh /etc/profile.d/conda.sh \
&& conda install matplotlib==3.0.2 seaborn==0.9.0 \
&& conda install -c conda-forge r-base==3.5.1 sos==0.17.7 dsc==0.3.1.2 rpy2==2.9.4 \
&& conda clean --all -tipsy && rm -rf /tmp/* $HOME/.cache
pip install sos-notebook==0.17.3 jupyter_contrib_nbextensions==0.5.0 --no-cache-dir

# Packages for building and running susieR vignettes
conda install -c conda-forge r-devtools r-testthat r-openssl r-reshape r-ggplot2 r-cowplot \
r-profvis r-microbenchmark r-pkgdown r-dplyr r-stringr r-readr r-magrittr \
r-matrixstats r-glmnet \
libiconv && conda clean --all -tipsy && rm -rf /tmp/* $HOME/.cache
ln -s /bin/tar /bin/gtar
"Singularity" 101L, 3915C
