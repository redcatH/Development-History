# Gitlab-runer

## Docker安装

1. docker pull gitlab/gitlab-runner:latest
2. docker run -d --name gitlab-runner --restart always -v gitlab-runner-home:/home/gitlab-runner -v gitlab-runner-config:/etc/gitlab-runner -v /var/run/docker.sock:/var/run/docker.sock gitlab/gitlab-runner:latest