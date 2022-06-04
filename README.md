# Ansible을 이용하여 NFS Server 및 Client 설정

## 1. NFS Server 작업 순서
1. nfs 패키지 설치 
2. 공유할 디렉토리 생성 및 권한 부여 
3. 공유 디렉토리 설정 (/etc/exports)
4. nfs 서비스 재시작 
<br />    
<br />    

## 2. NFS Client 작업 순서
1. nfs 패키지 설치 
2. 마운트할 공유 디렉토리 생성 
3. Mount

<br />    
<br />    

## 3. 실행 방법
```
$ ansible-playbook nfs_adv.yml -k
```