```
1069  docker ps
 1070  docker images
 1071  docker version
 1072  docker container ls
 1073  docker ps
 1074  docker ps -a
 1075  docker run busybox echo "Welcome to Docker"
 1076  docker ps
 1077  docker ps -a
 1078  docker run -it busybox
 1079  docker ps
 1080  docker ps -a
 1081  docker start 56c05a336040
 1082  docker ps
 1083  docker attach 56c05a336040
 1084  docker ps
 1085  docker rename stoic_tesla test-1
 1086  docker ps
 1087  docker inspect test-1
 1088  history
 1089  docker ps
 1090  docker stop test-1
 1091  docker ps
 1092  docker ps -a
 1093  docker rm test-1
 1094  docker ps
 1095  docker ps -a
 1096  docker ps -aq
 1097  docker rm $(docker ps -aq)
 1098  docker ps -a
 1099  docker images
 1100  docker run -d --name test-2 amitvashist7/k8s-tiny-web:2
 1101  docker images
 1102  docker ps
 1103  docker inspect  test-2
 1104  curl 172.17.0.2
 1105  ip addr
 1106  route -n
 1107  docker inspect  test-2
 1108  ls
 1109  docker run -d --name test-3 -p 8081:80 amitvashist7/k8s-tiny-web:2
 1110  docker ps
 1111  netstat -tunlp
 1112  systemctl  status docker
 1113  docker run -d --name test-4 -P amitvashist7/k8s-tiny-web:2
 1114  docker ps

```
