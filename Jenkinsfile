// Declarative //
pipeline {
agent any 
  
  stages {
    stage("build"){
      steps {
      echo "Hello GitHub!"
      }
    } 
  
  }/*{
docker { image 'node:7-alpine' }
}
stages {
stage('Test') {
steps {
sh 'node --version'
}
}
}
}
// Script //
node {
/* Requires the Docker Pipeline plugin to be installed */
/*docker.image('node:7-alpine').inside {
stage('Test') {
sh 'node --version'
}
}*/
}
