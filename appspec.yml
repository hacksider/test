version: 0.0
os: linux
files:
  - source: /index.html
    destination: /var/www/myzler/public_html/

hooks:
  AfterInstall:
    - location: scripts/updatelinux.sh
      timeout: 3000
      runas: root

