# Usage 

Place the file **sonar-project.properties** inside your project directory and run the following:
```sh
docker pull luisgros/sonarqube
docker run -v $(pwd):/src -p 9000:9000 luisgros/sonarqube
```
