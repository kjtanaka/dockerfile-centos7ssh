# kjtanaka/centos7ssh

https://hub.docker.com/r/kjtanaka/centos7ssh/

```bash
docker run -p 2233:22 --name=cn01 -e AUTHORIZED_KEYS="$(cat ~/.ssh/id_rsa.pub)" -dt kjtanaka/centos7ssh
ssh -p 2233 -l root localhost
```
