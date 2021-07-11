# SCA-Cloud-School-Application

## Prerequisities
In order to run this container you'll need docker installed.

## How to clone project repository

You can clone this repository via

### Github
`git clone https://github.com/rafiatdaniju/SCA-Cloud-School-Application.git`

or 

### Dockerhub
`docker pull rafiat/sca-app`


## How to run the container
### From Github
You will first build using the command 
`docker build -t sca-cloud-update .`

then run, using
`docker run -d --name app-container -p 80:80 sca-cloud-update`

### From Dockerhub
`docker run -d --name app-container -p 80:80 rafiat/sca-app `

## Note !!!
1.  `app-container` can be replaced with any name you want to name your container
2.  `-p 80:80` is the port number


## Expected Behaviour

<img width="1439" alt="Screen Shot 2021-07-11 at 9 43 50 PM" src="https://user-images.githubusercontent.com/52916285/125210230-4aa17880-e296-11eb-9e07-7c0b7f69d561.png">
