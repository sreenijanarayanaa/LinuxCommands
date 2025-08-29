# 🔹 File & Directory Management

pwd      →      print working directory

ls -l / ls -la      →      list files (long format, hidden files)

cd      →      change directory

mkdir      →      create directory

rmdir      →      remove empty directory

rm -rf      →      remove files/directories recursively

touch file.txt      →      create an empty file

cp src dest      →      copy files/directories

mv old new      →      move/rename file/directory

find . -name "*.log"      →      search files by name

tree      →      show directory structure (if installed)

# 🔹 File Viewing & Editing

cat file.txt      →      view file contents

less file.txt      →      scroll through file (q to quit)

head -n 20 file.txt      →      show first 20 lines

tail -n 50 file.txt      →      show last 50 lines

tail -f app.log      →      live stream logs

nano file.txt / vim file.txt      →      edit files

# 🔹 Permissions & Ownership

ls -l      →      check file permissions

chmod 755 file.sh      →      change permissions

chown user:group file.txt      →      change owner

whoami      →      current user

# 🔹 Process & System Monitoring

ps aux      →      list processes

top / htop      →      monitor system usage

kill -9 PID      →      force kill a process

jobs / fg / bg      →      job control in shell

uptime      →      how long system is running

df -h      →      disk usage

du -sh folder/      →      folder size

free -m      →      memory usage

# 🔹 Networking

ping google.com      →      test connectivity

curl -I https://example.com      →      check response headers

wget URL      →      download files

ifconfig / ip a      →      network details

netstat -tulnp      →      check ports & connections

ss -ltnp      →      modern replacement for netstat

# 🔹 Search & Filters

grep "error" file.log      →      search text in files

grep -r "TODO" src/      →      recursive search

sort file.txt      →      sort lines

uniq -c file.txt      →      unique lines with count

wc -l file.txt      →      count lines

cut -d',' -f2 file.csv      →      extract column 2

awk '{print $1,$3}' file.txt      →      print fields

sed 's/foo/bar/g' file.txt      →      replace text

# 🔹 Archiving & Compression

tar -cvf archive.tar dir/      →      create tarball

tar -xvf archive.tar      →      extract tarball

tar -czvf archive.tar.gz dir/      →      compress

tar -xzvf archive.tar.gz      →      extract compressed tar

zip -r archive.zip dir/ / unzip archive.zip

# 🔹 Package Management (depends on OS)

apt update && apt upgrade (Debian/Ubuntu)

yum install package (CentOS/RHEL)

dnf install package (Fedora)

# 🔹 Git & Version Control (most common ones)

git clone repo_url

git status

git add .

git commit -m "msg"

git push origin branch

git pull

# 🔹 Docker & Containers (if you work with devops)

docker ps      →      list running containers

docker images      →      list images

docker exec -it container bash      →      enter container

docker logs -f container      →      stream container logs

# 🔹 Others

history      →      show command history

!!      →      repeat last command

!123      →      run command from history number

alias gs="git status"      →      create shortcuts

man command      →      open manual page

which java      →      locate executable
