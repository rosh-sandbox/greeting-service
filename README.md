## Welcome Greeting Service

This project is a demo project to show how to use free could devops services to set up a continuous integration.

**Build**
Maven is used as the build tool.

**Repository**
Github is the repository for the source code.
https://github.com/rosh-sandbox/greeting-service

**Build Server**
Travis CI is used as the build server.
https://travis-ci.org/rosh-sandbox/greeting-service

**Artifact Repository**
Built release artifacts are uploaded in to the bitray based maven repository server.
https://bintray.com/roshinnovations/public-api/gs-rest-service

**Deployment**
Succesfully build artifacts are deployed in heroku PaaS as a Java based web app.
https://dashboard.heroku.com/apps/my-greeting-service

**Access Service**
The deployed REST API could be accessed with the following url:
https://my-greeting-service.herokuapp.com/greeting

**Performance Test**
The performance test for the public api is configured here:
https://loader.io/tests/38be44f41ce18511c6fbcfb5c1e52529





