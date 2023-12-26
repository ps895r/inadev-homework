# inadev-homework
launch eks cluster and install Jenkins

to setup, there is a launcher script that needs to be pulled first. This launch.sh script pulls down this repo and builds the eks cluster and installs Jenkins into that cluster. The launch.sh then downloads several git/docker plugins, sets up the connection with GitHub to pull in the weather app and uses the jenkins cli to automate creating a pipeline job to run the Jenkinsfile located within the inadev-weather repo. 

weather app:
https://github.com/ps895r/inadev-weather

launcher repo:
https://github.com/ps895r/launch-inadev-homework


