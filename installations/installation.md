## Installation of Java 🔗

```
sudo apt update
```

```
sudo apt install fontconfig openjdk-21-jre
```

### Check Java Version

```
java -version
```


## Instllation of Jenkins

```
sudo wget -O /etc/apt/keyrings/jenkins-keyring.asc \
  https://pkg.jenkins.io/debian-stable/jenkins.io-2023.key
echo "deb [signed-by=/etc/apt/keyrings/jenkins-keyring.asc]" \
  https://pkg.jenkins.io/debian-stable binary/ | sudo tee \
  /etc/apt/sources.list.d/jenkins.list > /dev/null
sudo apt update
sudo apt install jenkins
```

## Start Jenkins

```
sudo systemctl enable jenkins
```


### You can start the Jenkins service with the command:

```
sudo systemctl start jenkins
```

### You can check the status of the Jenkins service using the command:

```
sudo systemctl status jenkins
```

