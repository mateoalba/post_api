nest generate module basics
nest generate controller basics
nest generate service basics


GIT_SSH_COMMAND='ssh -i ~/.ssh/github_deploy' git clone git@github.com:mateoalba/post_api.git /opt/posts_api




ssh-ed25519 AAAAC3NzaC1lZDI1NTE5AAAAIHAJO7BuFMSWEBQhTRyqSvKmxUfzCW6Cb+ObUbKhr/oz gh-actions-root
pm2 start dist/main.js --name nestjs-posts-api