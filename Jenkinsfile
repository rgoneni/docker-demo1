node {
        stage ('clone repository') {
        checkout scm
    }
        stage ('build image') {
        app = docker.build("alpine-docker:1.0")
        }
        
  }
   
