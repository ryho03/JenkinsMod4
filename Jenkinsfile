pipeline {
   agent any
   stages {
      stage('init') {
          steps {
            sh 'chmod +x init.sh'
            sh 'sh init.sh'
          }
      }
      stage('Build') {
          steps {
            sh 'chmod +x build.sh'
            sh 'sh build.sh'
          }
      }
      stage('Deploy') {
          steps {
            sh 'chmod +x deploy.sh'
            sh 'sh deploy.sh'
          }
      }      
   }
}
