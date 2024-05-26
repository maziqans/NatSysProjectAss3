# Net&Sys Assignment: Running Containers for Application Development

Group Name: __Fill your team name__. 

Team Mates:
1. Ammar Haziq Bin Annas (2116043)
2. __Fill name__ and __matric no__
3. __Fill name__ and __matric no__

## Rules
1. You are allowed to have **3 group** members.
2. When you complete the assignment, make sure to submit the repository link of your cloned project. Make sure all the files are as what you aspect in your repository. 
3. Answer all questions in the **README.md**, in your own repository. Either use the online VSCode, terminal or github to edit. Answers are expected where you see __Fill answer here__.
4. Learn how to use markdown. https://www.w3schools.io/file/markdown-introduction/

## Forking this project repository
1. First thing you need in doing this assignment is to have a github account. Make sure to sign up at https://www.github.com
2. The second thing you need is to fork the Net&Sys Assignment repository in your own github account. 

    1. Go to https://github.com/ZainabBashi/NatSysProject and click fork to copy the project into your own repository
    2. Make sure that the new fork is now in your own repository

***Questions:***

1. What is the link of the fork Net&Sys Assignment in your repository. ***(1 mark)*** 
__(https://github.com/ZainabBashi/NatSysProject)__.
2. How many files and folders are in this repository. ***(1 mark)*** 
__7 Files & 1 Folder__.


## Exploring github codespaces

1. The next thing that we will be doing is exploring codespaces. First of all, read about codespaces https://docs.github.com/en/codespaces/overview#what-is-a-codespace
2. Then go to the link https://github.com/codespaces and we shall start a new codespace.  
3. Click on ***New codespace***.
4. Choose your own Net&Sys Assignment repository to start your codespace.

 <img src="./images/newcodespace.png" width="50%">

5. Once you have created you codespace, you will see the following. You might already be familiar with this, since it will look similar to VSCode. 

 <img src="./images/UIwebvscode.png" width="70%">

6. You will see the [README file](./README.md) file. One is a preview of how it looks like on the web, and the other is the editing view in markdown language. 
7. Edit the [README file](./README.md). Make sure you have your group details correct, ie, group name and team members along with their matric Numbers. 
8. Once you have finish editing, click File->Save or ***ctrl-s*** to save it. 
9. After saving, you will notice an M or U next to your file. You will need to commit any changes, whenever you make changes so that it is uploaded to the github repository. 

 <img src="./images/SourceControlUI.png" width="70%">

10. Click on the source control, hint: its on the left side panel, and it will list down the files that have been modified or updated. Click on commit. It will then ask you "Would you like to stage all your changes and commit them directly?" Just say yes, and a new tab will appear. Type a message to log what you have done, and click on the check mark. 

 <img src="./images/CommittingUI.png" width="70%">

11. After that, sync the changes to the main repository. 
12. Make sure to commit and sync your files to the main repository, or else, your work will be lost since it is not saved into the main repository when you submit your project.

***Questions:***

1. What is default OS used to run the virtual environment for codespaces. ***(1 mark)*** __Linux__.
2. What are the two options of RAM, disk and vcpu configuration you can have in running codespaces . ***(1 mark)***
 __- 4-core 8GB RAM & 32GB Disk__
 __- 8-core 16GB RAM & 64GB Disk__.
3. Why must we commit and sync our current work on source control? ***(1 mark)*** 
__to save the changes we made and record changes history__.

## Exploring the Terminal

1. Look at the TERMINAL tab. Explore and run commands according to the questions below. 
2. You can include your answers as images, or cut and paste the output here. If you are cutting and pasting your answers, wrap your answers in the codeblock clause in markdown. For example, if i run the command **whoami** the the output would look like the one below.
```bash
@joeynor ➜ /workspaces/OSProject (main) $ whoami 
codespace
```



***Questions:***

Look at the TERMINAL tab. Run the following commands and provide the output here. 

1. Run the command **pwd** . ***(1 mark)*** 
```bash
@maziqans ➜ /workspaces/NatSysProjectAss3 (main) $ pwd
/workspaces/NatSysProjectAss3
```

2. Run the command **cat /etc/passwd** . ***(1 mark)*** 
```bash
@maziqans ➜ /workspaces/NatSysProjectAss3 (main) $ cat /etc/passwd
root:x:0:0:root:/root:/bin/bash
daemon:x:1:1:daemon:/usr/sbin:/usr/sbin/nologin
bin:x:2:2:bin:/bin:/usr/sbin/nologin
sys:x:3:3:sys:/dev:/usr/sbin/nologin
sync:x:4:65534:sync:/bin:/bin/sync
games:x:5:60:games:/usr/games:/usr/sbin/nologin
man:x:6:12:man:/var/cache/man:/usr/sbin/nologin
lp:x:7:7:lp:/var/spool/lpd:/usr/sbin/nologin
mail:x:8:8:mail:/var/mail:/usr/sbin/nologin
news:x:9:9:news:/var/spool/news:/usr/sbin/nologin
uucp:x:10:10:uucp:/var/spool/uucp:/usr/sbin/nologin
proxy:x:13:13:proxy:/bin:/usr/sbin/nologin
www-data:x:33:33:www-data:/var/www:/usr/sbin/nologin
backup:x:34:34:backup:/var/backups:/usr/sbin/nologin
list:x:38:38:Mailing List Manager:/var/list:/usr/sbin/nologin
irc:x:39:39:ircd:/var/run/ircd:/usr/sbin/nologin
gnats:x:41:41:Gnats Bug-Reporting System (admin):/var/lib/gnats:/usr/sbin/nologin
nobody:x:65534:65534:nobody:/nonexistent:/usr/sbin/nologin
_apt:x:100:65534::/nonexistent:/usr/sbin/nologin
systemd-timesync:x:101:101:systemd Time Synchronization,,,:/run/systemd:/usr/sbin/nologin
systemd-network:x:102:103:systemd Network Management,,,:/run/systemd:/usr/sbin/nologin
systemd-resolve:x:103:104:systemd Resolver,,,:/run/systemd:/usr/sbin/nologin
messagebus:x:104:105::/nonexistent:/usr/sbin/nologin
codespace:x:1000:1000::/home/codespace:/bin/bash
sshd:x:105:65534::/run/sshd:/usr/sbin/nologin
```

3. Run the command **df** . ***(1 mark)*** 
```bash
@maziqans ➜ /workspaces/NatSysProjectAss3 (main) $ df
Filesystem     1K-blocks     Used Available Use% Mounted on
overlay         32847680 10345876  20807708  34% /
tmpfs              65536        0     65536   0% /dev
shm                65536        8     65528   1% /dev/shm
/dev/root       30298176 24463956   5817836  81% /vscode
/dev/sdb1       46127956       96  43752284   1% /tmp
/dev/loop3      32847680 10345876  20807708  34% /workspaces
```

4. Run the command **du** . ***(1 mark)*** 
```bash
@maziqans ➜ /workspaces/NatSysProjectAss3 (main) $ du
8       ./.git/objects/86
8       ./.git/objects/d8
8       ./.git/objects/58
12      ./.git/objects/b5
8       ./.git/objects/4b
8       ./.git/objects/04
1824    ./.git/objects/pack
12      ./.git/objects/af
8       ./.git/objects/3f
12      ./.git/objects/73
16      ./.git/objects/b6
8       ./.git/objects/96
8       ./.git/objects/1b
12      ./.git/objects/70
12      ./.git/objects/ff
8       ./.git/objects/4a
8       ./.git/objects/f6
8       ./.git/objects/cb
12      ./.git/objects/1c
8       ./.git/objects/52
8       ./.git/objects/c6
12      ./.git/objects/81
8       ./.git/objects/eb
8       ./.git/objects/fd
8       ./.git/objects/71
8       ./.git/objects/24
8       ./.git/objects/fa
8       ./.git/objects/1f
12      ./.git/objects/44
8       ./.git/objects/f2
8       ./.git/objects/a6
12      ./.git/objects/3d
8       ./.git/objects/3a
8       ./.git/objects/cd
8       ./.git/objects/b9
8       ./.git/objects/0b
12      ./.git/objects/72
8       ./.git/objects/91
12      ./.git/objects/64
12      ./.git/objects/2e
8       ./.git/objects/47
8       ./.git/objects/74
16      ./.git/objects/fb
12      ./.git/objects/17
8       ./.git/objects/e7
8       ./.git/objects/60
8       ./.git/objects/93
8       ./.git/objects/a3
8       ./.git/objects/fe
12      ./.git/objects/6e
8       ./.git/objects/ab
12      ./.git/objects/e5
8       ./.git/objects/4f
8       ./.git/objects/b2
8       ./.git/objects/83
8       ./.git/objects/7b
8       ./.git/objects/41
4       ./.git/objects/info
8       ./.git/objects/c3
8       ./.git/objects/0d
8       ./.git/objects/fc
12      ./.git/objects/d2
8       ./.git/objects/20
12      ./.git/objects/62
12      ./.git/objects/14
8       ./.git/objects/49
8       ./.git/objects/e9
2440    ./.git/objects
12      ./.git/logs/refs/remotes/origin
16      ./.git/logs/refs/remotes
8       ./.git/logs/refs/heads
28      ./.git/logs/refs
36      ./.git/logs
12      ./.git/refs/remotes/origin
16      ./.git/refs/remotes
4       ./.git/refs/tags
8       ./.git/refs/heads
32      ./.git/refs
4       ./.git/lfs/tmp
8       ./.git/lfs
4       ./.git/branches
68      ./.git/hooks
8       ./.git/info
2632    ./.git
1972    ./images
4624    .
```

5. Run the command **ls** . ***(1 mark)*** 
```bash
@maziqans ➜ /workspaces/NatSysProjectAss3 (main) $ ls
README.md  images
```

6. Run the command **ls -asl** . ***(1 mark)*** 
```bash
@maziqans ➜ /workspaces/NatSysProjectAss3 (main) $ ls -asl
total 32
 4 drwxrwxrwx+ 4 codespace root  4096 May 26 03:06 .
 4 drwxr-xrwx+ 5 codespace root  4096 May 26 03:06 ..
 4 drwxrwxrwx+ 9 codespace root  4096 May 26 03:11 .git
16 -rw-rw-rw-  1 codespace root 12741 May 26 03:09 README.md
 4 drwxrwxrwx+ 2 codespace root  4096 May 26 03:06 images
```

7. Run the command **free -h** . ***(1 mark)*** 
```bash
@maziqans ➜ /workspaces/NatSysProjectAss3 (main) $ free -h
              total        used        free      shared  buff/cache   available
Mem:          7.7Gi       1.4Gi       247Mi       1.0Mi       6.1Gi       6.0Gi
Swap:            0B          0B          0B
```

8. Run the command **cat /proc/cpuinfo** . ***(1 mark)*** 
```bash
@maziqans ➜ /workspaces/NatSysProjectAss3 (main) $ cat /proc/cpuinfo
processor       : 0
vendor_id       : AuthenticAMD
cpu family      : 25
model           : 1
model name      : AMD EPYC 7763 64-Core Processor
stepping        : 1
microcode       : 0xffffffff
cpu MHz         : 3243.904
cache size      : 512 KB
physical id     : 0
siblings        : 2
core id         : 0
cpu cores       : 1
apicid          : 0
initial apicid  : 0
fpu             : yes
fpu_exception   : yes
cpuid level     : 13
wp              : yes
flags           : fpu vme de pse tsc msr pae mce cx8 apic sep mtrr pge mca cmov pat pse36 clflush mmx fxsr sse sse2 ht syscall nx mmxext fxsr_opt pdpe1gb rdtscp lm constant_tsc rep_good nopl tsc_reliable nonstop_tsc cpuid extd_apicid aperfmperf pni pclmulqdq ssse3 fma cx16 pcid sse4_1 sse4_2 movbe popcnt aes xsave avx f16c rdrand hypervisor lahf_lm cmp_legacy svm cr8_legacy abm sse4a misalignsse 3dnowprefetch osvw topoext invpcid_single vmmcall fsgsbase bmi1 avx2 smep bmi2 erms invpcid rdseed adx smap clflushopt clwb sha_ni xsaveopt xsavec xgetbv1 xsaves clzero xsaveerptr rdpru arat npt nrip_save tsc_scale vmcb_clean flushbyasid decodeassists pausefilter pfthreshold v_vmsave_vmload umip vaes vpclmulqdq rdpid fsrm
bugs            : sysret_ss_attrs null_seg spectre_v1 spectre_v2 spec_store_bypass srso
bogomips        : 4890.86
TLB size        : 2560 4K pages
clflush size    : 64
cache_alignment : 64
address sizes   : 48 bits physical, 48 bits virtual
power management:

processor       : 1
vendor_id       : AuthenticAMD
cpu family      : 25
model           : 1
model name      : AMD EPYC 7763 64-Core Processor
stepping        : 1
microcode       : 0xffffffff
cpu MHz         : 3243.873
cache size      : 512 KB
physical id     : 0
siblings        : 2
core id         : 0
cpu cores       : 1
apicid          : 1
initial apicid  : 1
fpu             : yes
fpu_exception   : yes
cpuid level     : 13
wp              : yes
flags           : fpu vme de pse tsc msr pae mce cx8 apic sep mtrr pge mca cmov pat pse36 clflush mmx fxsr sse sse2 ht syscall nx mmxext fxsr_opt pdpe1gb rdtscp lm constant_tsc rep_good nopl tsc_reliable nonstop_tsc cpuid extd_apicid aperfmperf pni pclmulqdq ssse3 fma cx16 pcid sse4_1 sse4_2 movbe popcnt aes xsave avx f16c rdrand hypervisor lahf_lm cmp_legacy svm cr8_legacy abm sse4a misalignsse 3dnowprefetch osvw topoext invpcid_single vmmcall fsgsbase bmi1 avx2 smep bmi2 erms invpcid rdseed adx smap clflushopt clwb sha_ni xsaveopt xsavec xgetbv1 xsaves clzero xsaveerptr rdpru arat npt nrip_save tsc_scale vmcb_clean flushbyasid decodeassists pausefilter pfthreshold v_vmsave_vmload umip vaes vpclmulqdq rdpid fsrm
bugs            : sysret_ss_attrs null_seg spectre_v1 spectre_v2 spec_store_bypass srso
bogomips        : 4890.86
TLB size        : 2560 4K pages
clflush size    : 64
cache_alignment : 64
address sizes   : 48 bits physical, 48 bits virtual
power management:
```

9. Run the command **top** and type **q** to quit. ***(1 mark)*** 
```bash
processor       : 1
vendor_id       : AuthenticAMD
cpu family      : 25
model           : 1
model name      : AMD EPYC 7763 64-Core Processor
stepping        : 1
microcode       : 0xffffffff
cpu MHz         : 3243.873
cache size      : 512 KB
top - 03:25:07 up 46 min,  0 users,  load average: 0.15, 0.23, 0.25
Tasks:  17 total,   1 running,  16 sleeping,   0 stopped,   0 zombie
%Cpu(s):  3.2 us,  3.7 sy,  0.0 ni, 93.1 id,  0.0 wa,  0.0 hi,  0.0 si,  0.0 st
MiB Mem :   7929.6 total,    233.4 free,   1484.6 used,   6211.6 buff/cache
MiB Swap:      0.0 total,      0.0 free,      0.0 used.   6128.9 avail Mem 

    PID USER      PR  NI    VIRT    RES    SHR S  %CPU  %MEM     TIME+ COMMAND                                                                                                                
   2581 codespa+  20   0   21.1g 336844  46208 S   1.0   4.1   0:27.37 node                                                                                                                   
   3337 codespa+  20   0  726396  61236  38656 S   0.7   0.8   0:01.45 node                                                                                                                   
    900 root      20   0 1983432  87564  53376 S   0.3   1.1   0:00.38 dockerd                                                                                                                
      1 codespa+  20   0    1136    640    640 S   0.0   0.0   0:00.07 docker-init                                                                                                            
      7 codespa+  20   0    7236   1664   1664 S   0.0   0.0   0:00.01 sleep                                                                                                                  
     48 root      20   0   12196   3480   2560 S   0.0   0.0   0:00.00 sshd                                                                                                                   
    907 root      20   0 1798408  46624  30592 S   0.0   0.6   0:00.72 containerd                                                                                                             
   1660 codespa+  20   0    2616   1536   1536 S   0.0   0.0   0:00.00 sh                                                                                                                     
   1691 root      20   0    2616   1536   1536 S   0.0   0.0   0:00.00 sh                                                                                                                     
   2353 codespa+  20   0    2624   1664   1664 S   0.0   0.0   0:00.00 sh                                                                                                                     
   2380 codespa+  20   0  982052 122820  42240 S   0.0   1.5   0:06.07 node                                                                                                                   
   2652 codespa+  20   0  851240  55272  38784 S   0.0   0.7   0:00.24 node                                                                                                                   
   3856 codespa+  20   0  619064  69580  38144 S   0.0   0.9   0:00.67 node                                                                                                                   
   4309 codespa+  20   0    2616   1536   1536 S   0.0   0.0   0:00.00 sh                                                                                                                     
   4350 root      20   0    2616   1408   1408 S   0.0   0.0   0:00.00 sh                                                                                                                     
   4584 codespa+  20   0   16496  11392   3328 S   0.0   0.1   0:00.13 bash                                                                                                                   
  11829 codespa+  20   0   10880   3584   3200 R   0.0   0.0   0:00.00 top   
```

10. Run the command **uname -a**. ***(1 mark)*** 
```bash
@maziqans ➜ /workspaces/NatSysProjectAss3 (main) $ uname -a
Linux codespaces-4e5be1 6.5.0-1021-azure #22~22.04.1-Ubuntu SMP Tue Apr 30 16:08:18 UTC 2024 x86_64 x86_64 x86_64 GNU/Linux
```

11. What is the available free memory in the system. ***(1 mark)*** 
__6.0GiB__.
12. What is the available disk space mounted on /workspace. ***(1 mark)*** 
__20807708KB__.
13. Name the version and hardware architecture of the linux Virtual environment. ***(1 mark)*** 
__6.5.0-1021-azure #22~22.04.1-Ubuntu SMP Tue Apr 30 16:08:18 UTC 2024__.
14. What is the difference between **ls** vs **ls -asl**. ***(1 mark)*** 
__ls: display the list of files and folders__
__ls -asl: display the lists of files and folder including the hidden ones with detailed information__.
15. What is the TLB size of the Virtual CPU. ***(1 mark)*** 
__2560 4K pages__.
16. What is the CPU speed of the Virtual CPU. ***(1 mark)*** 
__3243.904 MHz__.
17. What is the top running process that consumes the most CPU cycles. ***(1 mark)*** 
__PID 2581__.

## Running your own container instance.

1. At the terminal, run a linux instance. By typing the following command. 
```
docker pull debian
docker run --detach -it debian
```
2. This will run the debian container. To check if the debian container is running, type
```bash
@joeynor ➜ /workspaces/OSProject (main) $ docker ps -a
CONTAINER ID   IMAGE     COMMAND   CREATED         STATUS         PORTS     NAMES
f65be1987f84   debian    "bash"    4 minutes ago   Up 4 minutes             romantic_jackson
```

3. Keep note of the name used by your container, this is usually given random names unless you specify your own name. Now run a bash command on the container. Make sure you use the name of your container instead of the one shown here. 
```bash
docker exec -i -t romantic_jackson /bin/bash
```

4. Create a file on the container. First you must make sure you are in the bash command prompt of the container. The container is new, and does not have any software other than the debian OS. To create a new file, you will need an editor installed. In the bash shell of the container, run the package manager apt-get to install nano text editor. 

```bash
root@f65be1987f84:~# apt-get update      

root@f65be1987f84:~# apt-get install nano

root@f65be1987f84:~# cd /root

root@f65be1987f84:~# nano helloworld.txt
```

5. Edit your helloworld.txt, create your messsage and save by typing ctrl-X. Once saved, explore using the container to see where the file is located. Then exit the shell, by typing **exit**.

6. Stop the container and run **docker ps -a**, and restart the container again. Is your file in the container still available?
```bash 
@joeynor ➜ /workspaces/OSProject (main) $ docker stop romantic_jackson

@joeynor ➜ /workspaces/OSProject (main) $ docker ps -a
CONTAINER ID   IMAGE     COMMAND   CREATED          STATUS                        PORTS     NAMES
f65be1987f84   debian    "bash"    19 minutes ago   Exited (137) 18 seconds ago             romantic_jackson

@joeynor ➜ /workspaces/OSProject (main) $ docker restart romantic_jackson
```

7. Stop the container and delete the container. What happened to your helloworld.txt?

```bash 
@joeynor ➜ /workspaces/OSProject (main) $ docker stop romantic_jackson

@joeynor ➜ /workspaces/OSProject (main) $ docker ps -a
CONTAINER ID   IMAGE     COMMAND   CREATED          STATUS                        PORTS     NAMES
f65be1987f84   debian    "bash"    19 minutes ago   Exited (137) 18 seconds ago             romantic_jackson

@joeynor ➜ /workspaces/OSProject (main) $ docker rm romantic_jackson
```

***Questions:***

1. Are files in the container persistent. Why not?. ***(1 mark)*** 
__No, because if we delete the container, everything in the container will be deleted as well__.
2. Can we run two, or three instances of debian linux? . ***(1 mark)*** 
__Yes__.

## Running your own container with persistent storage

1. In the previous experiment, you might have notice that containers are not persistent. To make storage persistent, you will need to mount them. 
At the terminal, create a new directory called **myroot**, and run a instance of debian linux and mount myroot to the container. Find out the exact path of my root, and mount it as the root folder in the debian container. 
2. Create a file in /root on the container, the files should also appear in myroot of your host VM.

```bash 
@joeynor ➜ /workspaces/OSProject (main) $ mkdir myroot
@joeynor ➜ /workspaces/OSProject (main) $ cd myroot/
@joeynor ➜ /workspaces/OSProject/myroot (main) $ pwd
/workspaces/OSProject/myroot

@joeynor ➜ /workspaces/OSProject/myroot (main) $ docker run --detach -it -v /workspaces/OSProject/myroot:/root debian
```

***Questions:***

1. Check the permission of the files created in myroot, what user and group is the files created in docker container on the host virtual machine? . ***(2 mark)*** 
__codespace user and codespcace group__.
2. Can you change the permission of the files to user codespace.  You will need this to be able to commit and get points for this question. ***(2 mark)***
```bash
//use sudo and chown
sudo chown -R codespace:codespace myroot

```
*** __Yes I can change the permission__.***

## You are on your own, create your own static webpage

1. Create a directory called webpage in your host machine
2. Inside the directory, create a page index.html, with any content you would like
3. Then, run the apache webserver and mount the webpage directory to it. Hint:
```bash
## the -p 8080:80 flag points the host port 8080 to the container port 80

docker run --detach -v /workspaces/OSProject/webpage:/usr/local/apache2/htdocs/ -p 8080:80 httpd
```

4. If it works, codespace will trigger a port assignment and provide a URL for you to access your webpage like the one below.

 <img src="./images/websitelink.png" width="70%">


5. You can also see the Port in the **PORTS** tab, next to the terminal tab.

6. You can then access your website by adding an index.html towards the end of your url link, like the one below. 

 <img src="./images/helloworldweb.png" width="70%">

***Questions:***

1. What is the permission of folder /usr/local/apache/htdocs and what user and group owns the folder? . ***(2 mark)*** 
__Permission :755 (rwxr-xr-x)__
__Owner: apache__
__Group: apache__.
2. What port is the apache web server running. ***(1 mark)***
__Port 80__
3. What port is open for http protocol on the host machine? ***(1 mark)***
__Port 8081 (because port 8080 is in use so I changed to :)__
```bash
-p 8081:80 httpd
```

## Create SUB Networks

1. In docker, you can create your own private networks where you can run multiple services, in this part, we will create two networks, one called bluenet and the other is rednet
2. Run the docker create network to create you networks like the ones below
```bash
## STEP 1:
## Create Networks ##
docker network create bluenet
docker network create rednet`

## STEP 2: (automatically running)
## Create (1) Container in background called "c1" running busybox image ##
docker run -itd --net bluenet --name c1 busybox sh
docker run -itd --net rednet --name c2 busybox sh
```
***Questions:***

1. Describe what is busybox and what is command switch **--name** is for? . ***(2 mark)*** 
__Busybox is a simplified version of linux dist. --name is for naming the container when it's created__.
2. Explore the network using the command ```docker network ls```, show the output of your terminal. ***(1 mark)***
```bash
@maziqans ➜ /workspaces/NatSysProjectAss3/webpage (main) $ docker network ls
NETWORK ID     NAME      DRIVER    SCOPE
ed83bdb2c689   bluenet   bridge    local
96c6690682fc   bridge    bridge    local
337086502c69   host      host      local
cad909293b18   none      null      local
5a48fc587cf3   rednet    bridge    local
```

3. Using ```docker inspect c1``` and ```docker inspect c2``` inscpect the two network. What is the gateway of bluenet and rednet.? ***(1 mark)***
```bash
@maziqans ➜ /workspaces/NatSysProjectAss3/webpage (main) $ docker inspect c1
[
    {
        "Id": "0faa07ad86c36d8c85785c7c8f3b2006c5b0c6ee1a13226310fcf3da76427a47",
        "Created": "2024-05-26T04:40:22.806611656Z",
        "Path": "sh",
        "Args": [],
        "State": {
            "Status": "running",
            "Running": true,
            "Paused": false,
            "Restarting": false,
            "OOMKilled": false,
            "Dead": false,
            "Pid": 44892,
            "ExitCode": 0,
            "Error": "",
            "StartedAt": "2024-05-26T04:40:23.35723163Z",
            "FinishedAt": "0001-01-01T00:00:00Z"
        },
        "Image": "sha256:65ad0d468eb1c558bf7f4e64e790f586e9eda649ee9f130cd0e835b292bbc5ac",
        "ResolvConfPath": "/var/lib/docker/containers/0faa07ad86c36d8c85785c7c8f3b2006c5b0c6ee1a13226310fcf3da76427a47/resolv.conf",
        "HostnamePath": "/var/lib/docker/containers/0faa07ad86c36d8c85785c7c8f3b2006c5b0c6ee1a13226310fcf3da76427a47/hostname",
        "HostsPath": "/var/lib/docker/containers/0faa07ad86c36d8c85785c7c8f3b2006c5b0c6ee1a13226310fcf3da76427a47/hosts",
        "LogPath": "/var/lib/docker/containers/0faa07ad86c36d8c85785c7c8f3b2006c5b0c6ee1a13226310fcf3da76427a47/0faa07ad86c36d8c85785c7c8f3b2006c5b0c6ee1a13226310fcf3da76427a47-json.log",
        "Name": "/c1",
        "RestartCount": 0,
        "Driver": "overlay2",
        "Platform": "linux",
        "MountLabel": "",
        "ProcessLabel": "",
        "AppArmorProfile": "docker-default",
        "ExecIDs": null,
        "HostConfig": {
            "Binds": null,
            "ContainerIDFile": "",
            "LogConfig": {
                "Type": "json-file",
                "Config": {}
            },
            "NetworkMode": "bluenet",
            "PortBindings": {},
            "RestartPolicy": {
                "Name": "no",
                "MaximumRetryCount": 0
            },
            "AutoRemove": false,
            "VolumeDriver": "",
            "VolumesFrom": null,
            "ConsoleSize": [
                24,
                232
            ],
            "CapAdd": null,
            "CapDrop": null,
            "CgroupnsMode": "private",
            "Dns": [],
            "DnsOptions": [],
            "DnsSearch": [],
            "ExtraHosts": null,
            "GroupAdd": null,
            "IpcMode": "private",
            "Cgroup": "",
            "Links": null,
            "OomScoreAdj": 0,
            "PidMode": "",
            "Privileged": false,
            "PublishAllPorts": false,
            "ReadonlyRootfs": false,
            "SecurityOpt": null,
            "UTSMode": "",
            "UsernsMode": "",
            "ShmSize": 67108864,
            "Runtime": "runc",
            "Isolation": "",
            "CpuShares": 0,
            "Memory": 0,
            "NanoCpus": 0,
            "CgroupParent": "",
            "BlkioWeight": 0,
            "BlkioWeightDevice": [],
            "BlkioDeviceReadBps": [],
            "BlkioDeviceWriteBps": [],
            "BlkioDeviceReadIOps": [],
            "BlkioDeviceWriteIOps": [],
            "CpuPeriod": 0,
            "CpuQuota": 0,
            "CpuRealtimePeriod": 0,
            "CpuRealtimeRuntime": 0,
            "CpusetCpus": "",
            "CpusetMems": "",
            "Devices": [],
            "DeviceCgroupRules": null,
            "DeviceRequests": null,
            "MemoryReservation": 0,
            "MemorySwap": 0,
            "MemorySwappiness": null,
            "OomKillDisable": null,
            "PidsLimit": null,
            "Ulimits": [],
            "CpuCount": 0,
            "CpuPercent": 0,
            "IOMaximumIOps": 0,
            "IOMaximumBandwidth": 0,
            "MaskedPaths": [
                "/proc/asound",
                "/proc/acpi",
                "/proc/kcore",
                "/proc/keys",
                "/proc/latency_stats",
                "/proc/timer_list",
                "/proc/timer_stats",
                "/proc/sched_debug",
                "/proc/scsi",
                "/sys/firmware",
                "/sys/devices/virtual/powercap"
            ],
            "ReadonlyPaths": [
                "/proc/bus",
                "/proc/fs",
                "/proc/irq",
                "/proc/sys",
                "/proc/sysrq-trigger"
            ]
        },
        "GraphDriver": {
            "Data": {
                "LowerDir": "/var/lib/docker/overlay2/de15a512a20184a828a2b6e78a37a8d9a11423c1428f4cce2c30decd8bbb3181-init/diff:/var/lib/docker/overlay2/82ea3050566af512147d84c3d508af130bdb7d9f96ca29e61e75d9dabc4de564/diff",
                "MergedDir": "/var/lib/docker/overlay2/de15a512a20184a828a2b6e78a37a8d9a11423c1428f4cce2c30decd8bbb3181/merged",
                "UpperDir": "/var/lib/docker/overlay2/de15a512a20184a828a2b6e78a37a8d9a11423c1428f4cce2c30decd8bbb3181/diff",
                "WorkDir": "/var/lib/docker/overlay2/de15a512a20184a828a2b6e78a37a8d9a11423c1428f4cce2c30decd8bbb3181/work"
            },
            "Name": "overlay2"
        },
        "Mounts": [],
        "Config": {
            "Hostname": "0faa07ad86c3",
            "Domainname": "",
            "User": "",
            "AttachStdin": false,
            "AttachStdout": false,
            "AttachStderr": false,
            "Tty": true,
            "OpenStdin": true,
            "StdinOnce": false,
            "Env": null,
            "Cmd": [
                "sh"
            ],
            "Image": "busybox",
            "Volumes": null,
            "WorkingDir": "",
            "Entrypoint": null,
            "OnBuild": null,
            "Labels": {}
        },
        "NetworkSettings": {
            "Bridge": "",
            "SandboxID": "264b2a4ef6a7d331a107d2a19c05d8274d595a0e3c9ac8d448d9003a5241572d",
            "SandboxKey": "/var/run/docker/netns/264b2a4ef6a7",
            "Ports": {},
            "HairpinMode": false,
            "LinkLocalIPv6Address": "",
            "LinkLocalIPv6PrefixLen": 0,
            "SecondaryIPAddresses": null,
            "SecondaryIPv6Addresses": null,
            "EndpointID": "",
            "Gateway": "",
            "GlobalIPv6Address": "",
            "GlobalIPv6PrefixLen": 0,
            "IPAddress": "",
            "IPPrefixLen": 0,
            "IPv6Gateway": "",
            "MacAddress": "",
            "Networks": {
                "bluenet": {
                    "IPAMConfig": null,
                    "Links": null,
                    "Aliases": null,
                    "MacAddress": "02:42:ac:12:00:02",
                    "NetworkID": "ed83bdb2c6898e2b6159de9661b1e80b6cd4d97bd1334715c57be1a1504e8b69",
                    "EndpointID": "7e8880399b9ecdff59225c06413938929d2fddea19da77d162648b8e32e6107b",
                    "Gateway": "172.18.0.1",
                    "IPAddress": "172.18.0.2",
                    "IPPrefixLen": 16,
                    "IPv6Gateway": "",
                    "GlobalIPv6Address": "",
                    "GlobalIPv6PrefixLen": 0,
                    "DriverOpts": null,
                    "DNSNames": [
                        "c1",
                        "0faa07ad86c3"
                    ]
                }
            }
        }
    }
]
@maziqans ➜ /workspaces/NatSysProjectAss3/webpage (main) $ docker inspect c2
[
    {
        "Id": "ffdd02e919ec863bf59d424b73e456b62861e2f6e5bd18eb6f7580f80857413c",
        "Created": "2024-05-26T04:40:38.059727252Z",
        "Path": "sh",
        "Args": [],
        "State": {
            "Status": "running",
            "Running": true,
            "Paused": false,
            "Restarting": false,
            "OOMKilled": false,
            "Dead": false,
            "Pid": 45098,
            "ExitCode": 0,
            "Error": "",
            "StartedAt": "2024-05-26T04:40:38.54328953Z",
            "FinishedAt": "0001-01-01T00:00:00Z"
        },
        "Image": "sha256:65ad0d468eb1c558bf7f4e64e790f586e9eda649ee9f130cd0e835b292bbc5ac",
        "ResolvConfPath": "/var/lib/docker/containers/ffdd02e919ec863bf59d424b73e456b62861e2f6e5bd18eb6f7580f80857413c/resolv.conf",
        "HostnamePath": "/var/lib/docker/containers/ffdd02e919ec863bf59d424b73e456b62861e2f6e5bd18eb6f7580f80857413c/hostname",
        "HostsPath": "/var/lib/docker/containers/ffdd02e919ec863bf59d424b73e456b62861e2f6e5bd18eb6f7580f80857413c/hosts",
        "LogPath": "/var/lib/docker/containers/ffdd02e919ec863bf59d424b73e456b62861e2f6e5bd18eb6f7580f80857413c/ffdd02e919ec863bf59d424b73e456b62861e2f6e5bd18eb6f7580f80857413c-json.log",
        "Name": "/c2",
        "RestartCount": 0,
        "Driver": "overlay2",
        "Platform": "linux",
        "MountLabel": "",
        "ProcessLabel": "",
        "AppArmorProfile": "docker-default",
        "ExecIDs": null,
        "HostConfig": {
            "Binds": null,
            "ContainerIDFile": "",
            "LogConfig": {
                "Type": "json-file",
                "Config": {}
            },
            "NetworkMode": "rednet",
            "PortBindings": {},
            "RestartPolicy": {
                "Name": "no",
                "MaximumRetryCount": 0
            },
            "AutoRemove": false,
            "VolumeDriver": "",
            "VolumesFrom": null,
            "ConsoleSize": [
                24,
                232
            ],
            "CapAdd": null,
            "CapDrop": null,
            "CgroupnsMode": "private",
            "Dns": [],
            "DnsOptions": [],
            "DnsSearch": [],
            "ExtraHosts": null,
            "GroupAdd": null,
            "IpcMode": "private",
            "Cgroup": "",
            "Links": null,
            "OomScoreAdj": 0,
            "PidMode": "",
            "Privileged": false,
            "PublishAllPorts": false,
            "ReadonlyRootfs": false,
            "SecurityOpt": null,
            "UTSMode": "",
            "UsernsMode": "",
            "ShmSize": 67108864,
            "Runtime": "runc",
            "Isolation": "",
            "CpuShares": 0,
            "Memory": 0,
            "NanoCpus": 0,
            "CgroupParent": "",
            "BlkioWeight": 0,
            "BlkioWeightDevice": [],
            "BlkioDeviceReadBps": [],
            "BlkioDeviceWriteBps": [],
            "BlkioDeviceReadIOps": [],
            "BlkioDeviceWriteIOps": [],
            "CpuPeriod": 0,
            "CpuQuota": 0,
            "CpuRealtimePeriod": 0,
            "CpuRealtimeRuntime": 0,
            "CpusetCpus": "",
            "CpusetMems": "",
            "Devices": [],
            "DeviceCgroupRules": null,
            "DeviceRequests": null,
            "MemoryReservation": 0,
            "MemorySwap": 0,
            "MemorySwappiness": null,
            "OomKillDisable": null,
            "PidsLimit": null,
            "Ulimits": [],
            "CpuCount": 0,
            "CpuPercent": 0,
            "IOMaximumIOps": 0,
            "IOMaximumBandwidth": 0,
            "MaskedPaths": [
                "/proc/asound",
                "/proc/acpi",
                "/proc/kcore",
                "/proc/keys",
                "/proc/latency_stats",
                "/proc/timer_list",
                "/proc/timer_stats",
                "/proc/sched_debug",
                "/proc/scsi",
                "/sys/firmware",
                "/sys/devices/virtual/powercap"
            ],
            "ReadonlyPaths": [
                "/proc/bus",
                "/proc/fs",
                "/proc/irq",
                "/proc/sys",
                "/proc/sysrq-trigger"
            ]
        },
        "GraphDriver": {
            "Data": {
                "LowerDir": "/var/lib/docker/overlay2/e9d4cc8a991f0938241b06c693fc4c4a278a73fbbca9535eada84135f8ec2217-init/diff:/var/lib/docker/overlay2/82ea3050566af512147d84c3d508af130bdb7d9f96ca29e61e75d9dabc4de564/diff",
                "MergedDir": "/var/lib/docker/overlay2/e9d4cc8a991f0938241b06c693fc4c4a278a73fbbca9535eada84135f8ec2217/merged",
                "UpperDir": "/var/lib/docker/overlay2/e9d4cc8a991f0938241b06c693fc4c4a278a73fbbca9535eada84135f8ec2217/diff",
                "WorkDir": "/var/lib/docker/overlay2/e9d4cc8a991f0938241b06c693fc4c4a278a73fbbca9535eada84135f8ec2217/work"
            },
            "Name": "overlay2"
        },
        "Mounts": [],
        "Config": {
            "Hostname": "ffdd02e919ec",
            "Domainname": "",
            "User": "",
            "AttachStdin": false,
            "AttachStdout": false,
            "AttachStderr": false,
            "Tty": true,
            "OpenStdin": true,
            "StdinOnce": false,
            "Env": null,
            "Cmd": [
                "sh"
            ],
            "Image": "busybox",
            "Volumes": null,
            "WorkingDir": "",
            "Entrypoint": null,
            "OnBuild": null,
            "Labels": {}
        },
        "NetworkSettings": {
            "Bridge": "",
            "SandboxID": "74dbad93e04db158d5225aa5f7d4fe94846005fe148f6313cd298baf3c380014",
            "SandboxKey": "/var/run/docker/netns/74dbad93e04d",
            "Ports": {},
            "HairpinMode": false,
            "LinkLocalIPv6Address": "",
            "LinkLocalIPv6PrefixLen": 0,
            "SecondaryIPAddresses": null,
            "SecondaryIPv6Addresses": null,
            "EndpointID": "",
            "Gateway": "",
            "GlobalIPv6Address": "",
            "GlobalIPv6PrefixLen": 0,
            "IPAddress": "",
            "IPPrefixLen": 0,
            "IPv6Gateway": "",
            "MacAddress": "",
            "Networks": {
                "rednet": {
                    "IPAMConfig": null,
                    "Links": null,
                    "Aliases": null,
                    "MacAddress": "02:42:ac:13:00:02",
                    "NetworkID": "5a48fc587cf349f90863312dbb44519b371bd1af63090eb424d3d566d996cbe8",
                    "EndpointID": "4fd746117fa72ecb9cb6d3498ec7e081757dc8a56ce8ba22520f11fc257068bd",
                    "Gateway": "172.19.0.1",
                    "IPAddress": "172.19.0.2",
                    "IPPrefixLen": 16,
                    "IPv6Gateway": "",
                    "GlobalIPv6Address": "",
                    "GlobalIPv6PrefixLen": 0,
                    "DriverOpts": null,
                    "DNSNames": [
                        "c2",
                        "ffdd02e919ec"
                    ]
                }
            }
        }
    }
]
```
__Inspecting the gateway__
```bash
@maziqans ➜ /workspaces/NatSysProjectAss3/webpage (main) $ docker network inspect bluenet | grep Gateway
                    "Gateway": "172.18.0.1"
@maziqans ➜ /workspaces/NatSysProjectAss3/webpage (main) $ docker network inspect rednet | grep Gateway
                    "Gateway": "172.19.0.1"
```
__Gateway bluenet : 172.18.0.1__
__Gateway rednet : 172.19.0.1__                    

4. What is the network address for the running container c1 and c2.
```bash
@maziqans ➜ /workspaces/NatSysProjectAss3/webpage (main) $ docker inspect c1 | grep IPAddress
            "SecondaryIPAddresses": null,
            "IPAddress": "",
                    "IPAddress": "172.18.0.2",
@maziqans ➜ /workspaces/NatSysProjectAss3/webpage (main) $ docker inspect c2 | grep IPAddress
            "SecondaryIPAddresses": null,
            "IPAddress": "",
                    "IPAddress": "172.19.0.2",
```
__Network Address c1 : 172.18.0.2__
__Network Address c2 : 172.19.0.2__ 

5. Using the command ```docker exec c1 ping c2```, which basically issue a ping from container c1 to c2. Are you able to ping? Show your output . ***(1 mark)***
```bash
@maziqans ➜ /workspaces/NatSysProjectAss3/webpage (main) $ docker exec c1 ping c2
ping: bad address 'c2'
```

## Bridging two SUB Networks
1. Let's try this again by creating a network to bridge the two containers in the two subnetworks
```
docker network create bridgenet
docker network connect bridgenet c1
docker network connect bridgenet c2
docker exec c1 ping c2
```

Result:
```bash
@maziqans ➜ /workspaces/NatSysProjectAss3/webpage (main) $ docker network create bridgenet
52d63630ac8b59af600b6bc0485e7f84a76ad0148a49b663dbc6dfd9d84a7fe4
@maziqans ➜ /workspaces/NatSysProjectAss3/webpage (main) $ docker network connect bridgenet c1
@maziqans ➜ /workspaces/NatSysProjectAss3/webpage (main) $ docker network connect bridgenet c2
@maziqans ➜ /workspaces/NatSysProjectAss3/webpage (main) $ docker exec c1 ping c2
PING c2 (172.20.0.3): 56 data bytes
64 bytes from 172.20.0.3: seq=0 ttl=64 time=0.125 ms
64 bytes from 172.20.0.3: seq=1 ttl=64 time=0.072 ms
64 bytes from 172.20.0.3: seq=2 ttl=64 time=0.067 ms
64 bytes from 172.20.0.3: seq=3 ttl=64 time=0.065 ms
64 bytes from 172.20.0.3: seq=4 ttl=64 time=0.113 ms
64 bytes from 172.20.0.3: seq=5 ttl=64 time=0.088 ms
64 bytes from 172.20.0.3: seq=6 ttl=64 time=0.076 ms
64 bytes from 172.20.0.3: seq=7 ttl=64 time=0.088 ms
64 bytes from 172.20.0.3: seq=8 ttl=64 time=0.075 ms
64 bytes from 172.20.0.3: seq=9 ttl=64 time=0.076 ms
^C
```

## What to submit

1. Make sure to commit all changes on your source control, and make sure your source control is sync to the repository. 
2. Check your repository link, to see if all the files and answers are included in the repository. 
3. Submit through italeem, by providing the link to your repository.
4. Due by ***30 May, 2024***
