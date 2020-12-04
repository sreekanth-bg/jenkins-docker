# Jenkins docker
* Jenkins CI with docker client


find GID of docker using: ```cat /etc/group |grep docker``` or ```getent group docker```  
If GID is other than 999, replace in line 9: ```groupadd -g 999 docker && \```
