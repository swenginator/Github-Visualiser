# Github-Visualiser

### Prerequisites
To run this project, you will need the following installed:

- Docker

### Running the Project
Navigate to the `github-visualiser` folder and run the following terminal commands:

```
docker build -t <your_image_name> .
docker run -it -p 8080:8080 --rm <your_image_name>
```
The docker container is now running and the project should be accessible on `localhost:8080`.
