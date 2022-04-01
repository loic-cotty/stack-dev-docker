git init
git add .
git commit -m "first commit"
git branch -M main
git remote add origin git@github.com:loic-cotty/stack-dev-docker.git
git push -u origin main




database
    -> Dockerfile
nginx
    conf.d
        -> default.conf
    sites
        -> documentroot.conf
    -> Dockerfile
    -> nginx.conf
php-fpm
    ->Dockerfile
docker-compose.yml

