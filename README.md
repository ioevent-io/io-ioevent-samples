# IO Event Sample Applications
This repository contains a collection of applications written using IO Event. All the applications are self contained. They must run on Kafka middleware technologies. You have the option of running the samples against local or Docker containerized versions of Kafka. For convenience, `docker-compose.yml` files are provided as part of each application wherever it is applicable. For this reason, Docker Compose is required and it’s recommended to use the latest version. These compose files bring up the middleware Kafka and other necessary components for running each app. If you bring up Kafka in Docker containers, please make sure that you bring them down while in the same sample directory. You can read the README that is part of each sample and follow along the instructions to run them.

You can build the entire samples by going to the root of the repository and then do: ./mvnw clean package However, the recommended approach to build them is to pick the sample that you are interested in and go to that particular app and follow the instructions there in the README for that app.

# Following is the list of various sample applications provided

## Source samples

* Hello World Sample

![alt text](https://raw.githubusercontent.com/ioevent-io/io-ioevent-samples/main/ioevent-hello-world/ioevent-hello-world-diagram.jpg)

* Exclusive Gateway Sample

![alt text](https://raw.githubusercontent.com/ioevent-io/io-ioevent-samples/main/ioevent-exclusive-sample/ioevent-exclusive-flow-exemple.jpg)

* Parallel Gateway Sample

![alt text](https://raw.githubusercontent.com/ioevent-io/io-ioevent-samples/main/ioevent-parallel-sample/ioevent-parrallel-flow-exemple.jpg)

* File Processing Sample

![alt text](https://raw.githubusercontent.com/ioevent-io/io-ioevent-samples/main/ioevent-file-processing/ioevent-file-processing-exemple.jpg)

* Error handling Sample

![alt text](https://raw.githubusercontent.com/ioevent-io/io-ioevent-samples/main/ioevent-error-handling-sample/ioevent-error-handling-flow-sample.jpg)

* Error End Sample

![alt text](https://raw.githubusercontent.com/ioevent-io/io-ioevent-samples/main/ioevent-error-end/io-event-error-end-flow-sample.jpg)

* Start Timer Sample

![alt text](https://raw.githubusercontent.com/ioevent-io/io-ioevent-samples/main/ioevent-start-timer/ioevent-start-timer-exemple.jpg)

* Intermediate Timer Sample

![alt text](https://raw.githubusercontent.com/ioevent-io/io-ioevent-samples/main/ioevent-intermediate-timer/ioevent-intermediate-timer-exemple.jpg)