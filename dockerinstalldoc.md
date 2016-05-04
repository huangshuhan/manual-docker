Docker的安装  
备注说明：官网推荐安装的centos的版本是7.0，linux内核要求是3.x以上的，这次docker安装服务器是centos6.5内核是2.x，就无法用官网推荐的使用安装。    
故查找别的资料安装的docker。    
安装连接地址：http://www.linuxidc.com/Linux/2015-01/111091.htm  


运行命令docker version的结果，查看版本信息    
Client version: 1.7.1  
Client API version: 1.19  
Go version (client): go1.4.2  
Git commit (client): 786b29d/1.7.1  
OS/Arch (client): linux/amd64

安装完成以后运行docker info的命令，查看其他信息。例如镜像数量等。(注：运行docker info命令时，需要先运行docker服务 service docker start)
Containers: 0  
Images: 0  
Storage Driver: devicemapper  
 Pool Name: docker-253:0-2360287-pool  
 Pool Blocksize: 65.54 kB  
 Backing Filesystem: extfs  
 Data file: /dev/loop0  
 Metadata file: /dev/loop1  
 Data Space Used: 305.7 MB  
 Data Space Total: 107.4 GB  
 Data Space Available: 43.79 GB  
 Metadata Space Used: 733.2 kB  
 Metadata Space Total: 2.147 GB  
 Metadata Space Available: 2.147 GB  
 Udev Sync Supported: true  
 Deferred Removal Enabled: false  
 Data loop file: /var/lib/docker/devicemapper/devicemapper/data  
 Metadata loop file: /var/lib/docker/devicemapper/devicemapper/metadata  
 Library Version: 1.02.95-RHEL6 (2015-09-08)  
Execution Driver: native-0.2  
Logging Driver: json-file  
Kernel Version: 2.6.32-431.el6.x86_64  
Operating System: <unknown>  
CPUs: 4  
Total Memory: 7.632 GiB  
Name: asus  
ID: JNCO:XF3E:732D:VBTL:HHW2:IGK4:RP6G:HYJB:RDDR:VCKW:2HAB:MNQT

总结：  
docker的安装是比较简单，只要按照步骤来，安装完成以后，运行相关的查询版本命令，就知道docker是否安装完成了.  