# ProjetMogenius
Etape pour le déploiement d'un service Nginx sur Docker
## créer une image 
`docker image build ./ -t docker-nginx:1.0.0`

## créer un container 
`docker container create -p 2222:80 docker-nginx:1.0.0`

## Exécuter ce container
`docker container start 312b8278e11373cb3211faeab53b7f0b47e996b5e84fc58`
