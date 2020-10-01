[![Docker Image CI](https://github.com/shunak/docker-nginx-for-react-typescript-production-environment/workflows/Docker%20Image%20CI/badge.svg)](https://github.com/shunak/docker-nginx-for-react-typescript-production-environment/actions?query=workflow%3A%22Docker+Image+CI%22)
# How to use
after you used [this development environment](https://github.com/shunak/docker-react-typescript-development-environment), this repos will help you.<br>
## install
before install this, you must make production artifact directory in development dir on [this](https://github.com/shunak/docker-react-typescript-development-environment)<br>
how to make this is, in the development dir, <br>
```
yarn build
```
makes production artifact directory ``build/`` <br>
To use this, you must make this ``build/`` directory before installation.


```
git clone https://github.com/shunak/docker-nginx-for-react-typescript-production-environment.git
``` 
```
cd docker-nginx-for-react-typescript-production-environment
```
```
cp docker-compose.yml ../
```
```
cp Dockerfile ../
```

