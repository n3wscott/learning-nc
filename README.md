# learning-nc
Node Containers


- [x] Starting with https://nodejs.org/en/docs/guides/nodejs-docker-webapp/

- [ ] Follow up with tips in https://betterprogramming.pub/docker-for-node-js-in-production-b9dc0e9e48e0


pack build --builder=gcr.io/buildpacks/builder learning-node
docker run -it -ePORT=8080 -p8080:8080 learning-node