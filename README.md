# Programming-Formative-POE-3

DockerFile run Instructions
1.docker build -t raceday-mvc -f RaceDay.Web/Dockerfile .
2.docker run -d -p 8080:8080 --name raceday-mvc-container raceday-mvc
3.docker stop raceday-mvc-container
4.docker rm raceday-mvc-container
