# ELK_Swarm
ELK stack on docker swarm

Prerequisites for the volume mappings and repository data
Elasticsearch persistence on docker swarm nodes. This is originally assuming one data node for now.
mkdir /data/master
mkdir /data/gateway
mkdir /data/data
mkdir /data/ingest
mount -t nfs4 192.168.168.213:/ELK /mnt/backups
mkdir /conf
