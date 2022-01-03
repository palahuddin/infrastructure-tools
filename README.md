# Infrastructure Tools

Script for installing common tools of insfrastructure
*## this is still in development stage ##*

## Script
Downloading via curl

```bash
curl -o infrastr https://raw.githubusercontent.com/palahuddin/infrastructure-tools/master/infrastr && chmod +x infrastr
```

## Usage

```bash
infrastr -c <command> -s <service>

### 'pick' install

infrastr -c <command> -s pick <service[1]> <service[2]> <service[3]> ...
```

## Help
```bash
infrastr Script, Personal Infrastructure Setup Purpose For Common Tools

Usage:
   infrastr -c <command> -s <service>

Usage multiple install 'pick' Service:
   infrastr -c  <command> -s pick <service name[1]> <service name[2]> <service name[3]> ...

Options:
   -c <command>
   -s <service name>

Available commands: 
   install  <install service>
   setup    <setup service>

Available 'install' services:
   all            Setup All Services
   golang         Installing golang 
   mc             Installing minio client 
   java           Installing java 
   nodejs         Installing nodejs 
   pm2            Installing pm2 
   docker         Installing docker 
   kubectl        Installing kubectl 
   helm           Installing Helm 
   compose        Installing docker compose 
   ansible        Installing ansible 
   terraform      Installing terraform 
   rke2           Setup RKE2 Kubernetes CLuster


Available 'setup' services:
   nginx          Deploy nginx and certbot
   harbor         Opensource container registry
   minio          Opensource object storage
   kind           Local Kubernetes Cluster Development 
```

#

