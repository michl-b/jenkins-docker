# Jenkins Setup for Docker usage

The compose file starts a jenkins:alpine container on port 10080 with a volume to local home folder jenkins_home

## run
```bash
# clone git repo
git clone https://github.com/michl-b/jenkins-docker.git

# create folder for volume mount-point
cd jenkins-docker
mkdir jenkins_home

# run container detached (-d)
docker-compose up -d
```
