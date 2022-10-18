pipeline {
  agent any
  tools {
    maven 'maven-3.8.6'
  }
  stages {
    stage ('Build') {
      steps {
        sh 'mvn clean compile && mvn exec:java -Dexec.mainClass="org.example.Main"'
      }
    }
  }
}

