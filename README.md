## Local Installation and Testing

### Installation 

Make sure you have **NodeJS** install and `npm` command works at the command line. If Yes, run the following commands in root folder of this project to run the project.

```sh 
# To build 
npm install 

# To run
npm start
```

### Testing 

While the server is running hit the URL [http://127.0.0.1:8080/api](http://127.0.0.1:8080/api)

## On OpenShift 

```sh 
# To deploy a new app in your current namespace
oc new-app https://github.com/vchintal/wu-svc-a.git

# To expose the route 
oc expose service wu-svc-a --path=/api
```
