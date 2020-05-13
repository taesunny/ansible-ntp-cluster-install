# Install ntp cluster using ansible (Ansible을 이용한 ntp 클러스터 구성)

## Command example (커맨드 실행 예제)
```
ansible-playbook -i hosts.ini npt_playbook_ubuntu.yaml
```

## Choose one ntp server config files in two files below (적절한 ntp config 파일을 선택해주세요)
```
ntp.server.remote.conf.j2 : set server to look time self
ntp.server.self.conf.j2 : for use remote ntp servers using network
```

## Ansible Installing Script for ubuntu

[Ansible installing script for ubuntu]



[Ansible installing script for ubuntu]: install_ansible.sh